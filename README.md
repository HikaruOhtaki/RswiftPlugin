# RswiftPlugin

SwiftPM build tool plugin for Rswift

## Usage

### Package.swift

```swift
dependencies: [
    .package(url: "https://github.com/HikaruOhtaki/RswiftPlugin", branch: "main"),
],
targets: [
    .target(
        name: "App",
        plugins: [
            .plugin(name: "RswiftPlugin", package: "RswiftPlugin"),
        ]
    )
]
```
