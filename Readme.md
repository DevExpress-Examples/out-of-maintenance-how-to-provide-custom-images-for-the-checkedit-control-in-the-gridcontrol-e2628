<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128652492/11.1.4%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E2628)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/WpfApplication28/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/WpfApplication28/MainWindow.xaml))
* [MainWindow.xaml.cs](./CS/WpfApplication28/MainWindow.xaml.cs)
<!-- default file list end -->
# How to provide custom images for the CheckEdit control in the GridControl


<p>This example illustrates how to support the functionality of the PictureChecked and PictureUnchecked properties from WinForms controls in the WPF CheckEdit used in a GridControl. For this, implement a custom ControlTemplate with an Image and define a custom DataTrigger that will change the Image's ImageSource property when a cell value is True. Use this ControlTemplate in GridColumn's <a href="https://documentation.devexpress.com/WPF/DevExpress.Xpf.Grid.ColumnBase.EditTemplate.property">EditTemplate</a> and <a href="https://documentation.devexpress.com/WPF/DevExpress.Xpf.Grid.ColumnBase.DisplayTemplate.property">DisplayTemplate</a> properties.</p>

<br/>


