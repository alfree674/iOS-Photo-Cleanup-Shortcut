# iOS Photo Cleanup Shortcut
An iOS Shortcut designed to automate gallery cleanup. It groups past photos into a single album so you can quickly review and delete them, preventing media accumulation.

## Requirements
* Create an album in your iOS Photos app named exactly **Este día** (or modify the target album name directly inside the shortcut).
* Exclude all shared albums to prevent execution errors.

## Installation
* **Quick Install:** Download it directly to your device 👉 **[Install from iCloud](https://www.icloud.com/shortcuts/0dcc5ef7b2174011b2abad4c1f4e3ce5)**.
* **Manual Install:** Download the `.shortcut` file from this repository and open it on your iOS device.

## How it Works
When executed, the shortcut follows this automated flow:
1. **Empties** the "Este día" (This Day) album.
2. **Searches** for photos taken on this exact date over the past 5 years, plus yesterday's photos for recent control.
3. **Excludes** photos saved in shared albums (Cascais 2025, Gredos, Bilbao, amigos, etc.) to avoid permission errors.
4. **Groups** the final results in the "This Day" album, leaving them ready for review.
