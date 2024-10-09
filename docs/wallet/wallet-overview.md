---
id: wallet-overview
title: Wallet Overview
sidebar_label: Overview
description: Wallet features.
keywords:
  - docs
  - polygon id
  - wallet
---

A digital wallet is an application that can hold and manage users' `Credentials`. Based on the principles of Self-Sovereign Identity (SSI) and cryptography, a wallet helps its Holder share data with others without exposing any other sensitive private information. Only the wallet holder has the right to decide which information to share and what needs to remain private.

Polygon ID offers some interesting ways to get started with leveraging a credential-focused wallet: [**the Wallet SDK**](#wallet-sdk) and [**the Polygon ID Wallet app**](#polygon-id-wallet-app).

## Wallet SDK

The Wallet SDK is a Flutter-based SDK that can be used by developers to build applications or integrate the wallet functionalities seamlessly with their existing apps. [Get started with the Wallet SDK here](./wallet-sdk/polygonid-sdk/polygonid-sdk-overview.md).

These are the modules (SDKs) we provide:

- [polygonid-flutter-sdk](https://github.com/0xPolygonID/polygonid-flutter-sdk) \[Dart plugin\]
- polygonid-ios-wrapper-sdk \[Swift lib (Framework)\] (_work in progress_)
- [polygonid-android-wrapper-sdk](https://github.com/0xPolygonID/polygonid-android-sdk) \[Kotlin lib (.aar)\]
- Polygonid-react-native-wrapper-sdk \[RN lib\] (_work in progress_)

Depending on which type of developer (integrator) you are, you can use different modules (SDK):

- Flutter developers should use "polygonid-flutter-sdk"
- IOS developers should use "polygonid-ios-wrapper-sdk"
- Android developers should use "polygonid-android-wrapper-sdk"
- React native developers can use several modules (SDKs):
  - "polygonid-ios-wrapper-sdk" AND "polygonid-android-wrapper-sdk" (together for supporting both platforms)
    OR
  - "polygonid-react-native-wrapper-sdk" (_work in progress_)

:::info

If you are interested in building web-based applications with Polygon ID, please visit the [<ins>JS SDK documentation</ins>](/docs/js-sdk/js-sdk-overview.md).

:::
