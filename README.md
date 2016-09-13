# CommonCrypto
CommonCrypto module wrapper project for Xcode 8 and Swift 3

# How to use
a) Clone / download this project. Add this project as a subproject to your swift framework / app by dragging .xcodeproj file a little below your main project in Xcode.
b) Build binary for each target which produces CommonCrypto.framework for each platform, then copy those \*.framework files with their parent folders into your parent project via dropping them to Xcode and applying “Copy items if needed” checkbox (unselect any target membership though). If you drop them without folders Xcode will not allow to do that because their names are equivalent.

After you did "a" or "b", just use "import CommonCrypto" statement in your target swift classes, now underlying CommonCrypto C API is available.

## TODO: CocoaPods support
## TODO: Carthage support
## TODO: Explanation how to use that with examples
