---
title: Win32Interop class
description: The **Win32Interop** class is available in .NET 5 and later as part of the [Windows App SDK](/windows/apps/windows-app-sdk/).
ms.topic: article
ms.date: 02/08/2022
keywords: windows 10, windows 11, Windows App SDK, desktop development, winui, Windows UI Library, app sdk, C#, interop
ms.author: stwhi
author: stevewhims
ms.localizationpriority: low
---

# Win32Interop class

As a C# desktop application developer, in .NET 5 and later you can make use of the **Win32Interop** class, whose methods wrap and represent several interoperability functions including the [GetWindowIdFromWindow](/windows/windows-app-sdk/api/win32/microsoft.ui.interop/nf-microsoft-ui-interop-getwindowidfromwindow) function.

The **Win32Interop** class is available in .NET 5 and later as part of the [Windows App SDK](/windows/apps/windows-app-sdk/).

## Definition

Namespace: [Microsoft.UI](microsoft.ui.md)

```csharp
public class Win32Interop
```

## Methods

* [GetDisplayIdFromMonitor(IntPtr)](microsoft.ui.win32interop.getdisplayidfrommonitor.md)
* [GetIconFromIconId(IconId)](microsoft.ui.win32interop.geticonfromiconid.md)
* [GetIconIdFromIcon(IntPtr)](microsoft.ui.win32interop.geticonidfromicon.md)
* [GetMonitorFromDisplayId(DisplayId)](microsoft.ui.win32interop.getmonitorfromdisplayid.md)
* [GetWindowFromWindowId(WindowId)](microsoft.ui.win32interop.getwindowfromwindowid.md)
* [GetWindowIdFromWindow(IntPtr)](microsoft.ui.win32interop.getwindowidfromwindow.md)

## Applies to

| Product | Versions |
|-|-|
|**WinUI 3**|Windows App SDK 1.0|

## See also

* [C# interop APIs for WinUI](../index.md)
* [Call interop APIs from a .NET 5+ app](/windows/apps/desktop/modernize/winrt-com-interop-csharp)
