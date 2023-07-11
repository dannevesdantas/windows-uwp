---
title: PowerToys File Locksmith utility for Windows
description: A Windows shell extension for checking which files are in use and by which processes.
ms.date: 12/06/2022
ms.topic: article
no-loc: [PowerToys, Windows, File Locksmith, Win]
---

# File Locksmith utility

File Locksmith is a Windows shell extension for checking which files are in use and by which processes.

![File Locksmith Demo.](../images/powertoys-file-locksmith.gif)

## How to activate and use File Locksmith

To activate File Locksmith, open PowerToys and ensure that it is updated to the most recent version and that "Enable File Locksmith" is set to **On** (enabled). Select one or more files or directories in Windows File Explorer. If a directory is selected, all of its subfiles and subdirectories will be scanned as well. Right-click on the selected file(s), choose **Show more options** from the menu to expand your list of menu options, then select **What's using this file?** to open File Locksmith and see which processes are using the file(s).

When File Locksmith is activated, it will scan all of the running processes that it can access, checking which files the processes are using. Processes that are being run by a different user cannot be accessed and may be missing from the list of results. To scan all processes, select the **Restart as administrator** button.

![Restart File Locksmith as administrator.](../images/powertoys-file-locksmith-restart-as-admin.png)

After scanning, a list of processes will be displayed. You can select the **End task** button to terminate the process, or select the expander to show more information.
File Locksmith will automatically remove terminated processes from the list, whether or not this action was done from File Locksmith. To manually refresh the list of processes, select the **Reload** button.
