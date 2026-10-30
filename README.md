# Hello, Welcome to iOS

A minimal, build-ready SwiftUI iPhone app. The screen displays “Hello, Welcome to iOS.”

## Build on a Mac

Open `HelloWelcomeToiOS.xcodeproj` in Xcode and choose **Product → Build**. The project uses automatic code signing; choose your Apple development team in the project’s Signing & Capabilities settings if you want to run it on a device.

## Build from Windows with GitHub Actions

Push this folder to a GitHub repository, then run **Build iOS app** from the Actions tab. The workflow uses a hosted macOS runner and uploads an unsigned IPA artifact. You can download that artifact from the completed workflow run. An unsigned IPA is a build output, not an installable/signed app; signing requires an Apple certificate and provisioning profile.
