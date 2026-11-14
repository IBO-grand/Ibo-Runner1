# Ibo Runner — iOS IPA & Xcode Project

Bundle ID: `com.ibostudio.iborunner`
Version: `1.0.1 (1)`
Minimum iOS: `15.0`

## Build .ipa without a Mac (GitHub Actions)
1. Push this folder to a GitHub repository.
2. Open **Actions → Build Unsigned iOS IPA → Run workflow**.
3. Download the `IboRunner-ipa` artifact (`IboRunner-unsigned.ipa`).
4. Sideload onto your iPhone using Sideloadly, AltStore, or TrollStore.

## Build directly on Mac (Xcode)
1. Open `IboRunner.xcodeproj` in Xcode.
2. Select your Apple ID team in **Signing & Capabilities**.
3. Connect your iPhone and click **Run** (or **Product → Archive → Distribute App** to export a signed `.ipa`).
