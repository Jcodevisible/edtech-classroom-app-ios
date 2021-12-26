# 💬 Virtual Classroom App for iOS with Azure Communication Services [![](https://img.shields.io/twitter/url?url=https%3A%2F%2Fgithub.com%2FGetStream%2Fedtech-classroom-app-ios)](https://twitter.com/intent/tweet?text=Want%20to%20build%20an%20edtech%20virtual%20classroom%20app%20for%20iOS%20with%20video%20and%20chat%3F%20Learn%20how%3A&url=https%3A%2F%2Fgithub.com%2FGetStream%2Fedtech-classroom-app-ios)

<img align="right" src="https://i.imgur.com/Ev4caua.png" width="50%" />

## 📚 Tutorial

This repository contains the iOS Lab project following the **Microsoft GEARS 2022 - Azure Communications Mobile Support** demo session. You should read the Lab Guide before trying to run this project as it contains it may contain useful information not presented in this README.

## ⚙️ Setup

## Requirements
- Xcode 11+
- iOS 13+

The following additional prerequisites are needed:
- An Azure account with an active subscription. https://azure.microsoft.com/free/?WT.mc_id=A261C142F
- A Mac running the latest version of Xcode. https://go.microsoft.com/fwLink/p/?LinkID=266532
- A deployed Communication Services resource. https://docs.microsoft.com/en-us/azure/communication-services/quickstarts/create-communication-resource
- A User Access Token for your Azure Communication Service. https://docs.microsoft.com/en-us/azure/communication-services/quickstarts/access-tokens


### Configuration

You should place your ACS token credentials in [`AppDelegate.swift`](VirtualClassroom/AppDelegate.swift#L18-L20).

### Dependencies

To install the dependencies, use CocoaPods in this project's folder:

```bash
$ pod install --repo-update
```

### Running

Run this sample app as any normal app, but only on real devices. If you run in a simulator, the call will work, but you won't be able to watch or stream video due to limitations of the simulator, though voice should work.

## 🔗 Helpful Links

- https://docs.microsoft.com/en-us/azure/communication-services/quickstarts/voice-video-calling/getting-started-with-calling?pivots=platform-ios
- https://docs.microsoft.com/en-us/azure/communication-services/quickstarts/voice-video-calling/get-started-with-video-calling?pivots=platform-ios

