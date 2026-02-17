# LinuxGate 🐧
A modern, user-friendly Windows application that simplifies the process of dual-booting Linux alongside Windows.

**Remember to star ⭐ this repo & follow me**

## 📥 Download
**[Download LinuxGate v0.1.1-beta](https://github.com/asakpke/LinuxGate/releases/download/v0.1.1-beta/LinuxGate.zip)**

**[Download LinuxGate Installation Files Excluding mint.iso](https://github.com/asakpke/LinuxGate/releases/download/v0.1.1-beta/Installation.Files.Excluding.mint.iso.zip)**

```
Why download installation files?
Server sometime fails to download files, so unzip & copy paste to the same LinuxGate.exe folder. 
Also if you like to download Linux Mint before starting the LinuxGate installation, then copy/paste it as mint.iso to the same folder.
```

## 🚀 Installation
1. **Prepare Files:** Download `LinuxGate.zip`, the **Installation Files**, and **Linux Mint**. Rename the Linux Mint ISO to `mint.iso` and place it in the same folder as `LinuxGate.exe`.
2. **Run Installer:** Launch `LinuxGate.exe` as an administrator.
3. **Configure:** Follow the on-screen instructions to choose Linux Mint, set your partition size, and create your username/password.
4. **Initial Reboot:** Restart your system and select **Install Linux** from the boot menu.
5. **Finalize:** Let the process complete, then restart one final time to finish the setup.

## 🗑️ Uninstallation
1.  **Delete Linux Partition:** Use Windows Disk Management to delete the Linux partition.
2.  **Extend C Drive:** Extend your C drive to reclaim the unallocated space.
3.  **Fix GRUB Bootloader:** 
    *   Adjust the boot order in your BIOS to prioritize Windows Boot Manager.
    *   Utilize third-party tools like EasyBCD to reinstall Windows bootloader.
    *   Use Windows recovery tools (e.g., from a Windows installation media) to repair the bootloader. 

## ⚠️ Project Status - FUNCTIONAL BUT UNSTABLE
**WARNING: This project is functional but NOT RECOMMENDED for production use.**

The software is now working and can successfully set up a dual-boot environment. However, please be aware of the following limitations:

- ⚠️ **BIOS mode only** – UEFI mode has not been tested yet and may not work correctly
- ⚠️ **Not production-ready** – Use at your own risk, preferably on test machines
- ⚠️ **Backup recommended** – Always backup your data before attempting any dual-boot installation

felix068 is actively working on UEFI support and stability improvements. Contributions and bug reports are welcome!

## 📜 Project History
This project was initially started by [MopigamesYT](https://github.com/MopigamesYT) but was abandoned and left incomplete (non-functional). 

LinuxGate is based on the [LinuxGate project](https://github.com/ekimiateam/linuxgate), which was developed by felix068 during a company internship. The LinuxGate project was also left unfinished and non-functional.

This version includes a complete rework by felix068 aimed at creating a stable, functional dual-boot installer.

## 📄 License
This project is licensed under the GNU General Public License 3.0 - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments
- [Rose Pine](https://rosepinetheme.com/) for the color scheme
- [WPF](https://github.com/dotnet/wpf) for the UI framework
- Original concept by [MopigamesYT](https://github.com/MopigamesYT)
- Based on [Libertix](https://github.com/ekimiateam/libertix) project
- Forked from [felix068/LinuxGate](https://github.com/felix068/LinuxGate), thank you for the project 🙏

## ⭐ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=asakpke/LinuxGate&type=date&legend=top-left)](https://www.star-history.com/#asakpke/LinuxGate&type=date&legend=top-left)
