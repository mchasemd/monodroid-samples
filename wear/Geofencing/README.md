---
name: Xamarin.Android - Geofencing Wearable Sample
description: "Demonstrates the use of geofencing with wearable devices, by sending a notification to the watch when you are within... (Android Wear)"
page_type: sample
languages:
- csharp
products:
- xamarin
extensions:
    tags:
    - androidwear
urlFragment: wear-geofencing
---
# Geofencing Wearable Sample

This sample demonstrates the use of geofencing with wearable devices, by sending a notification to the watch when you are within a certain area.

## Instructions

* Deploy the project called "Geofencing" to your phone or tablet, and the project called "Wearable" to your Android Wear device.
* When you enter the specified coordinates in the constants class, a notification will be sent to the wearable.
* When testing this sample you may need to change the coordinates in the class Constants in the "Geofencing" project to coordinates that are closer to your location. Changing the values YERBA_BUENA_LATITUDE and YERBA_BUENA_LONGITUDE should work.

## Build Requirements

In order to build this solution, you will need the latest version of Xamarin Studio. This sample requires a physical Android 4.3 or higher device, that is connected to an Android Wear device or the Android Wear emulator.

![Geofencing Wearable Sample application screenshot](Screenshots/Starting geofence transition service.png "Geofencing Wearable Sample application screenshot")

## License

Copyright (c) 2005-2008, The Android Open Source Project  
