<!-- .slide: class="title" -->

## Extending the Capabilities and Offerings of your GIS: A guided tour of Esri’s Developer Resources
Mara Stoica, Justin Colville & Matt Bryant
<br><br><br>

Follow along at [http://esriurl.com/giscama2019](http://esriurl.com/giscama2019)

---

<!-- .slide: class="agenda" -->

## Agenda

- Introduction
- Configure
- Customize
- Break
- Develop
- Wrap-up
- Questions

---

<!-- .slide: class="section" -->

# Introduction

---

<!-- .slide: class="bg-7" -->

<div class="container">
    <div class="col" style="text-align:left">
        ![Esri](images/small-logo.png)<br>
        Mara Stoica<br>
        .NET Software Engineer<br>
        Esri<br>
        [mstoica@esri.com](mailto:mstoica@esri.com)
    </div>
    <div class="col" style="text-align:left">
        ![Esri](images/small-logo.png)<br>
        Justin Colville<br>
        Product Engineer<br>
        Esri<br>
        [jcolville@esri.com](mailto:jcolville@esri.com)
    </div>
    <div class="col" style="text-align:left">
        ![DEVNET](images/devnet-d-icon.png)<br>
        Matt Bryant<br>
        Chief Technology Officer<br>
        DEVNET<br>
        [bryant@devnetinc.com](mailto:bryant@devnetinc.com)
    </div>
</div>

---

<!-- .slide: class="bg-5" -->

## Apps and Builders and APIs, oh my?

 - There are a lot of options for extending the ArcGIS platform.
 - Consider your users and team needs.
 - Choose the right tools for the solution.

---

<!-- .slide: class="bg-5" -->

<div class="container">
    <div class="col" style="text-align:left">
        <h3>Configuration</h3>
        The process of setting up options using the administrative tools supplied within the application.
    </div>
    <div class="col" style="text-align:left">
        <h3>Customization</h3>
        Modification of the base product itself though code.
    </div>
    <div class="col" style="text-align:left">
        <h3>Development</h3>
        Creation of custom solutions that run independently of other systems.
    </div>
</div>

---

<!-- .slide: class="bg-5" -->

## Resources

[doc.arcgis.com](https://doc.arcgis.com/)<br>
[solutions.arcgis.com](https://solutions.arcgis.com/)<br>
[developers.arcgis.com](https://developers.arcgis.com/)

---

<!-- .slide: class="section" -->

# Configure

---

<!-- .slide: class="background" -->

## Apps for Everyone

 - Suites of purpose-built apps working together - [ArcGIS Apps](https://www.esri.com/en-us/arcgis/products/apps-for-everyone/overview)
 - [Apps for the Field](https://www.esri.com/en-us/arcgis/products/field-operations/overview)
  - Collector, Explorer, Workforce, Navigator, Tracker, Survey123
 - Apps for the Office
 - Apps for the Community
 - App Builders
  - Build Your Own Apps, No Coding Required

---

<!-- .slide: class="bg-5" -->

## Field Operations

 - Collector
  - Map centric data collection
  - Partner integration
    - Eos Positioning + LTI
    - Trimble - R1/R2/R102 integration
 - Survey123
  - Form based data collection
 - Explorer
  - Data viewing
  - [Severe Weather Web Map](arcgis-explorer://?itemID=d16d53126f1243a3a7a7f1d0dff39662)
 - URL Schema - [Explorer](https://github.com/Esri/explorer-integration), [Collector](https://github.com/Esri/collector-integration#documentation), [Survey123](https://doc.arcgis.com/en/survey123/reference/integratewithotherapps.htm)

---

<!-- .slide: class="bg-8" -->

| | Configure | Customize | Develop |
| --- | :-------: | :-------: | :-----: |
| Collector | ✔️ | ❌ | ❌ |
| Explorer | ✔️ | ❌ | ❌ |
| Survey123 | ✔️ | ❌ | ❌ |

---

<!-- .slide: class="bg-5" -->

## Arcade

 - Simple and portable expressions language<br>
 - [developers.arcgis.com/arcade](https://developers.arcgis.com/arcade/)<br>
 - [Toronto Neighborhoods Urban Trees](http://jsapi.maps.arcgis.com/home/item.html?id=2b998111603f4cd4bf135647b24b21b6)<br>
 - [What’s new with Arcade: Taking a stroll through FeatureSets](https://www.esri.com/arcgis-blog/products/mapping/mapping/whats-new-with-arcade-taking-a-stroll-through-featuresets-part-2/)

---

<!-- .slide: class="bg-8" -->

| | Configure | Customize | Develop |
| --- | :-------: | :-------: | :-----: |
| Collector | ✔️ | ❌ | ❌ |
| Explorer |  ✔️ | ❌ | ❌ |
| Survey123 |  ✔️ | ❌ | ❌ |
| Arcade |  ✔️ | ❌ | ❌ |

---

<!-- .slide: class="background" -->

## Operations Dashboard

- Real-time data visualization
- View activities and key performance indicators
- Use charts, gauges, maps, and other visual elements


[Dashboard](https://doc.arcgis.com/en/operations-dashboard/)

---

<!-- .slide: class="bg-8" -->

| | Configure | Customize | Develop |
| --- | :-------: | :-------: | :-----: |
| Collector | ✔️ | ❌ | ❌ |
| Explorer |  ✔️ | ❌ | ❌ |
| Survey123 |  ✔️ | ❌ | ❌ |
| Arcade |  ✔️ | ❌ | ❌ |
| Dashboard |  ✔️ | ❌ | ❌ |

---

<!-- .slide: class="background" -->

## Web AppBuilder<br><br>

- Configurable web mapping application
- Choose from several pre-made themes
- Add functionality with pre-built widgets


[https://doc.arcgis.com/en/web-appbuilder](https://doc.arcgis.com/en/web-appbuilder/)

---

<!-- .slide: class="background" -->

<div class="container">
    <div class="col">
        ![Floodplain Inquiry](http://solutions.arcgis.com/shared/img/FloodInquiryOverview.png)<br>
        [Floodplain Inquiry](https://www.arcgis.com/apps/webappviewer/index.html?id=c2b1439f82a14d2390a9197da6758d83)
    </div>
    <div class="col">
         ![Residential Comp Finder](http://solutions.arcgis.com/local-government/help/residential-comp-finders/img/overview.png)<br>
         [Residential Comp Finder](http://statelocaltryit.maps.arcgis.com/apps/webappviewer/index.html?id=2e5abc40d59745f486eb41f05e46d38d)
    </div>
</div>

---

<!-- .slide: class="bg-8" -->

| | Configure | Customize | Develop |
| --- | :-------: | :-------: | :-----: |
| Collector | ✔️ | ❌ | ❌ |
| Explorer |  ✔️ | ❌ | ❌ |
| Survey123 |  ✔️ | ❌ | ❌ |
| Arcade |  ✔️ | ❌ | ❌ |
| Dashboard |  ✔️ | ❌ | ❌ |
| Web AppBuilder |  ✔️ |   |  |

---

<!-- .slide: class="section" -->

# Customize

---

<!-- .slide: class="background" -->

## Web AppBuilde (developer edition)<br><br>

- Create custom widgets
- Create custom themes


[https://developers.arcgis.com/web-appbuilder/](https://developers.arcgis.com/web-appbuilder/)

---

<!-- .slide: class="bg-8" -->

| | Configure | Customize | Develop |
| --- | :-------: | :-------: | :-----: |
| Collector | ✔️ | ❌ | ❌ |
| Explorer |  ✔️ | ❌ | ❌ |
| Survey123 |  ✔️ | ❌ | ❌ |
| Arcade |  ✔️ | ❌ | ❌ |
| Dashboard |  ✔️ | ❌ | ❌ |
| Web AppBuilder |  ✔️ | ✔️  | ❌ |

---

<!-- .slide: class="background" -->

## AppStudio

[AppStudio](https://appstudio.arcgis.com/) helps convert your maps into beautiful mobile apps for Mac,<br>iOS, Android, Windows, and Linux

---

<!-- .slide: class="bg-8" -->

| | Configure | Customize | Develop |
| --- | :-------: | :-------: | :-----: |
| Collector | ✔️ | ❌ | ❌ |
| Explorer |  ✔️ | ❌ | ❌ |
| Survey123 |  ✔️ | ❌ | ❌ |
| Arcade |  ✔️ | ❌ | ❌ |
| Dashboard |  ✔️ | ❌ | ❌ |
| Web AppBuilder |  ✔️ | ✔️  | ❌ |
| AppStudio |  ✔️ | ✔️  |  |

---

<!-- .slide: class="background" -->

## ArcGIS Pro SDK

- Create Pro add-ins and solution configurations using C# or Visual Basic
- [ArcGIS Pro SDK](https://pro.arcgis.com/en/pro-app/sdk/)
- [ArcGIS Solutions Deployment Tool](https://solutions.arcgis.com/shared/help/deployment-tool/)<br><br>


### [Tutorials](https://developers.arcgis.com/labs/?product=Pro-SDK&topic=any)

- [Create an add-in with a button](https://developers.arcgis.com/labs/pro/build-your-first-add-in/)
- [Create an add-in with an identify tool](https://developers.arcgis.com/labs/pro/build-a-map-identification-tool/)

---

<!-- .slide: class="bg-8" -->

| | Configure | Customize | Develop |
| --- | :-------: | :-------: | :-----: |
| Collector | ✔️ | ❌ | ❌ |
| Explorer |  ✔️ | ❌ | ❌ |
| Survey123 |  ✔️ | ❌ | ❌ |
| Arcade |  ✔️ | ❌ | ❌ |
| Dashboard |  ✔️ | ❌ | ❌ |
| Web AppBuilder |  ✔️ | ✔️  | ❌ |
| AppStudio |  ✔️ | ✔️  |  |
| ArcGIS Pro SDK |  ❌ | ✔️ | ❌ |

---

<!-- .slide: class="background" -->

## Arcpy

- Data analysis
- Data conversion
- Data management
- Map automation <br><br><br>
- [Arcpy for ArcGIS Desktop](http://desktop.arcgis.com/en/arcmap/latest/analyze/arcpy/what-is-arcpy-.htm)
- [Arcpy for ArcGIS Pro](https://pro.arcgis.com/en/pro-app/arcpy/main/arcgis-pro-arcpy-reference.htm)

---

<!-- .slide: class="bg-8" -->

| | Configure | Customize | Develop |
| --- | :-------: | :-------: | :-----: |
| Collector | ✔️ | ❌ | ❌ |
| Explorer |  ✔️ | ❌ | ❌ |
| Survey123 |  ✔️ | ❌ | ❌ |
| Arcade |  ✔️ | ❌ | ❌ |
| Dashboard |  ✔️ | ❌ | ❌ |
| Web AppBuilder |  ✔️ | ✔️  | ❌ |
| AppStudio |  ✔️ | ✔️  |  |
| ArcGIS Pro SDK |  ❌ | ✔️ | ❌ |
| Arcpy |  ❌ | ✔️ | ❌ |

---

<!-- .slide: class="section" -->

# Develop

---

<!-- .slide: class="background" -->

## ArcGIS API for Python

[ArcGIS API for Python](https://developers.arcgis.com/python/)

---

<!-- .slide: class="bg-8" -->

| | Configure | Customize | Develop |
| --- | :-------: | :-------: | :-----: |
| Collector | ✔️ | ❌ | ❌ |
| Explorer |  ✔️ | ❌ | ❌ |
| Survey123 |  ✔️ | ❌ | ❌ |
| Arcade |  ✔️ | ❌ | ❌ |
| Dashboard |  ✔️ | ❌ | ❌ |
| Web AppBuilder |  ✔️ | ✔️  | ❌ |
| AppStudio |  ✔️ | ✔️  |  |
| ArcGIS Pro SDK |  ❌ | ✔️ | ❌ |
| Arcpy |  ❌ | ✔️ | ❌ |
| ArcGIS API for Python |  ❌ | ❌ | ✔️ |

---

<!-- .slide: class="background" -->

## JavaScript API<br><br>

- Build custom web applications


[https://developers.arcgis.com/javascript/](https://developers.arcgis.com/javascript/)

### [Tutorials](https://developers.arcgis.com/labs/)

- [Create map app](https://developers.arcgis.com/labs/javascript/create-a-starter-app/)
- [Create webmap app](https://developers.arcgis.com/labs/javascript/display-a-web-map/)
- [Add map coordinates widget](https://developers.arcgis.com/labs/javascript/get-map-coordinates/)

---

<!-- .slide: class="bg-8" -->

| | Configure | Customize | Develop |
| --- | :-------: | :-------: | :-----: |
| Collector | ✔️ | ❌ | ❌ |
| Explorer |  ✔️ | ❌ | ❌ |
| Survey123 |  ✔️ | ❌ | ❌ |
| Arcade |  ✔️ | ❌ | ❌ |
| Dashboard |  ✔️ | ❌ | ❌ |
| Web AppBuilder |  ✔️ | ✔️  | ❌ |
| AppStudio |  ✔️ | ✔️  |  |
| ArcGIS Pro SDK |  ❌ | ✔️ | ❌ |
| Arcpy |  ❌ | ✔️ | ❌ |
| ArcGIS API for Python |  ❌ | ❌ | ✔️ |
| Javascript API |  ❌ | ❌ | ✔️ |

---

<!-- .slide: class="background" -->

## Runtime APIs<br><br>

- Develop iPhone and iPad applications with the [ArcGIS Runtime SDK for iOS](https://developers.arcgis.com/ios/latest/)
- Develop apps for Android phones and tablets with the [ArcGIS Runtime SDK for Android](https://developers.arcgis.com/android/latest/)
- Develop apps for Windows, iOS, and Android with the [ArcGIS Runtime SDK for .NET](https://developers.arcgis.com/net/latest/)
- Develop apps for Windows, Linux and macOS with the [ArcGIS Runtime SDK for Java](https://developers.arcgis.com/java/latest/)
- Develop apps for Windows, macOS, Linux, Android, and iOS with the [ArcGIS Runtime SDK for QT](https://developers.arcgis.com/qt/latest/)

---

<!-- .slide: class="background" -->

## Developer Resources<br><br>

- [DevLabs (aka Tutorials)](https://developers.arcgis.com/labs/)
- [Open Source Apps](https://developers.arcgis.com/example-apps/)

---

<!-- .slide: class="bg-8" -->

| | Configure | Customize | Develop |
| --- | :-------: | :-------: | :-----: |
| Collector | ✔️ | ❌ | ❌ |
| Explorer |  ✔️ | ❌ | ❌ |
| Survey123 |  ✔️ | ❌ | ❌ |
| Arcade |  ✔️ | ❌ | ❌ |
| Dashboard |  ✔️ | ❌ | ❌ |
| Web AppBuilder |  ✔️ | ✔️  | ❌ |
| AppStudio |  ✔️ | ✔️  | ✔️ |
| ArcGIS Pro SDK |  ❌ | ✔️ | ❌ |
| Arcpy |  ❌ | ✔️ | ❌ |
| ArcGIS API for Python |  ❌ | ❌ | ✔️ |
| Javascript API |  ❌ | ❌ | ✔️ |
| Runtime APIs |  ❌ | ❌ | ✔️ |

---

<!-- .slide: class="questions" -->

## Questions

---

<!-- .slide: class="end" -->

![Esri](images/logo.png)
