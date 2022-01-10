# Xamarin.iOS.Tor

Xamarin.iOS.Tor is the easiest way to embed Tor in your Xamarin.iOS application. It binds c# to [iCepa's objecive-c Tor.framework](https://github.com/iCepa/Tor.framework). The API is not stable yet, and subject to change.

Currently, the framework compiles in static versions of `tor`, `libevent`, `openssl`, and `liblzma` from Tor.framework's release:

|          |         |
|:-------- | -------:|
| tor      | 0.4.6.8  |
| libevent | 2.1.12  |
| OpenSSL  | 1.1.1l  |
| liblzma  | 5.2.5  |

## Requirements

- iOS 8.0 or later
- Xcode 7.0 or later

## Installation 

Embedded frameworks require a minimum deployment target of iOS 8 or OS X Mavericks (10.9).

In .NET CLI:
```bash
dotnet add package Xamarin.iOS.Tor
```

You can also just use the `Manage NuGet Package` window on your project in Visual Studio.

Visit the [NuGet website](https://www.nuget.org/packages/Xamarin.iOS.Tor/) for more information.
