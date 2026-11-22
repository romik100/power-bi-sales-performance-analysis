
1.All_Measures

Gross_Margin = DIVIDE([Total_Gross_profit],[Total_Revenue])     Measures profitability percentage

Total_Gross_profit = SUM(Sales_Data[Gross Profit])              Measures gross profit

Total_orders = DISTINCTCOUNT(Sales_Data[ID])                    Measures order volume

Total_Quantity = SUM(Sales_Data[Units Sold])                    Measures units sold

Total_Revenue = SUM(Sales_Data[Revenue])                      Measures overall revenue      