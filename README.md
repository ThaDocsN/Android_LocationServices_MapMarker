# Android_LocationServices_MapMarker

## Overview
Build an app which allows users to place tags on a map and track their current location.

## Requirements
This app will consist of a map acitvity with your own buttons that will center the map on the user's current location and place a map marker on the centered location.

## Outline
1. Create a project with a maps activity
2. Add a maps api key
3. Add location services permissions
4. Add a button for them to select which will center the map on them
5. Add a button for a new pin at the target location
> use `mMap.getCameraPosition().target` to get the `LatLng` of the center of the map

## Go Further
- Allow the user to manually enter a latitude and longitude for a marker
- Use `setOnMarkerClickListener` to respond to when each marker is clicked. You can:
	- Make a toast of the marker's title
	- Store the marker objects which are created when calling `Marker addMarker (MarkerOptions options)` and remove it from the map by calling `marker.remove()`
