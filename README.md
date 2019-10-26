# XamarinAppIntro

[![NuGet version (XamarinAppIntro)](https://img.shields.io/nuget/v/XamarinAppIntro.svg?style=flat-square)](https://www.nuget.org/packages/XamarinAppIntro/)

This repository contains a Xamarin.Android binding library for the latest non-androidx version of the [AppIntro](https://github.com/AppIntro/AppIntro) java/android library. AppIntro enables you to add onboarding experiences to your android app easily. See [the AppIntro repo](https://github.com/AppIntro/AppIntro) for more information. This binding library enables you to utilize AppIntro's features from Xamaron.Android apps easily.

## Dependencies

* `Xamarin.Android.Support.v7.AppCompat` Version 28.0.0.3

Currently the binding library is build with `MonoAndroid8.0` as target. It should be possible to have a lower target, as AppIntro itself and the AppCompat library have lower targets, but this is currently not a requirement for me.