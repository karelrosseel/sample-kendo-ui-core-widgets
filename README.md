Kendo UI Core Widgets
====================
<a href="https://platform.telerik.com/#appbuilder/clone/https%3A%2F%2Fgithub.com%2FIcenium%2Fsample-kendo-ui-core-widgets" target="_blank"><img src="http://docs.telerik.com/platform/samples/images/try-in-appbuilder.png" alt="Try in AppBuilder" title="Try in AppBuilder" /></a>  <a href="https://github.com/Icenium/sample-kendo-ui-core-widgets" target="_blank"><img style="padding-left:20px" src="http://docs.telerik.com/platform/samples/images/get-github.png" alt="Get from GitHub" title="Get from GitHub"></a>

<a id="top"></a>
* [Overview](#overview)
* [Showcased APIs](#showcased-apis)
* [Important Directories and Files](#important-directories-and-files)
* [Screenshots](#screenshots)
* [Test the Sample](#test-the-sample)

# Overview

This sample shows you how to implement a native-looking user interface along with the unique Flat UI. The app provides a welcome screen, a dummy login form, geolocation implementation and data binding.

> *Supported mobile platforms:* iOS, Android, Windows Phone
>
> *Developed with:* Apache Cordova 3.7.0, Kendo UI Core v2014.1.624

[Back to Top](#top)

# Showcased APIs

This sample shows how to use the following widgets and features of Kendo UI Core.

* **[Kendo MVVM][Kendo MVVM]:** Model View ViewModel (MVVM) is a design pattern which helps developers separate the Model (the data) from the View (the UI). The View-Model part of MVVM is responsible for exposing the data objects from the Model in such a way that those objects are easily consumed in the View.
* **[Application][Application]:** The widget provides the necessary tools for building native-looking web based mobile applications.
* **[View][View]:** The widget represents a screen in the Kendo mobile Application.
* **[Tabstrip][Tabstrip]:** The widget displays an application-wide group of navigation buttons. The look of the mobile TabStrip changes depending on the user mobile device and operating system.
* **[NavBar][NavBar]:** The widget displays an application navigation bar. The mobile NavBar may display the current view title in the center, and optionally some additional left and right aligned widgets (a back button, settings button, etc.).
* **[Button][Button]:** The widget navigates to a mobile View or executes a custom callback when tapped.
* **[ListView][ListView]:** The widget displays flat or grouped list of items.
* **[ObservableObject][ObservableObject]:** The kendo.data.ObservableObject is the building block of Kendo MVVM.
* **[DataSource][DataSource]:** The DataSource component is an abstraction for using local data (array of JavaScript objects) or remote data (web service returning JSON, JSONP, OData or XML). 

For more information about the Kendo UI widget APIs, see the [Kendo UI API Reference][Kendo UI API Reference].

This sample shows how to use the following Apache Cordova core plugins.

* **[Geolocation][Geolocation]:** The plugin provides information about the location of the device.
* **[Dialogs (Notification)][Dialogs (Notification)]:** The plugin provides access to the native prompt, alert and confirmation dialogs, and to the beep alerts.

[Back to Top](#top)

# Important Directories and Files

* `data\weather.json`: Contains dummy data for the weather view model.
* `scripts\app.js`: Contains the application initialization and the implementation of switching between the native and the flat UI skins.
* `scripts\location.js`: Contains the implementation of the geolocation view model.
* `scripts\login.js`: Contains the implementation of the login view model.
* `scripts\qr-code.js`: Contains the implementation of the weather view model.

[Back to Top](#top)

# Screenshots

### iOS

Skin | Home | Login | Location | Weather
--- | --- | --- | --- | ---
Native | ![](https://raw.githubusercontent.com/Icenium/sample-kendo-ui-core-widgets/master/screenshots/ios/native-home.png) | ![](https://raw.githubusercontent.com/Icenium/sample-kendo-ui-core-widgets/master/screenshots/ios/native-login.png) | ![](https://raw.githubusercontent.com/Icenium/sample-kendo-ui-core-widgets/master/screenshots/ios/native-location.png) | ![](https://raw.githubusercontent.com/Icenium/sample-kendo-ui-core-widgets/master/screenshots/ios/native-weather.png)
Flat | ![](https://raw.githubusercontent.com/Icenium/sample-kendo-ui-core-widgets/master/screenshots/ios/flat-home.png) | ![](https://raw.githubusercontent.com/Icenium/sample-kendo-ui-core-widgets/master/screenshots/ios/flat-login.png) | ![](https://raw.githubusercontent.com/Icenium/sample-kendo-ui-core-widgets/master/screenshots/ios/flat-location.png) | ![](https://raw.githubusercontent.com/Icenium/sample-kendo-ui-core-widgets/master/screenshots/ios/flat-weather.png)

### Android

Skin | Home | Login | Location | Weather
--- | --- | --- | --- | ---
Native | ![](https://raw.githubusercontent.com/Icenium/sample-kendo-ui-core-widgets/master/screenshots/android/native-home.png) | ![](https://raw.githubusercontent.com/Icenium/sample-kendo-ui-core-widgets/master/screenshots/android/native-login.png) | ![](https://raw.githubusercontent.com/Icenium/sample-kendo-ui-core-widgets/master/screenshots/android/native-location.png) | ![](https://raw.githubusercontent.com/Icenium/sample-kendo-ui-core-widgets/master/screenshots/android/native-weather.png)
Flat | ![](https://raw.githubusercontent.com/Icenium/sample-kendo-ui-core-widgets/master/screenshots/android/flat-home.png) | ![](https://raw.githubusercontent.com/Icenium/sample-kendo-ui-core-widgets/master/screenshots/android/flat-login.png) | ![](https://raw.githubusercontent.com/Icenium/sample-kendo-ui-core-widgets/master/screenshots/android/flat-location.png) | ![](https://raw.githubusercontent.com/Icenium/sample-kendo-ui-core-widgets/master/screenshots/android/flat-weather.png)

### Windows Phone

Skin | Home | Login | Location | Weather
--- | --- | --- | --- | ---
Native | ![](https://raw.githubusercontent.com/Icenium/sample-kendo-ui-core-widgets/master/screenshots/wp/native-home.png) | ![](https://raw.githubusercontent.com/Icenium/sample-kendo-ui-core-widgets/master/screenshots/wp/native-login.png) | ![](https://raw.githubusercontent.com/Icenium/sample-kendo-ui-core-widgets/master/screenshots/wp/native-location.png) | ![](https://raw.githubusercontent.com/Icenium/sample-kendo-ui-core-widgets/master/screenshots/wp/native-weather.png)
Flat | ![](https://raw.githubusercontent.com/Icenium/sample-kendo-ui-core-widgets/master/screenshots/wp/flat-home.png) | ![](https://raw.githubusercontent.com/Icenium/sample-kendo-ui-core-widgets/master/screenshots/wp/flat-login.png) | ![](https://raw.githubusercontent.com/Icenium/sample-kendo-ui-core-widgets/master/screenshots/wp/flat-location.png) | ![](https://raw.githubusercontent.com/Icenium/sample-kendo-ui-core-widgets/master/screenshots/wp/flat-weather.png)

[Back to Top](#top)

# Test the Sample

Apart from exploring the sample code base in GitHub, you can also clone and run the sample in your preferred AppBuilder client.

## In-Browser

With the AppBuilder in-browser client, you can develop hybrid and NativeScript cross-platform mobile apps from your browser. You can use the in-browser client at [https://platform.telerik.com](https://platform.telerik.com).

### Clone the sample

1. Click **Try in AppBuilder** above.
1. Provide your login credentials, if prompted.

### Run the sample

1. [Run in the device simulator.][device simulator]
1. [Run in the companion app.][companion]
1. [Deploy on device via QR code.][QR code]

[Back to Top](#top)

## Windows

With the AppBuilder Windows client, you can develop hybrid and NativeScript cross-platform mobile apps from your Windows desktop. You can download and install the Windows client from [http://www.telerik.com/appbuilder/windows-client](http://www.telerik.com/appbuilder/windows-client).

### Clone the sample

1. Verify that the AppBuilder Windows client is running and you are logged in the Telerik Platform in the account in which you want to develop your application.
1. In the dashboard, click **Samples** and select **Hybrid**.
1. From the **Workspace** drop-down menu, select the workspace in which you want to develop your application.
1. Select **Demos**.
1. Select **Kendo Ui Core Widgets**.
1. (Optional) Rename the project.
1. Click **Clone**.

### Run the sample

With the AppBuilder Windows client, you can quickly test your apps on device, in the simulator or in the native emulators.

1. [Run in the device simulator.][device simulator]
1. [Run in the companion app.][companion]
1. [Run in the native emulators.][emulators]
1. [Deploy on device via QR code.][QR code]
1. [Deploy via cable connection.][USB deploy]

[Back to Top](#top)

## Visual Studio

With the AppBuilder extension for Visual Studio, you can develop hybrid and NativeScript cross-platform mobile apps from Microsoft Visual Studio. You can download and install the extension from [http://www.telerik.com/appbuilder/visual-studio-extension](http://www.telerik.com/appbuilder/visual-studio-extension).

### Clone the sample

1. Verify that the AppBuilder extension for Visual Studio is running and you are logged in the Telerik Platform in the account in which you want to develop your application.
1. Select **AppBuilder** &#8594; **Get Sample**.
1. Select **Hybrid**.
1. Select **Demos**.
1. Select **Kendo Ui Core Widgets**.
1. (Optional) Rename the project.
1. Click **Get**.

The extension for Visual Studio copies the sample files locally. The extension creates a new solution and project and loads them.

### Run the sample

With the AppBuilder extension for Visual Studio, you can quickly test your apps on device, in the simulator or in the native emulators.

1. [Run in the device simulator.][device simulator]
1. [Run in the companion app.][companion]
1. [Run in the native emulators.][emulators]
1. [Deploy on device via QR code.][QR code]
1. [Deploy via cable connection.][USB deploy]

[Back to Top](#top)

## CLI

With the AppBuilder command-line interface, you can develop hybrid and NativeScript cross-platform mobile apps from the command line. You can learn how to add the AppBuilder commands to your command line from [http://www.telerik.com/appbuilder/command-line-interface](http://www.telerik.com/appbuilder/command-line-interface).

### Clone the sample

1. Verify that a command prompt is running and you are logged in the Telerik Platform in the account in which you want to develop your application.
1. To list the available samples, run the following command.

	```bash
	appbuilder sample
	```
1. Run the clone command for the sample as listed by `appbuilder sample`.
	
	```bash
	appbuilder sample clone kendo-ui-core-widgets
	```

The AppBuilder command-line interface shows the following message: `Successfully initialized project in the folder!`

### Run the sample

With the AppBuilder command-line interface, you can quickly test your apps on device, in the simulator or in the native emulators.

1. [Run in the device simulator.][device simulator]
1. [Run in the companion app.][companion]
1. [Run in the native emulators.][emulators]
1. [Deploy on device via QR code.][QR code]
1. [Deploy via cable connection.][USB deploy]

[Back to Top](#top)

[device simulator]: http://docs.telerik.com/platform/appbuilder/testing-your-app/running-apps-in-simulator/launch-simulator
[companion]: http://docs.telerik.com/platform/appbuilder/testing-your-app/running-on-devices/run-companion/using-appbuilder-companion-app
[QR code]: http://docs.telerik.com/platform/appbuilder/testing-your-app/running-on-devices/deploy-remote
[USB deploy]: http://docs.telerik.com/platform/appbuilder/testing-your-app/running-on-devices/running-on-connected-devices/deploy-connected
[emulators]: http://docs.telerik.com/platform/appbuilder/testing-your-app/running-in-emulators/native-emulators
[Kendo UI API Reference]: http://docs.telerik.com/kendo-ui/api/introduction
[Kendo MVVM]: http://docs.telerik.com/kendo-ui/framework/mvvm/overview
[Application]: http://docs.telerik.com/kendo-ui/mobile/application
[View]: http://docs.telerik.com/kendo-ui/api/javascript/mobile/ui/view
[Tabstrip]: http://docs.telerik.com/kendo-ui/api/javascript/mobile/ui/tabstrip
[NavBar]: http://docs.telerik.com/kendo-ui/api/javascript/mobile/ui/navbar
[Button]: http://docs.telerik.com/kendo-ui/api/javascript/mobile/ui/button
[ListView]: http://docs.telerik.com/kendo-ui/api/javascript/mobile/ui/listview
[ObservableObject]: http://docs.telerik.com/kendo-ui/api/javascript/data/observableobject
[DataSource]: http://docs.telerik.com/kendo-ui/framework/datasource/overview
[Geolocation]: https://www.npmjs.com/package/cordova-plugin-geolocation
[Dialogs (Notification)]: https://www.npmjs.com/package/cordova-plugin-dialogs