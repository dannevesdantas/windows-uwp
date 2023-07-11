---
title: Latest downloads for the Windows App SDK
description: Latest downloads for the Windows App SDK, including the installer and MSIX packages
ms.topic: article
ms.date: 04/05/2023
keywords: windows win32, windows app development, Windows App SDK
ms.localizationpriority: medium
---

# Latest downloads for the Windows App SDK

This page provides download links to the *latest* releases of the [Windows App SDK](index.md) in the three release channels (stable, preview, and experimental). To get started quickly, download the latest x64 installer below. Or, for older releases, see [Older downloads for the Windows App SDK](./older-downloads.md).

> [!div class="button" style="text-align: left;" width="150px;"] 
> [Download the latest x64 stable installer (1.3.2)](https://aka.ms/windowsappsdk/1.3/latest/windowsappruntimeinstall-x64.exe)

For all the latest Windows App SDK downloads, refer to the tables and links below. To learn more, see [Windows App SDK release channels](release-channels.md) and the release notes provided below for each version.

## Stable release
### Windows App SDK 1.3

| Version | Runtime downloads |
|---|---|
| [1.3.2 (1.3.230602002)](stable-channel.md#version-132-13230602002) <br> 06/13/2023 <br> [Release notes](stable-channel.md#version-132-13230602002) | [Installer (x64)](https://aka.ms/windowsappsdk/1.3/1.3.230602002/windowsappruntimeinstall-x64.exe) <br/> [Installer (x86)](https://aka.ms/windowsappsdk/1.3/1.3.230602002/windowsappruntimeinstall-x86.exe) <br/> [Installer (arm64)](https://aka.ms/windowsappsdk/1.3/1.3.230602002/windowsappruntimeinstall-arm64.exe) <br/> [Redistributable](https://aka.ms/windowsappsdk/1.3/1.3.230602002/Microsoft.WindowsAppRuntime.Redist.1.3.zip) |
| [1.3.1 (1.3.230502000)](stable-channel.md#version-131-13230502000) <br> 05/09/2023 <br> [Release notes](stable-channel.md#version-131-13230502000) | [Installer (x64)](https://aka.ms/windowsappsdk/1.3/1.3.230502000/windowsappruntimeinstall-x64.exe) <br/> [Installer (x86)](https://aka.ms/windowsappsdk/1.3/1.3.230502000/windowsappruntimeinstall-x86.exe) <br/> [Installer (arm64)](https://aka.ms/windowsappsdk/1.3/1.3.230502000/windowsappruntimeinstall-arm64.exe) <br/> [Redistributable](https://aka.ms/windowsappsdk/1.3/1.3.230502000/Microsoft.WindowsAppRuntime.Redist.1.3.zip) |
| [1.3.0 (1.3.230331000)](stable-channel.md#version-13) <br> 04/12/2023 <br> [Release notes](stable-channel.md#version-13) | [Installer (x64)](https://aka.ms/windowsappsdk/1.3/1.3.230331000/windowsappruntimeinstall-x64.exe) <br/> [Installer (x86)](https://aka.ms/windowsappsdk/1.3/1.3.230331000/windowsappruntimeinstall-x86.exe) <br/> [Installer (arm64)](https://aka.ms/windowsappsdk/1.3/1.3.230331000/windowsappruntimeinstall-arm64.exe) <br/> [Redistributable](https://aka.ms/windowsappsdk/1.3/1.3.230331000/Microsoft.WindowsAppRuntime.Redist.1.3.zip) |

## Preview release
### Windows App SDK 1.3 Preview1

| Version | Runtime downloads |
|---|---|
| [1.3 Preview1 (1.3.230228005-preview1) ](/windows/apps/windows-app-sdk/preview-channel#version-13-preview-1-130-preview1) <br> 03/07/2023 <br> [Release notes](/windows/apps/windows-app-sdk/preview-channel#version-13-preview-130-preview1) | [Installer (x64)](https://aka.ms/windowsappsdk/1.3/1.3.230228005-preview1/windowsappruntimeinstall-x64.exe) <br/> [Installer (x86)](https://aka.ms/windowsappsdk/1.3/1.3.230228005-preview1/windowsappruntimeinstall-x86.exe) <br/> [Installer (arm64)](https://aka.ms/windowsappsdk/1.3/1.3.230228005-preview1/windowsappruntimeinstall-arm64.exe) <br/> [Redistributable](https://aka.ms/windowsappsdk/1.3/1.3.230228005-preview1/Microsoft.WindowsAppRuntime.Redist.1.3.zip) |

## Experimental release
###  Windows App SDK 1.4 Experimental1

| Version | Runtime downloads |
|---|---|
| [1.4 Experimental1 (1.4.230518007-experimental1) ](/windows/apps/windows-app-sdk/experimental-channel#version-14-experimental-140-experimental1) <br> 05/23/2023 <br> [Release notes](/windows/apps/windows-app-sdk/experimental-channel#version-14-experimental-140-experimental1) | [Installer (x64)](https://aka.ms/windowsappsdk/1.4/1.4.230518007-experimental1/windowsappruntimeinstall-x64.exe) <br/> [Installer (x86)](https://aka.ms/windowsappsdk/1.4/1.4.230518007-experimental1/windowsappruntimeinstall-x86.exe) <br/> [Installer (arm64)](https://aka.ms/windowsappsdk/1.4/1.4.230518007-experimental1/windowsappruntimeinstall-arm64.exe) <br/> [Redistributable](https://aka.ms/windowsappsdk/1.4/1.4.230518007-experimental1/Microsoft.WindowsAppRuntime.Redist.1.4.zip) |

Depending on your development scenario, you might require the following:

**SDK downloads**

| Tool&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Description | 
|:------------- |:-------------|
| NuGet package | The [**Microsoft.WindowsAppSDK** NuGet package](https://www.nuget.org/packages/Microsoft.WindowsAppSDK/) provides access to APIs provided by the Windows App SDK. The NuGet package is included with the Visual Studio extension project templates. If you have an existing project in which you want to use the Windows App SDK, you can install the latest version of the Windows App SDK NuGet package in your project directly from Visual Studio. For setup instructions, see [Use the Windows App SDK in an existing project](use-windows-app-sdk-in-existing-project.md).  |

**Runtime downloads**

Apps packaged with external location, and unpackaged apps, that use the Windows App SDK can use the standalone `.exe` runtime installer or MSIX packages to deploy the Windows App SDK package dependencies with them. For setup instructions, see [Windows App SDK deployment guide for framework-dependent apps packaged with external location or unpackaged](deploy-unpackaged-apps.md).

| Tool&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Description | 
|:------------- |:-------------|
| Installer | The standalone .exe installer, **WindowsAppRuntimeInstall.exe**, is available as a separate download beginning with Windows App SDK 1.0.1. It installs the Windows App SDK Runtime which includes the Framework, Main, Singleton and DDLM packages.  |
| Redistributable |  The Windows App Runtime Redistributable (**Microsoft.WindowsAppRuntime.Redist**) is a zip file that includes the installer and MSIX packages for all architectures (x64, x86, and ARM64).|
