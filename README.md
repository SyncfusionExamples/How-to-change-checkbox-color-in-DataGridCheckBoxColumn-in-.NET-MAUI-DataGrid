# How to change checkbox color in DataGridCheckBoxColumn in .NET MAUI DataGrid?

This article demonstrates how to change checkbox color in DataGridCheckBoxColumn in [.NET MAUI DataGrid](https://www.syncfusion.com/maui-controls/maui-datagrid).

To change the checkbox color in a DataGridCheckBoxColumn, you can define a custom color using the SfDataGridCheckBoxColor theme key in your application's resource dictionary. This ensures consistent styling across your application. This customization applies globally to all checkboxes in the DataGridCheckBoxColumn. Additionally, ensure that the SfDataGridTheme is set to CommonTheme to enable custom styling for DataGrid.

```xml
<Application.Resources>
    <ResourceDictionary>
        <ResourceDictionary.MergedDictionaries>
            <syncTheme:SyncfusionThemeResourceDictionary />
            <ResourceDictionary>
                <x:String x:Key="SfDataGridTheme">CommonTheme</x:String>
                <Color x:Key="SfDataGridCheckBoxColor">Red</Color>
            </ResourceDictionary>
            <ResourceDictionary Source="Resources/Styles/Colors.xaml" />
            <ResourceDictionary Source="Resources/Styles/Styles.xaml" />
        </ResourceDictionary.MergedDictionaries>
    </ResourceDictionary>
</Application.Resources>
```

You can download this example on [GitHub](https://github.com/SyncfusionExamples/How-to-change-checkbox-color-in-DataGridCheckBoxColumn-in-.NET-MAUI-DataGrid).