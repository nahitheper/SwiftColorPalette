Swift Color Palette
=============================

A SketchApp plugin that making color palette an enum in other words generates Swift Color Theme files from your Sketch documents.  

Swift Color Palette plugin inspired by [**@NatashaTheRobot**](https://github.com/NatashaTheRobot) 's   [blog post](https://www.natashatherobot.com/swift-enum-no-cases/) 

Installation
=============================

[Download](https://github.com/nahitheper/SwiftColorPalette/archive/master.zip) and extract the contents of this repository. Then double-click the `SwiftColorPalette.sketchplugin` bundle to install the plugin.
In [Sketch Toolbox](http://sketchtoolbox.com), search for 'Swift Color Palette' and tap Install.

Short Demo
=============================

<img src="./demo.gif" width="100%" alt="Swift Color Palette" /> 

Usage
=============================
* Rename color palette layer(s)
* Select a layer(s)
* Run using ```Plugins > Menu > Swift Color Palette```
* Select a Export File (optional) or you can choose copy to clipboard.
* Click OK.

Example Code
=============================
```swift
enum ColorPalette {
    static let lightGrayColor =  UIColor(red:0.737, green: 0.769, blue: 0.792, alpha: 1.000)
    static let blueColor =  UIColor(red:0.353, green: 0.510, blue: 0.647, alpha: 1.000)
    static let grayColor =  UIColor(red:0.373, green: 0.373, blue: 0.376, alpha: 1.000)
    static let panelColor =  UIColor(red:0.212, green: 0.227, blue: 0.267, alpha: 1.000)
    static let secondaryColor =  UIColor(red:0.141, green: 0.220, blue: 0.282, alpha: 1.000)
    static let primaryColor =  UIColor(red:0.129, green: 0.133, blue: 0.145, alpha: 1.000)
}
```

Feedback
=========

If you have any questions, find a bug, or have ideas for ways to improve the plugin, ping me on twitter: @nahitheper


