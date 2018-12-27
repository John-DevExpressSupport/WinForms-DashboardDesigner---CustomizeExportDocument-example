<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/DesignerSample/Form1.cs) (VB: [Form1.vb](./VB/DesignerSample/Form1.vb))
<!-- default file list end -->
# WinForms Dashboard - How to add custom information to the exported Excel document


The <a href="https://docs.devexpress.com/Dashboard/DevExpress.DashboardWin.DashboardDesigner.CustomizeExportDocument">DashboardDesigner.CustomizeExportDocument</a> event allows you to obtain the stream of the exported document using the <a href="https://docs.devexpress.com/Dashboard/DevExpress.DashboardCommon.CustomizeExportDocumentEventArgs.Stream">Stream</a> property and customize the document's layout according to your requirements. For instance, <a href="https://documentation.devexpress.com/#Dashboard/CustomDocument15181">Excel documents</a> may be loaded into the <a href="https://documentation.devexpress.com/#DocumentServer/clsDevExpressSpreadsheetWorkbooktopic">Workbook</a> component for further processing.<br>This example shows how to add a custom header to each sheet for the exported workbook.<br><br>

<br/>


