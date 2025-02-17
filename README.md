<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/724474966/23.1.3%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T1203119)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
[![](https://img.shields.io/badge/💬_Leave_Feedback-feecdd?style=flat-square)](#does-this-example-address-your-development-requirementsobjectives)
<!-- default badges end -->
# DataGrid for DevExtreme - How to implement sticky headers

This example demonstrates how to implement sticky headers for a DataGrid component.

![Screenshot 2023-11-28 174740](https://github.com/DevExpress-Examples/DevExtreme-DataGrid-How-to-implement-sticky-headers/assets/14982461/4c9ae36d-a312-43e1-ab69-9e86bc41ec41)

To implement sticky headers, you need to modify the DataGrid's stylesheet. Apply the following attributes to the CSS class `.dx-datagrid-headers`:

- `position: sticky`
- `z-index: 1000`

```css
  .dx-datagrid .dx-datagrid-headers{
    background-color: #fff;
    position: sticky;
    top: 0;
    z-index: 1000;
  }
```

## Files to Review

- **jQuery**
    - [index.js](jQuery/src/index.js)
    - [index.css](jQuery/src/index.css)
- **Angular**
    - [app.component.html](Angular/src/app/app.component.html)
    - [app.component.ts](Angular/src/app/app.component.ts)
    - [app.component.scss](Angular/src/app/app.component.scss)
- **Vue**
    - [Home.vue](Vue/src/components/HomeContent.vue)
    - [main.css](Vue/src/assets/main.css)
- **React**
    - [App.tsx](React/src/App.tsx)
    - [App.css](React/src/App.css)
- **NetCore**    
    - [Index.cshtml](ASP.NET%20Core/Views/Home/Index.cshtml)
    - [Site.css](ASP.NET%20Core/wwwroot/css/Site.css)

## Documentation

- [Getting Started with DataGrid](https://js.devexpress.com/Documentation/Guide/UI_Components/DataGrid/Getting_Started_with_DataGrid/)
- [HTML-Based Components Customization](https://js.devexpress.com/Documentation/Guide/Themes_and_Styles/HTML-Based_Components_Customization/)
<!-- feedback -->
## Does this example address your development requirements/objectives?

[<img src="https://www.devexpress.com/support/examples/i/yes-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=devextreme-datagrid-sticky-headers&~~~was_helpful=yes) [<img src="https://www.devexpress.com/support/examples/i/no-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=devextreme-datagrid-sticky-headers&~~~was_helpful=no)

(you will be redirected to DevExpress.com to submit your response)
<!-- feedback end -->
