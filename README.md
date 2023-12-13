<!-- default badges list -->
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T1203119)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
# DataGrid for DevExtreme - How to implement sticky headers

This example demonstrates how to implement sticky headers for DataGrid. 

![Screenshot 2023-11-28 174740](https://github.com/DevExpress-Examples/DevExtreme-DataGrid-How-to-implement-sticky-headers/assets/14982461/4c9ae36d-a312-43e1-ab69-9e86bc41ec41)

The idea is to define header position as `sticky` and apply the following CSS rules to them:
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
- **Angular**
    - [app.component.html](Angular/src/app/app.component.html)
    - [app.component.ts](Angular/src/app/app.component.ts)
- **Vue**
    - [Home.vue](Vue/src/components/HomeContent.vue)
- **React**
    - [App.tsx](React/src/App.tsx)
- **NetCore**    
    - [Index.cshtml](ASP.NET%20Core/Views/Home/Index.cshtml)

## Documentation

- link
- link
- ...

## More Examples

- link
- link
- ...
