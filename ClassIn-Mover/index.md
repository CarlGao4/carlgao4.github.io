---
layout: cimover
title: "ClassIn Mover"
nofooter: true
---

# [![ClassIn-Mover icon 32x32](ClassIn_Mover_32.png) ClassIn Mover ![GitHub all releases](https://img.shields.io/github/downloads/CarlGao4/ClassIn-Mover/total)](https://carlgao4.github.io/ClassIn-Mover/) 

[简体中文](zh-cn)

A program to move `ClassIn` classroom window in order to exit from focused learning mode.

Supported `ClassIn` version: `3.0.2.130` to `3.0.5.1`, as well as `3.0.7.x` `4.x`. (`ClassIn` prior to `3.0.2.130` does not have focused learning mode at all)

Please remember that this project only aims at helping those whose studies have been influenced by focused learning mode because of failure of taking screenshots, looking up information or other reasons similar to these, but not fulfilling some students' wish of resisting learning.

Maybe the program will lose efficacy in the future versions.

## Downloads

#### ![GitHub release (latest by date)](https://img.shields.io/github/v/release/CarlGao4/ClassIn-Mover)

#### [Download latest version from Github Release (github.com)](./download_github.html) {#dl_gh}

#### [Download latest version from Gitee mirror (gitee.com)](./download_gitee.html) {#dl_gt}

## Components

### ClassIn Mover Classic

The program remained the old style of v1.0.0, except the modern UI by Tk.

#### Usage

Run this program before entering the classroom, then get into the classroom as normal.

After that, the program will automatically detect the classroom window, and make it unable to occupy the whole screen.

If working well, the program should output one line of log each second, showing the current working status.

### ClassIn Mover

The program will be started on the minimized status, which only a transparent icon is displayed. You can click it to open the main window, which can move, resize, and set z-order (or topmost) of your selected ClassIn window.

Auto patch is enabled as default, which will automatically resize the window into normal state like other applications once a new ClassIn window has been detected. You can disable this feature by right-clicking the minimized icon. The button `Auto Patch` on the main window will not enable this feature, but just patch the selected window.

## Known issues

-   **This program calls native API and thus can only work on Windows.**

## Report

You can report your requirement or an issue on [GitHub issues](https://github.com/CarlGao4/ClassIn-Mover/issues). Gitee issues have been closed. Please remember that English is required even we know most of the users are not native speakers because we respect the open source community.

## [Version history](releases)