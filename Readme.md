# How to provide custom images for the CheckEdit control in the GridControl


<p>This example illustrates how to support the functionality of the PictureChecked and PictureUnchecked properties from WinForms controls in the WPF CheckEdit used in a GridControl. For this, implement a custom ControlTemplate with an Image and define a custom DataTrigger that will change the Image's ImageSource property when a cell value is True. Use this ControlTemplate in GridColumn's <a href="https://documentation.devexpress.com/WPF/DevExpress.Xpf.Grid.ColumnBase.EditTemplate.property">EditTemplate</a> and <a href="https://documentation.devexpress.com/WPF/DevExpress.Xpf.Grid.ColumnBase.DisplayTemplate.property">DisplayTemplate</a> properties.</p>

<br/>


