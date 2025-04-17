#  Apple Fonts Collection

This repository contains a collection of official Apple fonts, extracted from Apple’s publicly available DMG font packages.
It’s intended for developers, designers, and typography enthusiasts who want quick access to these fonts for personal projects, prototyping, or testing on macOS and other platforms.

## 📁 Repository Structure

- **SF-Pro**: The main San Francisco font family.
- **SF-Compact**: A more space-efficient variant of SF, often used on watchOS.
- **SF-Mono**: The monospaced version of San Francisco.
- **NewYork**: A serif font by Apple.
- **SF-Arabic**, **SF-Armenian**, **SF-Georgian**, **SF-Hebrew**: Regional adaptations of the San Francisco font.

## 📦 How to Use

1. Download or clone the repository.
2. Install the fonts you need by opening the `.ttf` or `.otf` files.
3. Start using them in your design or development tools.

## 🐧 Using on Linux

To install these fonts on Linux:

1. Copy the font folders or specific `.ttf`/`.otf` files to your local fonts directory:

   ```
   ~/.local/share/fonts/
   ```

   Or for system-wide installation:

   ```
   /usr/share/fonts/
   ```

2. Update the font cache:

   ```
   fc-cache -f -v
   ```

3. The fonts should now be available in your applications.

You can verify the installation by running:

```
fc-list | grep "SF Pro"
```

(or replace with any other font name you installed)

## ⚠️ Disclaimer

These fonts are the property of Apple Inc.
They are provided here **for personal use and testing purposes only**.
Please review [Apple's font license agreement](https://developer.apple.com/fonts) before using them in any commercial project or distribution.
