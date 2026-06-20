# Azeno42 Tech's Windows Wizard (v0.1-Alpha)

A lightweight, powerful, and interactive PowerShell-based post-install tool designed to debloat Windows and install essential software seamlessly. Built for power users who want maximum performance and zero bloat right after a fresh Windows installation.

## 🚀 Features (v0.1-Alpha)
- **Multi-Language Support:** Full English and Türkçe localization built right into the core architecture.
- **Dynamic UWP Debloater:** Scans your system in real-time for removable Microsoft Store/UWP applications, maps them with safe filters to protect core OS files, and lets you batch-uninstall via comma-separated numbers (e.g., `1,3,5`).
- **Clean UI View:** Displays user-friendly app names alongside their raw system package names in subtle gray for maximum clarity.
- **Categorized Winget Package Installer:** Installs the most popular web browsers, gaming launchers, and development/creativity tools silently in the background using Windows Package Manager.
- **System Information:** A quick standalone module to review your OS caption, hardware architecture, and active environment details.

## 🔮 Future Roadmap & Vision
This tool is just the beginning. The ultimate goal for **Azeno42 Tech Wizard** is to evolve into a universal cross-platform deployment and flashing hub:
- **Universal Android Flashing & Recovery Tool:** Integration with ADB/Fastboot to automatically detect connected Android devices, cross-reference models via a dynamic server-side database, and flash custom recoveries (TWRP/OrangeFox) or Stock/Custom ROMs automatically.
- **Advanced Windows Tweaks:** Registry-based performance optimizations, telemetry removal, and deep gaming/ping tweaks.

## 🛠️ How to Run
1. Open **PowerShell** as an **Administrator**.
2. Temporarily bypass execution policy to run the script:
```powershell
   Set-ExecutionPolicy Unrestricted -Scope Process -Force
```
3. Navigate to the script directory and execute:
```powershell
   .\A42's_Win_Wizard.ps1
```

## 📝 License & Credits
Developed entirely by Azeno42 (Muratcan Yücepur). Feel free to submit issues or pull requests to improve the script!
