[//]: # (Linux/Unix Desktops > Desktop Themes > KDE > KDE Plasma > Plasma 6 splashscreen)

<p align="center">
  <img alt="AZKi Kyukurarin Splash Screen" src="contents/splash/images/splash.gif" width="300"/>
</p>

<h1 align="center">AZKi Kyukurarin <i>- a Plasma 6 splashscreen</i></h1>

<p align="center">
  <img alt="Plasma 6 Ready" src="https://img.shields.io/badge/Plasma_6-Ready-blue?style=for-the-badge&logo=kde">
  <img alt="Qt6" src="https://img.shields.io/badge/Built_with-Qt6%20%2F%20QML-purple?style=for-the-badge&logo=qt">
  <img alt="License" src="https://img.shields.io/badge/License-GPLv3-green?style=for-the-badge">
</p>

## Description
A minimal custom animated splash screen for KDE Plasma 6 featuring **AZKi Kyukurarin**.  
This splash screen is implemented using **Qt6 and QML**, the same UI framework used internally by KDE Plasma, allowing smooth animations and native integration with the Plasma 6 splash system.

It replaces the default static splash screen with a more lively animated experience during login.

## Installation

Since this package is not yet on the KDE Store, you can install it manually from the source.

### Manual Installation (Git)

1. **Clone the repository:**
```bash
git clone https://github.com/shandikadav/azki-kyukurarin-splash.git
cd azki-kyukurarin-splash
```

2.  **Install to local KDE directory:**
    ```bash
    # Create directory if it doesn't exist
    mkdir -p ~/.local/share/plasma/look-and-feel/com.shandikadav.azkikyusplash

    # Copy files
    cp -r * ~/.local/share/plasma/look-and-feel/com.shandikadav.azkikyusplash/
    ```

3.  **Activate:**
    * Go to **System Settings** > **Colors & Themes** > **Splash Screen**
    * Select **AZKi Kyukurarin**
    * Click **Apply**

### Testing
You can test the splash screen without logging out by running:

```bash
ksplashqml --test com.shandikadav.azkikyusplash