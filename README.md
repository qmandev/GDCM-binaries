# GDCM-binaries

Prebuilt [GDCM](https://github.com/malaterre/GDCM) 3.0.24 as a Swift Package
Manager-compatible xcframework, distributed as a GitHub Release asset.

**Unofficial build.** Not produced, endorsed, or supported by the GDCM project.

## Release `gdcm-v3.0.24`

| | |
|---|---|
| Asset | `GDCM.xcframework.zip` |
| SHA-256 | `ac6473301f82d20a2a1d94748e0d0db0bd0c3a3d8ce26aa9e12c128cd91c1a5b` |
| Source | GDCM tag `v3.0.24` |
| Slices | macOS (arm64, x86_64), iOS, iOS Simulator, visionOS, visionOS Simulator |
| Toolchain | Xcode 26, CMake 4.x with `CMAKE_POLICY_VERSION_MINIMUM=3.5` |
| Excluded | MEXD and socketxx (DIMSE networking) |

## Use

```swift
.binaryTarget(
    name: "GDCM",
    url: "https://github.com/qmandev/GDCM-binaries/releases/download/gdcm-v3.0.24/GDCM.xcframework.zip",
    checksum: "ac6473301f82d20a2a1d94748e0d0db0bd0c3a3d8ce26aa9e12c128cd91c1a5b"
)
```

## Licenses

GDCM and the components it vendors are distributed under BSD, MIT, IJG,
zlib-style, and Boost terms; none is Apache-2.0. `NOTICE` carries every
attribution and full licence text, and must accompany any binary that links
this framework.
