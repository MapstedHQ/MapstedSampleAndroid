# Mapsted Sample App — Android

A native Android sample application demonstrating how to integrate the **Mapsted Mobile SDK**
(indoor positioning, mapping, wayfinding, and location-based services) into an Android app. Built
against the current **Mapsted SDK 26.7.1** release.

A sample Mapsted licence file is included, providing access to the **Square One Shopping Centre**
(propertyId `504`) so you can run the app out of the box.

## Prerequisites

| | Minimum |
|---|---|
| Android `minSdkVersion` | **26** |
| Android Studio | Ladybug (2024.2)+ |
| JDK | 17 |

The Mapsted Android artifacts (`com.mapsted:android-sdk-core`, `android-sdk-map`, `android-sdk-ui`
`26.7.1`) are resolved from the Mapsted Maven repository
`https://mapstedhq.github.io/mapsted-android-maven` (already configured in the sample's Gradle files).

## Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/MapstedHQ/MapstedSampleAndroid.git
   ```
2. Open one of the sample projects (for example `Sample_Kotlin_Compose`) in Android Studio.
3. Ensure the Mapsted licence file (`demo_android_licence.key`) is present in the app's
   `src/main/assets` folder. The included sample licence covers Square One (propertyId `504`); use
   your own licence key for your own properties.
4. Let Gradle sync, then build and run on a device or emulator (API 26+).

## Documentation

Full integration guides, API references, and getting-started tutorials are available at
[developer.mapsted.com/mobile-sdk](https://developer.mapsted.com/mobile-sdk/).

## Licence

This sample and the Mapsted Mobile SDK are distributed under the Mapsted proprietary licence — see
[`LICENSE`](LICENSE). All rights reserved.
