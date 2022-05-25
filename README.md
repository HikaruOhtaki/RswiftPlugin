# SwiftLintPlugin

SwiftPM build tool plugin for Rswift

## Usage

### Package.swift

```swift
dependencies: [
    .package(url: "https://github.com/HikaruOhtaki/RSwiftPlugin", branch: "main"),
],
targets: [
    .target(
        name: "App",
        plugins: [
            .plugin(name: "RSwiftPlugin", package: "RSwiftPlugin"),
        ]
    )
]
```
