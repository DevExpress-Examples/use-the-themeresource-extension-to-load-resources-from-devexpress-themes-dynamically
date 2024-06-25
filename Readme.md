<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128642544/14.1.8%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T207471)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
[![](https://img.shields.io/badge/💬_Leave_Feedback-feecdd?style=flat-square)](#does-this-example-address-your-development-requirementsobjectives)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/T207471/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/T207471/MainWindow.xaml))
* [MainWindow.xaml.cs](./CS/T207471/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/T207471/MainWindow.xaml.vb))
<!-- default file list end -->
# How to use the ThemeResource extension to load resources from DevExpress themes dynamically


The ThemeResource extension allows you to load a resource from a currently applied DevExpress theme without specifying the theme name in xaml and reload the resource if a theme is changed. You can reference the resource in xaml as follows:<br>


```xaml
<Border Background="{dxi:ThemeResource {dxt:FloatingContainerThemeKey ResourceKey=FloatingContainerBackground}}" />
```


<p> </p>
<p><strong>See Also:</strong><br><a href="https://www.devexpress.com/Support/Center/p/KA18580">KA18580 - How to modify DX themes in WPF</a><br><a href="https://www.devexpress.com/Support/Center/p/K18542">K18542 - How to implement the ThemeMananger theme support in custom controls</a><br><a href="https://www.devexpress.com/Support/Center/p/T128436">T128436 - How to use DevExpress themes in a WPF Application</a></p>

<br/>


<!-- feedback -->
## Does this example address your development requirements/objectives?

[<img src="https://www.devexpress.com/support/examples/i/yes-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=use-the-themeresource-extension-to-load-resources-from-devexpress-themes-dynamically&~~~was_helpful=yes) [<img src="https://www.devexpress.com/support/examples/i/no-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=use-the-themeresource-extension-to-load-resources-from-devexpress-themes-dynamically&~~~was_helpful=no)

(you will be redirected to DevExpress.com to submit your response)
<!-- feedback end -->
