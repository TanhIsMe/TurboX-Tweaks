# TurboX Tweaks - This script classic optimize windows                                     
<p align="center">
	<a href="https://github.com/TanhIsMe/TurboX-Tweaks" target="_blank">
   		<img src="https://github.com/TanhIsMe/TurboX-Tweaks/raw/refs/heads/main/files/banner.png">
	</a>
</p>




**Version 1.0**  
*All in one tool, include optimize and debloat windows to faster.*

![GitHub release](https://img.shields.io/badge/release-v1.0-blue)  
![Batch](https://img.shields.io/badge/Batch-Windows_10%2F11-green)  
![License](https://img.shields.io/badge/license-MIT-lightgrey)

---

## 📌 What it does

This **batch‑based** tool but it start in gui *Python*:
- Command CMD Automatic Optimize Windows
- Modify registry to get a high performance
- Service management (disable telemetry, Cortana, etc.)
- AppX package removal (bloatware)
- Import Power Plan better to custom power highest

Every tweak has been individually tested on clean Windows 10/11 systems.

---
## 🔨 Installation Manual
1. Go to [Releases](https://github.com/TanhIsMe/TurboX-Tweaks/releases/latest) page
2. Download and run as Administrator `EasyWin.bat`

## ⚡ Quick Launch

Copy and paste this command into **PowerShell (Run as Administrator)** – it downloads and runs the batch file automatically:

```powershell
irm https://tanhisme.github.io/TurboX-Tweaks/install.ps1 | iex
```

> [!IMPORTANT]
> **Use at your own risk.** This script modifies the Windows registry, services and installed apps. If you don't understand what a command does, do not run it.

---

⚠️ Caution – Performance vs. Security

· Can break kernel‑level anti‑cheat systems (e.g., Easy Anti‑Cheat, BattlEye) – games may refuse to launch.
· Lower your protection against speculative‑execution exploits (Spectre/Meltdown).
· Are not recommended for enterprise or shared environments.

The script always asks for your explicit confirmation before applying these specific tweaks – you can skip them safely.

If you do not understand what a command does, do not run it.

---
# The preview of tweak EasyWin
![Banner](files/logo.png)
</div>

--- 

📜 License

Released under the MIT License.
You are free to modify and distribute this software, provided that proper attribution is given to the original author.

---

📁 Repository structure

```
EasyWinTweak/
├── install.ps1.            # Use batch by powershell
├── EasyWinTweak.bat        # Main batch script
├── files/                  # The important file to work tweaks
├── backups/                # The batch backup if the tweaks beta version error
└── README.md               # This file
```

