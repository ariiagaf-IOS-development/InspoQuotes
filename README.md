# InspoQuotes

![Swift](https://img.shields.io/badge/Swift-5-orange)
![UIKit](https://img.shields.io/badge/UIKit-iOS-blue)
![StoreKit](https://img.shields.io/badge/StoreKit-In--App%20Purchase-green)
![Storyboard](https://img.shields.io/badge/Storyboard-Interface-lightgrey)
![UserDefaults](https://img.shields.io/badge/UserDefaults-Local%20Storage-yellowgreen)

<p align="center">
  <img src="https://github.com/user-attachments/assets/21408c52-1965-4da0-9154-70381ed604a6" width="250">
  <img src="https://github.com/user-attachments/assets/c2526c63-4efd-4ec2-9955-a8f0601a9998" width="250">
  <img src="https://github.com/user-attachments/assets/39d114e2-5cef-42d7-9dba-16d1c343dcad" width="250">
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
