# 📱 Telebey – App Icons Repository

![Telebey Banner](https://github.com/TelebeyISP/AppIcons/blob/main/Banner_TelebeyISP.png?raw=true)

Welcome to the official **Telebey AppIcons** repository. This folder contains the visual identity assets used for the Telebey mobile app, including icons designed for iOS, Android, and web platforms.

---

## 🎨 About Telebey

**Telebey** is a next-generation digital mobile network brand focused on delivering simple, fast, and flexible connectivity. Our app-first approach gives users full control over their data, eSIMs, subscriptions, and account settings — all within a clean and modern UI.

### The Telebey icon represents:
- 🌐 Modern digital telecom
- 🔗 Connectivity & simplicity
- ✨ A unique and recognizable brand identity
- 📲 Optimized design for app stores and device home screens

---

## 📦 What's Included

This repository contains comprehensive icon sets for all major platforms:

### 🔹 iOS Icons
- Complete icon set for iPhone, iPad, Apple Watch, and Mac
- App Store ready 1024x1024 icon
- All required sizes from 16px to 1024px
- Organized in `Assets.xcassets/AppIcon.appiconset/`

### 🔹 Android Icons
- Adaptive icons for all screen densities
- Material Design compliant
- Organized in density-specific folders (mdpi, hdpi, xhdpi, xxhdpi, xxxhdpi)

### 🔹 Web Icons
- Favicon (16x16, 32x32)
- Apple touch icon
- High-resolution web assets

---

## 📁 Repository Structure

```
AppIcons/
│
├── Assets.xcassets/
│   └── AppIcon.appiconset/
│       ├── Contents.json
│       ├── 16.png
│       ├── 20.png
│       ├── 29.png
│       ├── 32.png
│       ├── 40.png
│       ├── 48.png
│       ├── 50.png
│       ├── 55.png
│       ├── 57.png
│       ├── 58.png
│       ├── 60.png
│       ├── 64.png
│       ├── 66.png
│       ├── 72.png
│       ├── 76.png
│       ├── 80.png
│       ├── 87.png
│       ├── 88.png
│       ├── 92.png
│       ├── 100.png
│       ├── 102.png
│       ├── 108.png
│       ├── 114.png
│       ├── 120.png
│       ├── 128.png
│       ├── 144.png
│       ├── 152.png
│       ├── 167.png
│       ├── 172.png
│       ├── 180.png
│       ├── 196.png
│       ├── 216.png
│       ├── 234.png
│       ├── 256.png
│       ├── 258.png
│       ├── 512.png
│       └── 1024.png
│
├── android/
│   ├── mipmap-mdpi/
│   │   └── ic_TelebeyISP_AppIcon.png
│   ├── mipmap-hdpi/
│   │   └── ic_TelebeyISP_AppIcon.png
│   ├── mipmap-xhdpi/
│   │   └── ic_TelebeyISP_AppIcon.png
│   ├── mipmap-xxhdpi/
│   │   └── ic_TelebeyISP_AppIcon.png
│   └── mipmap-xxxhdpi/
│       └── ic_TelebeyISP_AppIcon.png
│
├── icons/
│   ├── favicon.ico
│   └── apple-icon.png
│
└── Banner_TelebeyISP.png
```

---

## 🛠 Usage Instructions

### 📱 iOS Implementation

1. Copy the entire `Assets.xcassets/AppIcon.appiconset/` folder into your Xcode project
2. The `Contents.json` file automatically maps all icon sizes to their correct usage
3. Xcode will handle the rest!

**Included platforms:**
- iPhone (all sizes)
- iPad (all sizes)
- Apple Watch (38mm, 40mm, 41mm, 42mm, 44mm, 45mm, 49mm)
- Mac (16px to 1024px)
- App Store (1024x1024)

### 🤖 Android Implementation

1. Copy the density-specific folders to your Android project:
   ```
   android/app/src/main/res/mipmap-mdpi/
   android/app/src/main/res/mipmap-hdpi/
   android/app/src/main/res/mipmap-xhdpi/
   android/app/src/main/res/mipmap-xxhdpi/
   android/app/src/main/res/mipmap-xxxhdpi/
   ```

2. Update your `AndroidManifest.xml`:
   ```xml
   <application
       android:icon="@mipmap/ic_TelebeyISP_AppIcon"
       ...>
   ```

**Included densities:**
- mdpi (48x48)
- hdpi (72x72)
- xhdpi (96x96)
- xxhdpi (144x144)
- xxxhdpi (192x192)

### 🌐 Web Implementation

Add these lines to your HTML `<head>`:

```html
<link rel="icon" href="/icons/favicon.ico" />
<link rel="apple-touch-icon" href="/icons/apple-icon.png" />
```

For progressive web apps (PWA), add to your `manifest.json`:

```json
{
  "icons": [
    {
      "src": "/icons/favicon.ico",
      "sizes": "64x64 32x32 24x24 16x16",
      "type": "image/x-icon"
    },
    {
      "src": "/icons/apple-icon.png",
      "sizes": "192x192",
      "type": "image/png"
    }
  ]
}
```

---

## 📐 Icon Specifications

### Design Guidelines
- **Style**: Modern, clean, recognizable
- **Format**: PNG with transparency
- **Color Space**: sRGB
- **Corner Radius**: iOS applies automatically, Android uses adaptive icons

### Size Reference

| Platform | Sizes Available |
|----------|----------------|
| iOS iPhone | 20, 29, 40, 57, 58, 60, 80, 87, 114, 120, 180 |
| iOS iPad | 20, 29, 40, 50, 72, 76, 100, 144, 152, 167 |
| Apple Watch | 48, 55, 66, 80, 88, 92, 100, 102, 108, 172, 196, 216, 234, 258 |
| Mac | 16, 32, 64, 128, 256, 512, 1024 |
| Android | mdpi, hdpi, xhdpi, xxhdpi, xxxhdpi |
| App Store | 1024x1024 |

---

## 🎨 Design Assets

### Banner
The official Telebey banner is included in this repository:
- **File**: `Banner_TelebeyISP.png`
- **Usage**: Marketing materials, GitHub README, documentation

---

## 🔧 Technical Details

### iOS Contents.json
The `Contents.json` file in the iOS folder is pre-configured with all necessary metadata for:
- iPhone app icons (all scales)
- iPad app icons (all scales)
- Apple Watch complications and app launchers
- Mac menu bar and dock icons
- App Store submission

### Android Naming Convention
All Android icons follow the naming pattern:
```
ic_TelebeyISP_AppIcon.png
```

This ensures compatibility with Android Studio and Google Play Store requirements.

---

## 📄 License

All Telebey app icons, logos, and assets are **copyrighted** and may not be used, modified, or redistributed without explicit permission from Telebey.

**© 2025 Telebey. All rights reserved.**

---

## 📞 Contact & Support

For questions, licensing inquiries, or technical support:

- **Website**: [telebey.com](https://telebey.com)
- **Email**: support@telebey.com
- **GitHub Issues**: [Report a problem](https://github.com/TelebeyISP/AppIcons/issues)

---

## 🚀 Quick Start Checklist

- [ ] Download or clone this repository
- [ ] For iOS: Copy `Assets.xcassets/AppIcon.appiconset/` to your Xcode project
- [ ] For Android: Copy `mipmap-*` folders to `android/app/src/main/res/`
- [ ] For Web: Copy files from `icons/` folder to your web root
- [ ] Update your app configuration files (AndroidManifest.xml, Info.plist, etc.)
- [ ] Test on multiple devices and screen sizes
- [ ] Submit to App Store / Google Play Store

---

**Built with ❤️ by the Telebey Team** | Building the Future of Telecommunications
