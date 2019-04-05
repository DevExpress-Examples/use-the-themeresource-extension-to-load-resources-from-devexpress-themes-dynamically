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


