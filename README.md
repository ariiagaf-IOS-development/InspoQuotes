# InspoQuotes

![Swift](https://img.shields.io/badge/Swift-5-orange)
![UIKit](https://img.shields.io/badge/UIKit-iOS-blue)
![StoreKit](https://img.shields.io/badge/StoreKit-In--App%20Purchase-green)
![Storyboard](https://img.shields.io/badge/Storyboard-Interface-lightgrey)
![UserDefaults](https://img.shields.io/badge/UserDefaults-Local%20Storage-yellowgreen)

<p align="center">
  <img src="images/main-screen.png" width="250">
  <img src="images/premium-row.png" width="250">
  <img src="images/premium-enabled.png" width="250">
</p>

## Overview

**InspoQuotes** is a simple iOS app that displays motivational quotes and allows users to unlock premium quotes through a local in-app purchase flow.

## Features

- View free inspirational quotes
- Unlock premium quotes with in-app purchase
- Restore previous purchases
- Save purchase state locally with `UserDefaults`
- Test purchases locally with a `.storekit` configuration file

## Tech Stack

- Swift
- UIKit
- StoreKit
- Storyboard
- UserDefaults

## In-App Purchase

- **Product Type:** Non-Consumable
- **Product ID:** `com.arina.InspoQuotes.PremiumQuotes`

## StoreKit Testing

This project uses a local StoreKit configuration file:

- `PremiumQuotesConfig.storekit`

To test purchases in Xcode:

1. Open **Edit Scheme**
2. Go to **Run → Options**
3. Select `PremiumQuotesConfig.storekit` in **StoreKit Configuration**

## Author

Student implementation by **Arina Agafonova**  
Based on learning materials from **The App Brewery iOS course** by **Angela Yu**
