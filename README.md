# ZPL for Swift

Swift Package Manager distribution of the [ZPL parser and renderer](https://github.com/codyps/zpl) for macOS and iOS.

The first package release is being prepared in [codyps/zpl#86](https://github.com/codyps/zpl/pull/86). No Swift version has been published yet.

Implementation, tests, and release tooling live in the source repository's `zpl-swift/` directory. Release automation replaces this repository with the tested Swift sources, a manifest referencing the checksummed XCFramework, and a matching semantic version tag.
