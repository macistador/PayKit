# PayKit
[...]

<p align="center">
  <img src="https://github.com/macistador/PayKit/blob/main/IconPayKit.png" width="300" height="300"/>
</p>

- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Other packages](#other-packages)
- [Credits](#credits)
- [License](#license)

## Features

- [x] ....

## Requirements

- iOS 15.0+
- Xcode 12.0+
- Swift 5.5+

## Installation

### SwiftPackageManager

```swift
dependencies: [
    .package(url: "https://github.com/macistador/PayKit", from: "0.0.1")
]
```

## Usage

### Preview

With __SwiftUI__
```swift
        

```

With __UIKit__
```swift
    

```

### Callbacks

Your object needs to conforms __xxxxDelegate__
```swift
extension DemoView: xxxxDelegate {
    
}
```

For more details you may take a look at the sample project.

## Other packages

Meanwhile this library works well alone, it is meant to be complementary to the following app bootstrap packages suite: 

- [CoreKit](https://github.com/macistador/CoreKit): Foundation app requirements: Routing, State management, logging...
- [BackendKit](https://github.com/macistador/BackendKit): Handling remote requests, authentication for Firebase / Supabase
- [DesignKit](https://github.com/macistador/DesignKit): DesignSystem
- [VisualKit](https://github.com/macistador/VisualKit): UI components (SwiftUI Views, ViewModifiers)
- [MediasKit](https://github.com/macistador/MediasKit): Loading, caching & displaying Images, Videos, Audios
- [CameraKit](https://github.com/macistador/CameraKit): Capturing photos, videos and audio with effects
- [PermissionsKit](https://github.com/macistador/PermissionsKit): User permissions handling
- [SocialKit](https://github.com/macistador/SocialKit): Share, invite friends
- [CartoKit](https://github.com/macistador/CartoKit): Locate, display maps
- [AnalyzeKit](https://github.com/macistador/AnalyzeKit): Analytics
- [IntelligenceKit](https://github.com/macistador/IntelligenceKit): Integrate embedded AI models
- [AdsKit](https://github.com/macistador/AdsKit): Displaying ads
- [PayKit](https://github.com/macistador/PayKit): Handling paywalls & inApps

## Credits

PayKit is developed and maintained by Michel-André Chirita. You can follow me on Twitter at @Macistador for updates.

## License

PayKit is released under the MIT license. [See LICENSE](https://github.com/macistador/PayKit/blob/master/LICENSE) for details.
