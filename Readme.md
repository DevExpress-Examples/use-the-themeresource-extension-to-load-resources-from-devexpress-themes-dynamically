<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128642544/21.1.5%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T207471)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
# Use the ThemeResource Extension to Load Resources from DevExpress Themes Dynamically

The ThemeResource extension allows you to load a resource from a currently applied DevExpress theme without specifying the theme name in xaml and reload the resource if a theme is changed. You can reference the resource in xaml:


```xaml
<Border Background="{dxi:ThemeResource {dxt:FloatingContainerThemeKey ResourceKey=FloatingContainerBackground}}" />
```

<!-- default file list -->
## Files to Look At

* [MainWindow.xaml](./CS/T207471/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/T207471/MainWindow.xaml))
* [MainWindow.xaml.cs](./CS/T207471/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/T207471/MainWindow.xaml.vb))
<!-- default file list end -->

## Documentation 
* [Customize Themes](https://docs.devexpress.com/WPF/400710/common-concepts/themes/customize-themes)
* [Knowledge Base Article: How to implement the ThemeMananger theme support in custom controls](https://supportcenter.devexpress.com/ticket/details/k18542/how-to-implement-the-thememananger-theme-support-in-custom-controls)

## More Examples
* [How to use DevExpress themes in a WPF Application](https://github.com/DevExpress-Examples/wpf-use-devexpress-theme-in-applications)
