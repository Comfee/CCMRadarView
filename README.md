CCMRadarView
==============

[![License APACHE](https://img.shields.io/hexpm/l/plug.svg)](https://github.com/cacmartinez/CCMRadarView/blob/master/LICENSE)
[![Release](https://img.shields.io/github/release/cacmartinez/CCMRadarView.svg)](https://github.com/cacmartinez/CCMRadarView)
[![Version](https://img.shields.io/cocoapods/v/CCMRadarView.svg?style=flat)](http://cocoadocs.org/docsets/CCMRadarView)
[![License](https://img.shields.io/cocoapods/l/CCMRadarView.svg?style=flat)](http://cocoadocs.org/docsets/CCMRadarView)
[![Platform](https://img.shields.io/cocoapods/p/CCMRadarView.svg?style=flat)](http://cocoadocs.org/docsets/CCMRadarView)

CCMRadarView is a simple to use view that uses the new IBDesignable and IBInspectable features of XCode6 to easily configure the icon in the center, the width of the waves of the radar, as well as the color, the number of waves,etc.

Here is a sample views of the radar:

Normal Radar

![CCMRadarView](https://github.com/cacmartinez/CCMRadarView/blob/master/Screenshots/radarInUse.gif)

Reversed Radar

![CCMRadarReversedView](https://github.com/cacmartinez/CCMRadarView/blob/master/Screenshots/reversedRadarInUse.gif)

==============

# Usage

In the storyboard draw a view to your controller and assign it the CCMRadarView class, then customize it as you want in the Attributes inspector.

![CCMRadarViewUsage](https://github.com/cacmartinez/CCMRadarView/blob/master/Screenshots/howToUse.gif)

To start and stop animations in the radar, you should call the `startAnimation()` or the `stopAnimation()` methods.

# Requirements

Xcode version 6.0 or later.

# Installation

## Files

Download or clone the repository, and copy the `CCMRadarView.swift` file to your project.

## With CocoaPods

**Requires CocoaPods v0.36.0**

CCMPopup is available through [CocoaPods](http://cocoapods.org). To install
it, simply add `use_frameworks!` line in your Podfile and the following line:

    pod "CCMRadarView"

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Author

Carlos Compean, ccompean@icalialabs.com

## License

CCMRadarView is available under the Apache License, Version 2.0. See the LICENSE file for more info.

