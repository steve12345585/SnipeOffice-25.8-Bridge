# SnipeOffice 25.8 (Bridge Branch) 🏹

This repository contains the **Bridge Branch** of the SnipeOffice suite. While our other branches target modern Windows 11 or ultra-legacy PowerPC/XP systems, this version is specifically built from the **LibreOffice 7.2.7 framework** to provide the best stability for mid-era "Modern Legacy" systems.

## 🎯 Target Systems
This branch is optimized for:
- **Windows:** 7 (SP1), 8, 8.1, and Server 2012.
- **Windows 9:** Full support for the [Windows 9 Developer Preview/Community Edition](https://windows9.4up.eu/).
- **macOS:** 10.10 (Yosemite) through 10.15 (Catalina).
- **Linux:** Ubuntu 18.04 LTS (Bionic Beaver) and derivatives.

## ✨ Branch-Specific Features
- **CSV BOM Support:** Backporting the `WriteBOM()` flag to the 7.2.7 Calc export filters to fix Excel compatibility on Windows 7/8.
- **Interface Alignment:** Updating the 7.2.7 UI icons and NotebookBar to match the aesthetic of SnipeOffice 25.8 (Main Branch) while retaining the GDI/Quartz rendering stability.
- **Format Parity:** Backporting OOXML filter updates from the 2025/2026 codebases to ensure file parity with the Windows 11 version of SnipeOffice.

## 🛠 Why 7.2.7?
We chose the 7.2.7 core for this branch because it is the "Goldilocks" version for these operating systems—it supports modern 64-bit architecture and high-DPI scaling without the heavy system requirements or incompatible APIs introduced in the later 24.x/25.x LibreOffice cycles.

## 🤝 Contributing
Please ensure pull requests are targeted at the `bridge-development` branch. If you are looking for the PowerPC/XP or Windows 11 versions, please see our organization's other repositories.

## ⚖️ License
SnipeOffice is licensed under the **MPL-2.0**.