<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/Dashboard_AggrCustomerOrderCount/Form1.cs) (VB: [Form1.vb](./VB/Dashboard_AggrCustomerOrderCount/Form1.vb))
<!-- default file list end -->
# Dashboard for WinForms - How to divide customers' count by the number of orders they made


This example shows how to divide customers' count by the number of orders they made.

## Example Structure

The following [Chart](https://docs.devexpress.com/Dashboard/14719/winforms-dashboard/winforms-designer/create-dashboards-in-the-winforms-designer/dashboard-item-settings/chart) shows the number of orders placed by each customer:

![screenshot](/images/aggr_example4_customerordercount122830.png)

The calculated field evaluates the number of unique orders placed by each customer:

```
aggr(CountDistinct([OrderID]), [CustomerID])
```

The following screenshot shows the final result after placing the calculated Customer Order Count field to Arguments and dropping the CustomerID field to Values:

![screenshot](/images/aggr_example4_customerordercount_result122829.png)

## Documentation

- [Intermediate Level Aggregations](https://docs.devexpress.com/Dashboard/115870/)
- [Aggregations](https://docs.devexpress.com/Dashboard/115894/)
- [Expression Constants, Operators, and Functions](https://docs.devexpress.com/Dashboard/400122/)

## More Examples

- [Dashboard for WinForms - How to display best and worst monthly sales for each year](https://github.com/DevExpress-Examples/how-to-display-best-and-worst-monthly-sales-for-each-year-t369371)
- [Dashboard for WinForms - How to Calculate the Contribution of Quarterly Sales to Total Yearly Sales](https://github.com/DevExpress-Examples/how-to-calculate-the-contribution-of-quarterly-sales-to-total-yearly-sales)
- [Dashboard for WinForms - How to evaluate a customer acquisition using the quarter/year of their first purchase](https://github.com/DevExpress-Examples/how-to-divide-customers-count-by-the-number-of-orders-they-made-t372356)
- [Dashboard for WinForms - How to calculate Highest Product Sales by Year](https://github.com/DevExpress-Examples/how-to-show-products-with-the-best-sales-in-a-year-along-with-sales-values-t372408)
- [Dashboard for WinForms - How to display sales by years in comparison with the previous year's sales](https://github.com/DevExpress-Examples/win-dashboard-display-previous-year-sales)
- [Dashboard for WinForms - How to Display Product Sales that are Greater than $20k](https://github.com/DevExpress-Examples/How-to-Display-Product-Sales-that-are-Greater-than-20k)
- [Dashboard for WinForms - How to Display Products with Sales Greater than Average Sales per Category](https://github.com/DevExpress-Examples/How-to-Display-Product-with-Sales-Greater-than-Average-Sales-per-Category)
