# WPFModernScrollbarStyle
A modern scrollbar style for WPF XAML

## Usage

1. Add `Scrollbar.xaml` to your project.
2. Add `<ResourceDictionary Source="Scrollbar.xaml"/>` to your merged dictionaries int `App.xaml`.

```xaml
<Application ...namespaces... >
    <Application.Resources>
        <ResourceDictionary>
            <ResourceDictionary.MergedDictionaries>
                ...other resource dictionaries...
                
                <ResourceDictionary Source="Scrollbar.xaml"/>
                
            </ResourceDictionary.MergedDictionaries>
        </ResourceDictionary>
    </Application.Resources>
    
    ...

</Application>
```
