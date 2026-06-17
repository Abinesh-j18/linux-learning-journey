# Installing Ubuntu on Windows WSL

## Overview

In this lab, I installed Ubuntu on Windows using Windows Subsystem for Linux (WSL).

WSL allows Linux to run directly on Windows without installing a virtual machine.

---

## Prerequisites

Before installing WSL, I enabled the following Windows features:

- Virtual Machine Platform
- Windows Subsystem for Linux

To enable them:

1. Press `Windows + R`
2. Type `optionalfeatures`
3. Press Enter
4. Enable:
   - Virtual Machine Platform
   - Windows Subsystem for Linux
5. Restart the computer

---

## Installing WSL

Open PowerShell as Administrator and run:

```powershell
wsl --install
```

After installation, restart the computer if prompted.

---

## Launching Ubuntu

After the restart:

1. Open Ubuntu from the Start Menu
2. Wait for the setup to complete
3. Create a username
4. Create a password

Ubuntu is now ready to use.

---

## Verification Commands

Check WSL version:

```powershell
wsl --version
```

Check installed Linux distributions:

```powershell
wsl -l -v
```

Example:

```powershell
NAME      STATE    VERSION
Ubuntu    Running  2
```

---

## What I Learned

- What WSL is
- How to enable required Windows features
- How to install Ubuntu on Windows
- How to launch Ubuntu for the first time
- How to verify the installation

---

## Screenshots

### Enable Windows Features

![Windows Features](windows-features.png)

### Install WSL

![WSL Installation](wsl-installation.png)

### Ubuntu First Launch

![Ubuntu First Launch](ubuntu-first-launch.png)

### Verify Installation

![WSL Version](wsl-version.png)


---

## Conclusion

WSL provides a simple way to run Linux on Windows. It is useful for learning Linux, cybersecurity, scripting, and system administration without needing a separate virtual machine.
