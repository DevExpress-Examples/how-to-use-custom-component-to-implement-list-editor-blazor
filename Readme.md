<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/388044123/22.2.4%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T1015880)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
# XAF Blazor - Use a Custom Component to Implement List Editor

This example demonstrates how to implement a custom List Editor that shows images in an ASP.NET Core Blazor application. 
The List Editor displays a Razor component with custom objects. These objects implement a custom [IPictureItem](./CS/MySolution.Module/BusinessObjects/IPictureItem.cs) interface to store images and their captions.

See the following help topic for more information: [How to: Use a Custom Component to Implement List Editor (Blazor)](https://docs.devexpress.com/eXpressAppFramework/403258/ui-construction/list-editors/how-to-use-a-custom-component-to-implement-list-editor-blazor).

![](custom-list-editor.png)

<!-- default file list -->
## Files to Review

* [PictureItemListView.razor](./CS/EF/CustomEditorEF/CustomEditorEF.Blazor.Server/Editors/CustomList/PictureItemListView.razor)
* [PictureItemListViewModel.cs](./CS/EF/CustomEditorEF/CustomEditorEF.Blazor.Server/Editors/CustomList/PictureItemListViewModel.cs)
* [PictureItemListViewRenderer.razor](./CS/EF/CustomEditorEF/CustomEditorEF.Blazor.Server/Editors/CustomList/PictureItemListViewRenderer.razor)
* [BlazorCustomListEditor.cs](./CS/EF/CustomEditorEF/CustomEditorEF.Blazor.Server/Editors/CustomList/BlazorCustomListEditor.cs)
<!-- default file list end -->

## Documentation
* [List Editors](https://docs.devexpress.com/eXpressAppFramework/113189/ui-construction/list-editors?p=netframework)
* [Using a Custom Control that is not Integrated by Default](https://docs.devexpress.com/eXpressAppFramework/113610/ui-construction/using-a-custom-control-that-is-not-integrated-by-default/using-a-custom-control-that-is-not-integrated-by-default)

## More GitHub Examples
[XAF Blazor - Use a Custom View Item to Add a Button to a Detail View](https://github.com/DevExpress-Examples/xaf-custom-view-item-blazor)
