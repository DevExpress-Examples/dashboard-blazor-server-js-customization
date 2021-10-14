<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/357643861/21.2.2%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T989998)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->

# Dashboard for Blazor Server - JavaScript Customization

<!-- default file list -->
## Files to Look At

* [Dashboard.razor](./CS/BlazorDashboardApp/Pages/Dashboard.razor)
* [_Host.cshtml](./CS/BlazorDashboardApp/Pages/_Host.cshtml)
* [dashboard-events-scripts.js](./CS/BlazorDashboardApp/wwwroot/dashboard-events-scripts.js)
<!-- default file list end -->

This example shows how you can customize the `DxDashboard` component with JavaScript:

- The [DxJSCustomization](https://docs.devexpress.com/Dashboard/DevExpress.DashboardBlazor.DxJSCustomization?v=21.1) class provides access to the [DashboardControl](https://docs.devexpress.com/Dashboard/js-DevExpress.Dashboard.DashboardControl) event handlers.
- The [onBeforeRender](https://docs.devexpress.com/Dashboard/js-DevExpress.Dashboard.DashboardControlOptions#js_devexpress_dashboard_dashboardcontroloptions_onbeforerender) event handler registers the custom [Parameter](https://github.com/DevExpress/dashboard-extensions/blob/master/docs/parameter-item.md) extension and removes the "New..." item from the dashboard menu.
- The [onItemCaptionToolbarUpdated](https://docs.devexpress.com/Dashboard/js-DevExpress.Dashboard.ViewerApiExtensionOptions#js_devexpress_dashboard_viewerapiextensionoptions_onitemcaptiontoolbarupdated) event handler adds a custom toolbar item to the Grid's caption.

## Documentation

- [DxJSCustomization](https://docs.devexpress.com/Dashboard/DevExpress.DashboardBlazor.DxJSCustomization?v=21.1)
- [Create a Blazor Server Dashboard Application](https://docs.devexpress.com/Dashboard/403029?v=21.1)

## More Examples

- [Get Started - Dashboard Component in Blazor Server Application](https://github.com/DevExpress-Examples/dashboard-blazor-server-app)
- [Dashboard Blazor Server App - Configuration](https://github.com/DevExpress-Examples/dashboard-blazor-server-configuration)
- [Dashboard Blazor WebAssembly App - JavaScript Customization](https://github.com/DevExpress-Examples/dashboard-blazor-webassembly-js-customization)
