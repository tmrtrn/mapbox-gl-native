# Changelog for Mapbox OS X SDK

## master

* Fixed an issue in which Mapbox.framework was nested inside another folder named Mapbox.framework. ([#4998](https://github.com/mapbox/mapbox-gl-native/pull/4998))
* Fixed a crash passing a mixture of point and shape annotations into `-[MGLMapView addAnnotations:]`. ([#5097](https://github.com/mapbox/mapbox-gl-native/pull/5097))
* Added a new option to `MGLMapDebugMaskOptions`, `MGLMapDebugWireframesMask`, that shows wireframes instead of the usual rendered output. ([#4359](https://github.com/mapbox/mapbox-gl-native/pull/4359))

## 0.1.0

* This version of the Mapbox OS X SDK roughly corresponds to version 3.3.0-alpha.2 of the Mapbox iOS SDK. The two SDKs have very similar feature sets. The main difference is the lack of user location tracking. Some APIs have been adapted to OS X conventions, particularly the use of NSPopover for callout views.
