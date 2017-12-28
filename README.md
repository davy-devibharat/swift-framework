Fritz Swift SDK
===============

The Fritz SDK is used to provide insights into your use of CoreML models. Fritz provides seamless over-the-air updates to your models as well as analytics in how well your models are performing on your end-users devices.

## Installation

### Swift Package Manager

The [Swift Package Manager](https://swift.org/package-manager/) is a tool for automating the distribution of Swift code and is integrated into the `swift` compiler.

Once you have your Swift package set up, adding Fritz as a dependency is as easy as adding it to the `dependencies` value of your `Package.swift`.

```swift
dependencies: [
    .Package(url: "https://github.com/fritzlabs/swift-sdk.git", majorVersion: 1)
]
```

### CocoaPods

[CocoaPods](http://cocoapods.org) is a dependency manager for Cocoa projects. You can install it with the following command:

```bash
$ gem install cocoapods
```

> CocoaPods 1.1.0+ is required to build Fritz 1.0.0+.

To integrate Fritz into your Xcode project using CocoaPods, specify it in your `Podfile`:

```
pod update
pod install Fritz '~> 1.0.0-beta'
```
