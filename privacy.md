---
layout: default
title: Privacy Policy
---

# My Hoard — Privacy Policy

**Last updated:** April 9, 2026

My Hoard ("the App") is a Magic: The Gathering card collection tracker and scanner. Your privacy matters to us. This policy explains what data the App collects, how it's used, and your choices.

## Data We Collect

### Card Collection Data
- Cards you scan and add to your collection (card names, quantities, conditions, languages, finish types)
- Decks you create (card lists, deck names, format, notes)
- Folders and organization preferences

**This data is stored locally on your device.** It never leaves your device unless you enable iCloud Sync (Pro feature).

### Camera Access
- The App uses your camera solely to scan Magic: The Gathering cards
- Images are processed on-device in real-time for card recognition
- **No images are stored, uploaded, or transmitted** — all recognition happens locally using on-device OCR and machine learning

### iCloud Sync (Pro Feature)
- If you purchase Pro and enable iCloud Sync, your collection and deck data is synced via Apple's CloudKit
- Data is stored in your personal iCloud account and is not accessible to us
- You can disable sync at any time in Settings

## Data We Do NOT Collect

- **No personal information** (name, email, phone number)
- **No account registration required**
- **No analytics or tracking** (no Firebase, no Amplitude, no third-party SDKs)
- **No advertising**
- **No card images are uploaded** — scanning is entirely on-device

## Third-Party Services

### Scryfall
- The App downloads card data (names, sets, prices, images) from [Scryfall](https://scryfall.com), a public Magic: The Gathering database
- Scryfall's privacy policy: [https://scryfall.com/docs/privacy](https://scryfall.com/docs/privacy)
- No personal data is sent to Scryfall — only standard HTTP requests for card data

### Apple (StoreKit & CloudKit)
- In-app purchases are processed by Apple via StoreKit
- iCloud sync uses Apple's CloudKit
- Apple's privacy policy: [https://www.apple.com/privacy/](https://www.apple.com/privacy/)

## Data Storage

| Data | Storage Location | Shared? |
|------|-----------------|---------|
| Collection & decks | On-device (SwiftData) | No (unless iCloud Sync enabled) |
| Card database | On-device (SQLite) | No |
| Scanner data (art hashes, embeddings, tags) | On-device | No |
| Scan images | Not stored | N/A |
| Purchase status | On-device + Apple | Apple only |

## Your Choices

- **Delete your data** at any time by deleting the App
- **Disable iCloud Sync** in Settings to keep data local-only
- **Revoke camera access** in iOS Settings → My Hoard
- **Export your data** via CSV or JSON from the App's settings

## Children's Privacy

The App does not knowingly collect data from children under 13. The App has no accounts, no social features, and no user-generated content visible to others.

## Changes

We may update this policy from time to time. Changes will be posted on this page with an updated date.

## Contact

Questions about this policy? [Open an issue on GitHub](https://github.com/cheokjiade/MyHoard-Public/issues).
