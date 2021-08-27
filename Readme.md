<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128652492/18.2.1%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E2628)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
# How to provide custom images for the CheckEdit control in the GridControl

<p><b>This example is obsolete. Starting with version 18.2, we introduced <a href="https://docs.devexpress.com/WPF/DevExpress.Xpf.Editors.ImageCheckEditStyleSettings">ImageCheckEditStyleSettings</a> for the CheckEdit. Please refer to <a href="https://supportcenter.devexpress.com/ticket/details/e2627/how-to-provide-custom-images-for-checked-unchecked-states-in-checkedit">How to provide custom images for checked/unchecked states in CheckEdit</a> to learn more.</b></p> 


This example illustrates how to provide custom images for the CheckEdit control in the GridControl. 

Implement a custom ControlTemplate with an Image and define a custom DataTrigger that will change the Image's ImageSource property when a cell value is True. Use this ControlTemplate in the CheckEdit's style. 

Then add the CheckEdit to GridColumn's <a href="https://docs.devexpress.com/WPF/DevExpress.Xpf.Grid.ColumnBase.CellTemplate?v=18.2">CellTemplate</a>.
