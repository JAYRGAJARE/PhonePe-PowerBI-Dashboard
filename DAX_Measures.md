# DAX Measures — Reference

> The exact measure names can be adapted to the names used in the PBIX file.

## Total Transactions

```DAX
Total Transactions = COUNTROWS(All_Transactions)
```

## Total Transaction Value

```DAX
Total Transaction Value = SUM(All_Transactions[Amount])
```

## Unique Users

```DAX
Unique Users = DISTINCTCOUNT(All_Transactions[User_ID])
```

## Successful Transactions

```DAX
Successful Transactions =
CALCULATE(
    [Total Transactions],
    All_Transactions[Payment_Status] = "Successful"
)
```

## Successful Rate

```DAX
Successful Rate =
DIVIDE(
    [Successful Transactions],
    [Total Transactions],
    0
)
```

Format the Successful Rate measure as a percentage in Power BI.

## Service Transaction Value

```DAX
Service Transaction Value =
SUM(All_Transactions[Amount])
```

Use `Service` on the visual axis to compare services.

## Top Users

Use `User_ID` on the axis and `[Total Transaction Value]` as the value, then apply a Top N filter in Power BI.
