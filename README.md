| <img alt="logo" src="https://raw.githubusercontent.com/CocoaDebug/CocoaDebug/master/pic/logo.png" width="250"/> |  |
| -------------- | -------------- |
| Version | [![CocoaPods Compatible](https://img.shields.io/cocoapods/v/CocoaDebug.svg)](https://img.shields.io/cocoapods/v/CocoaDebug.svg) |
| Platform | ![Platform](https://img.shields.io/badge/platforms-iOS%2012.0+-blue.svg) |
| Languages | ![Languages](https://img.shields.io/badge/languages-Swift%20%7C%20ObjC-blue.svg) |

<span style="float:none" />

## Screenshot

<img src="https://raw.githubusercontent.com/CocoaDebug/CocoaDebug/master/pic/b1.png" width="250">
<img src="https://raw.githubusercontent.com/CocoaDebug/CocoaDebug/master/pic/b5.png" width="250">
<img src="https://raw.githubusercontent.com/CocoaDebug/CocoaDebug/master/pic/b2.png" width="250">
<img src="https://raw.githubusercontent.com/CocoaDebug/CocoaDebug/master/pic/b3.png" width="250">
<img src="https://raw.githubusercontent.com/CocoaDebug/CocoaDebug/master/pic/b4.png" width="250">

## Introduction

- 👉 List network requests inside APP.

- 👉 List *print()* and *NSLog()* Xcode console logs.

- 👉 List sandbox folders and files.

- 👉 List APP and device informations, including: *app version/build*, *bundle name/id*, *screen resolution*, *device*, *iOS version*


## Tips

- [x] Support shake to hide or show the black bubble. (Support iPhone device and simulator)

- [x] Support share network details via email or copy to clipboard when you are in the *Network Details* page.

- [x] Support copy logs. (Long press the text, then select all or select copy)

- [x] Support search logs by keyword.

- [x] Support long press the black bubble to clean all network logs. (For ease of use)

- [x] Support add your custom test controller. (See demo project)

- [x] Support to preview and edit Sandbox files.

- [x] Support App->Network/Console-Logs to switch on/off monitor functions without coding. (Default value is on)

## Installation

### *CocoaPods*

```ruby
target 'YourTargetName' do
    use_frameworks!
    pod 'CocoaDebug', :configurations => ['Debug']
end
```

## Reference

[https://developer.apple.com/library/archive/samplecode/CustomHTTPProtocol/Introduction/Intro.html](https://developer.apple.com/library/archive/samplecode/CustomHTTPProtocol/Introduction/Intro.html)
