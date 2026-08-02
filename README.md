# DR Cheatsheet - Cheatsheet PWA 2026

> **DR Cheatsheet is an Android-friendly progressive web app for keeping DaVinci Resolve and TourBox Elite references together in an installable workspace that can also operate offline.**

[![Platform](https://img.shields.io/badge/Platform-Android-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Not%20specified-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/scottethanklib7367/dr-cheatsheet-pwa-2026?style=flat-square)](https://github.com/scottethanklib7367/dr-cheatsheet-pwa-2026)

---

<p align="center">
  <a href="https://scottethanklib7367.github.io/dr-cheatsheet-pwa-2026/">
    <img src="https://img.shields.io/badge/Download-DR%20Cheatsheet%20Latest-brightgreen?style=for-the-badge" alt="Download DR Cheatsheet">
  </a>
</p>

> **[Download DR Cheatsheet](https://scottethanklib7367.github.io/dr-cheatsheet-pwa-2026/)**

---

[Download Latest Build](https://scottethanklib7367.github.io/dr-cheatsheet-pwa-2026/)

---

## Overview

DR Cheatsheet is a compact, browser-based reference tool for DaVinci Resolve users working with a TourBox Elite. The PWA presents both sets of reference material in a format intended for quick consultation while editing or completing related tasks.

The application can be installed and uses cached resources for offline availability, making the references accessible when a network connection is unavailable or inconvenient. A service worker handles application updates so newer resources can reach installed versions as they are released.

---

## What It Includes

- Quick-reference material for DaVinci Resolve
- TourBox Elite reference content
- Installable PWA interface
- Cached resources for offline use
- Service-worker-driven application updates
- Android support
- Browser delivery without a separate native application
- Lightweight reference workspace for editing activities

---

## Getting Started

### Install the hosted application

1. Visit the [latest build](https://scottethanklib7367.github.io/dr-cheatsheet-pwa-2026/) from an Android device.
2. Select the browser's install or add-to-home-screen command, if offered.
3. Open DR Cheatsheet through the shortcut created on the device.

### Check out and run locally

```bash
git clone https://github.com/scottethanklib7367/dr-cheatsheet-pwa-2026.git
cd REPO
```

Start the files with a local web server and open the local URL it provides in a compatible browser. Serving the project over HTTP is recommended when testing PWA installation, service worker registration, offline caching, and update handling.

---

## Working with the App

1. Load DR Cheatsheet in a supported browser.
2. Consult the DaVinci Resolve references as required.
3. Open the TourBox Elite material for controller-specific information.
4. Install the PWA from the browser menu if you want a shortcut for future access.
5. After the resources have been cached, open the application without a network connection.
6. Let the service worker process newer application resources when an updated build becomes available.

---

## Configuration and Local Development

Normal PWA use does not require a separate configuration file. For development, serve the repository through a web server instead of opening the HTML file directly. This setup enables browser testing of installation, service worker registration, resource caching, and update behavior.

---

## Requirements

- An Android device as the primary supported platform
- A modern browser that supports PWAs
- A web server for local development
- Internet access for the first hosted visit and subsequent application updates
- Enough browser storage for the resources cached for offline use

---

## Frequently Asked Questions

### Is DR Cheatsheet available on Android?

Yes. Android is the documented target platform, and DR Cheatsheet is designed to install as a progressive web app.

### Can the app be used without an internet connection?

Yes, after the service worker has cached the required resources. Open the application online at least once before relying on offline access.

### What is the installation process?

Open the hosted build in a compatible browser, then choose its install or add-to-home-screen option.

### How does the app receive updates?

The service worker manages application updates. Once a newer build is published, the browser can update its cached resources through its normal service worker update process.

### What if offline mode does not work?

Connect to the internet and revisit the application so its initial resources can finish loading and be cached. Browser storage limits or service worker restrictions can also prevent offline behavior from working as expected.

### Do I need a settings file?

No. The standard PWA workflow has no separate settings file. For local work, the main configuration concern is serving the project through a web server.

### Where should I report issues or ask questions?

Use the repository's GitHub issue tracker for questions, reproducible bugs, and suggestions for improvements.

---

## Planned Improvements

- Further develop the DaVinci Resolve reference material
- Add and better organize TourBox Elite references
- Refine offline-first navigation and access
- Preserve and maintain service worker update handling
- Continue improving the Android-focused PWA experience

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
