<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/Dashboard_UnderlyingDataWin/Form1.cs) (VB: [Form1.vb](./VB/Dashboard_UnderlyingDataWin/Form1.vb))
<!-- default file list end -->
# Dashboard for WinForms - How to Display the Underlying Data for a Dashboard Item


This example demonstrates how to display the underlying data when an end-user double-clicks a dashboard item.

![screenshot](/images/screenshot.png)

The example handles the [DashboardItem.DoubleClick](https://docs.devexpress.com/Dashboard/DevExpress.DashboardWin.DashboardViewer.DashboardItemDoubleClick) event, calls the [e.GetUnderlyingData](https://docs.devexpress.com/Dashboard/DevExpress.DashboardWin.DashboardItemMouseHitTestEventArgs.GetUnderlyingData) method to retrieve records from the dashboard item's data source and invokes a form with the Grid control that displays the data.

> Starting with v19.2 you can use the built-in [Data Inspector](https://docs.devexpress.com/Dashboard/401194/common-features/underlying-and-displayed-data/data-inspector) to display the underlying data.

## Documentation

- [Obtain Underlying and Displayed Data](https://docs.devexpress.com/Dashboard/17269/winforms-dashboard/winforms-viewer/obtaining-underlying-and-displayed-data)
- [Data Inspector](https://docs.devexpress.com/Dashboard/401194/common-features/underlying-and-displayed-data/data-inspector)

## More Examples

- [Dashboard for WinForms - How to Get and Process the Dashboard Item's Underlying Data](https://github.com/DevExpress-Examples/how-to-obtain-a-dashboard-items-client-data-in-the-winforms-viewer-t140553)
