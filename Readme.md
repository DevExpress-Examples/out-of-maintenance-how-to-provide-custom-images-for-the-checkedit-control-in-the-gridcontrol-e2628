# How to provide custom images for the CheckEdit control in the GridControl

<p><b>This example is obsolete. Starting with version 18.2, we introduced <a href="https://docs.devexpress.com/WPF/DevExpress.Xpf.Editors.ImageCheckEditStyleSettings">ImageCheckEditStyleSettings</a> for the CheckEdit. Please refer to <a href="https://supportcenter.devexpress.com/ticket/details/e2627/how-to-provide-custom-images-for-checked-unchecked-states-in-checkedit">How to provide custom images for checked/unchecked states in CheckEdit</a> to learn more.</b></p> 


This example illustrates how to provide custom images for the CheckEdit control in the GridControl. 

Implement a custom ControlTemplate with an Image and define a custom DataTrigger that will change the Image's ImageSource property when a cell value is True. Use this ControlTemplate in the CheckEdit's style. 

Then add the CheckEdit to GridColumn's <a href="https://docs.devexpress.com/WPF/DevExpress.Xpf.Grid.ColumnBase.CellTemplate?v=18.2">CellTemplate</a>.
