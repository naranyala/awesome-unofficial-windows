# Awesome Unofficial Windows [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of unofficial, community-built tools for installing, tweaking, debloating, and customizing Windows.

These projects are **not affiliated with or endorsed by Microsoft**. Most of them modify system settings or rebuild OS images — read the docs, review the scripts, and use them at your own risk.

## Contents

- [Utilities & Tweaks](#utilities--tweaks)
- [Debloat & Privacy](#debloat--privacy)
- [ISO & Image Building](#iso--image-building)
- [Custom Windows Builds](#custom-windows-builds)
- [Bootable Media](#bootable-media)
- [Package Management](#package-management)
- [Shell & Explorer](#shell--explorer)
- [Customization & Theming](#customization--theming)
- [Window Management & Launchers](#window-management--launchers)
- [CLI & Automation](#cli--automation)
- [Security & Hardening](#security--hardening)
- [System Utilities](#system-utilities)
- [Community & Forums](#community--forums)
- [Learning & References](#learning--references)

## Utilities & Tweaks

- [winutil](https://github.com/ChrisTitusTech/winutil) - Chris Titus Tech's Windows utility: install programs, apply tweaks, fix issues, and manage updates from a single GUI (run as admin: `irm https://christitus.com/win | iex`).
- [Sophia Script for Windows](https://github.com/farag2/Sophia-Script-for-Windows) - Massive PowerShell module with hundreds of documented presets for fine-tuning Windows 10/11 without a GUI.
- [ThisIsWin11](https://github.com/builtbybel/ThisIsWin11) - A hands-on tour of Windows 11 that doubles as a modular app installer and tweak console.
- [Flyoobe](https://github.com/builtbybel/Flyoobe) - A wizard-style setup tool that de-bloats and personalizes a fresh Windows 11 install.
- [Bloatboxer](https://github.com/builtbybel/Bloatboxer) - Modern successor to Bloatbox for removing preinstalled apps.
- [SuperMSConfig](https://github.com/builtbybel/SuperMSConfig) - Advanced startup, service, and boot configuration beyond what msconfig offers.

## Debloat & Privacy

- [Win11Debloat](https://github.com/Raphire/Win11Debloat) - Simple, lightweight PowerShell script to remove preinstalled apps, disable telemetry, and declutter Windows 10/11.
- [Windows10Debloater](https://github.com/Sycnex/Windows10Debloater) - PowerShell scripts and a GUI for stripping bloatware and telemetry from Windows 10.
- [debloat-windows-10](https://github.com/W4RH4WK/debloat-windows-10) - Script suite that debloats, tweaks, and hardens a fresh Windows 10 installation.
- [O&O ShutUp10++](https://www.oo-software.com/en/shutup10) - Free privacy tool that lets you control every telemetry and tracking setting with recommended presets.
- [W10Privacy](https://www.w10privacy.de) - Detailed, granular privacy switchboard for Windows 10 and 11, grouped by risk level.
- [Privatezilla](https://github.com/builtbybel/privatezilla) - Integrates Windows 10 privacy settings with a profiling engine to audit and apply a privacy profile.
- [xd-AntiSpy](https://github.com/builtbybel/xd-AntiSpy) - Toggles for disabling Windows 11 telemetry, Copilot, Recall, and other data collection.
- [CleanmgrPlus](https://github.com/builtbybel/CleanmgrPlus) - Extended disk cleaner that exposes cleanup categories Microsoft left out of the classic tool.

## ISO & Image Building

- [tiny11builder](https://github.com/ntdevlabs/tiny11builder) - PowerShell scripts to build a trimmed-down, debloated Windows 11 ISO (regular `tiny11maker.ps1` and ultra-stripped `tiny11coremaker.ps1`) in any language or architecture.
- [UUP dump](https://uupdump.net) - Community site that assembles official Windows Update UUP files into installable ISOs for any build, language, and edition.
- [MediaCreationTool.bat](https://github.com/AveYo/MediaCreationTool.bat) - Universal Windows 10/11 media creation script for downloading official ISOs, ESDs, and UUP builds.
- [ReadySunValley](https://github.com/builtbybel/ReadySunValley) - Checks your PC against Windows 11 requirements and guides you through install workarounds.
- [CloneApp](https://github.com/builtbybel/CloneApp) - Back up and restore app settings and configs before/after an image rebuild.

## Custom Windows Builds

Community-repackaged Windows images with performance, privacy, or UI changes pre-applied. **Unofficial and unsupported: these can lag behind security updates, may break Windows Update or Store apps, and should not be used for banking or work machines without understanding the trade-offs. Prefer building your own image from the tools above.**

- [AtlasOS](https://github.com/Atlas-OS/Atlas) - Open-source Windows modification aimed at latency and throughput tuning for gaming and workstation use.
- [ReviOS](https://revi.cc) - Performance- and privacy-oriented Windows 11 builds with a post-install configuration tool.
- [Ghost Spectre](https://ghostspectre.com) - Modified Windows 10/11 ISOs with optional debloat presets and a lightweight "Superlite" edition.

## Bootable Media

- [Rufus](https://github.com/pbatard/rufus) - Create bootable USB installers from ISOs, with options to bypass TPM, Secure Boot, and Microsoft account requirements.
- [Ventoy](https://github.com/ventoy/Ventoy) - Boot any number of ISOs from one USB stick by simply copying files — no repeated flashing.
- [Hiren's BootCD PE](https://www.hirensbootcd.org) - Community-maintained rescue disk with a Windows 11 PE environment full of recovery and diagnostic tools.

## Package Management

- [Chocolatey](https://github.com/chocolatey/choco) - Mature package manager for Windows with a huge community feed (`choco install <pkg>`).
- [Scoop](https://github.com/ScoopInstaller/Scoop) - Command-line installer that unpacks portable apps into your home directory — no admin, no leftover registry junk.
- [UniGetUI](https://github.com/Devolutions/UniGetUI) - GUI front end for winget, Scoop, Chocolatey, pip, and npm with unified upgrade notifications.
- [Ninite](https://ninite.com) - Batch installer that silently deploys a pick-and-choose list of popular apps with sane defaults and no toolbars.

## Shell & Explorer

- [ExplorerPatcher](https://github.com/valinet/ExplorerPatcher) - Restores the classic taskbar, Start menu, and tray behavior on Windows 10/11.
- [Open-Shell](https://github.com/Open-Shell/Open-Shell-Menu) - Classic-style Start menu and Explorer enhancements for any Windows version.
- [Bloatynosy](https://github.com/builtbybel/Bloatynosy) - Opinionated Windows 11 tuning hub with categorized tweaks and recommendations.
- [FluentTweaker](https://github.com/builtbybel/FluentTweaker) - Toggles for visual styles, context menus, and taskbar behavior.

## Customization & Theming

- [TranslucentTB](https://github.com/TranslucentTB/TranslucentTB) - Makes the taskbar translucent, transparent, or blurred, with per-desk and per-state profiles.
- [DWMBlurGlass](https://github.com/Maplespe/DWMBlurGlass) - Adds acrylic and blur effects to title bars across Windows 10/11.
- [SecureUxTheme](https://github.com/namazso/SecureUxTheme) - Applies unsigned visual styles without disabling Secure Boot or patching system files on disk.
- [Windhawk](https://github.com/ramensoftware/windhawk) - Customization marketplace with mods that patch and restyle Explorer, Start menu, and system components.
- [Seelen UI](https://github.com/eythaann/Seelen-UI) - Fully customizable desktop environment replacement with bars, docks, and workspaces.

## Window Management & Launchers

- [GlazeWM](https://github.com/glzr-io/glazewm) - Tiling window manager for Windows inspired by i3, controlled entirely from the keyboard.
- [komorebi](https://github.com/LGUG2Z/komorebi) - Dynamic tiling window manager for Windows with a Rust core and scripting via a shippable CLI.
- [Flow Launcher](https://github.com/Flow-Launcher/Flow.Launcher) - Quick file search and app launcher with community plugins, hotkeys, and calculation built in.

## CLI & Automation

- [AutoHotkey](https://github.com/AutoHotkey/AutoHotkey) - The classic macro and automation scripting language for remapping keys, strings, and whole workflows.
- [clink](https://github.com/chrisant996/clink) - Adds Bash-style line editing, completion, and history to the stock `cmd.exe` prompt.
- [oh-my-posh](https://github.com/JanDeDobbeleer/oh-my-posh) - Prompt theme engine for PowerShell, cmd, Bash, and Fish with repository status and status-line widgets.

## Security & Hardening

- [HardeningKitty](https://github.com/scipag/HardeningKitty) - Audits and hardens Windows security settings against known baselines, reporting per-setting results.
- [windows_hardening](https://github.com/0x6d69636b/windows_hardening) - Maintained list of Windows hardening settings with Group Policy and registry exports.
- [StevenBlack/hosts](https://github.com/StevenBlack/hosts) - Consolidated hosts file blocking ad, malware, and porn domains — drop-in for `C:\Windows\System32\drivers\etc\hosts`.
- [Sandboxie-Plus](https://github.com/sandboxie-plus/Sandboxie) - Open-source sandbox that runs untrusted programs in an isolated container instead of on the real system.

## System Utilities

- [System Informer](https://github.com/winsiderss/systeminformer) - The maintained successor to Process Hacker: process, service, and network monitoring with malware inspection.
- [Everything](https://www.voidtools.com) - Instant filename search across every NTFS volume; the fastest file locator on Windows.
- [burnbytes](https://github.com/builtbybel/burnbytes) - Lightweight visualizer for what Windows cleanup utilities actually delete.
- [Appcopier](https://github.com/builtbybel/Appcopier) - Clone installed app lists between machines when migrating to a fresh install.

## Community & Forums

- [MSFN Forums](https://forums.msfn.org/) - Long-running home of the nLite/vLite and unattended-install crowd; deep Windows customization knowledge.
- [TenForums](https://www.tenforums.com/) - Large independent Windows 10/11 help forum with extensive tutorials and a sister network of version-specific boards.
- [Wilders Security Forums](https://www.wilderssecurity.com/) - Security-focused discussion of Windows configuration, sandboxes, and privacy tooling.
- [Neowin](https://neowin.net) - Independent tech community covering Windows builds, insider leaks, and releases.
- [MajorGeeks](https://www.majorgeeks.com) - Long-running software archive with forums and hand-tested downloads.
- [r/Windows11](https://www.reddit.com/r/Windows11/) - Reddit's largest Windows 11 community for support, news, and customization showcases.
- [r/Windows10](https://www.reddit.com/r/Windows10/) - Reddit's Windows 10 community, still very active around EOL and LTSC topics.

## Learning & References

- [winutil docs](https://winutil.christitus.com/) - Official documentation for winutil, including known issues.
- [tiny11builder README](https://github.com/ntdevlabs/tiny11builder#readme) - What gets removed from the image, script variants, and usage instructions.
- [Winaero](https://www.winaero.com) - Blog and download site documenting obscure Windows settings, tweakers, and behavior changes.
- [Chris Titus Tech](https://christitus.com/windows-tool/) - Background articles and videos on the Windows utility ecosystem.

## Contributing

Contributions welcome! Read [CONTRIBUTING.md](CONTRIBUTING.md) for the rules — basically: unofficial/community-maintained projects only, working links, and a short factual description.

---

To the extent possible under law, this list is offered under the [MIT License](LICENSE).
