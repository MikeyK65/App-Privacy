# DevFlow — Privacy Policy

Applies to DevFlow, published by Mike Kennedy ("the Developer"). It takes precedence
over the [general policy](README.md) for this app.

**The Developer operates no servers and receives no user data.**

## What DevFlow does with your data

DevFlow is a client for Azure DevOps. To function, it connects directly from your
device to Microsoft services:

- **Sign-in.** If you sign in with a Microsoft account, authentication is performed
  with Microsoft Entra ID. Your display name and email address are read from the
  resulting token and shown in the app.
- **Personal Access Tokens.** If you connect using a PAT instead, that token is
  sent only to Microsoft's Azure DevOps API.
- **Your content.** Repositories, pull requests, pipelines, and work items are
  fetched directly from Azure DevOps and displayed on your device.

This information is exchanged solely between your device and Microsoft, and is
governed by the Microsoft Privacy Statement
(https://privacy.microsoft.com/privacystatement) and your organisation's Azure
DevOps configuration. None of it is sent to the Developer.

## What is stored on your device

Access tokens, refresh tokens, Personal Access Tokens, and your organisation and
project settings are stored in the operating system's secure credential store
(iOS/macOS Keychain, Android Keystore, Windows credential storage). Content
fetched from Azure DevOps is held in a short-lived in-memory cache. Signing out
or deleting the app removes this data.

## Subscriptions

Premium subscriptions are processed by the Apple App Store or Google Play. The
Developer does not receive or store payment details.

## What the apps do not do

No analytics, advertising, tracking technologies, or crash-reporting SDKs are
used. No data is sold or shared with third parties for advertising, and no
profile is built about you.

## Children

The apps are not directed at children under 13 and do not knowingly collect
data from them.

## Changes

This policy will be updated before release if any app's data handling changes.

Contact: devmikekennedy@gmail.com

Last updated: 10 August 2026
