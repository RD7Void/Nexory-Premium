# Nexory Premium

Memory injection and modification tool for emulators, featuring a key-based licensing system and customizable visual interface.

---

## Table of Contents

- [Getting Started](#getting-started)
- [Login Screen](#login-screen)
- [Side Menu](#side-menu)
- [Main Features](#main-features)
- [Custom Codes](#custom-codes)
- [User Profile](#user-profile)
- [Visual Settings](#visual-settings)
- [Title Bar](#title-bar)
- [Notifications](#notifications)
- [Requirements](#requirements)

---

## Getting Started

1. Open the **HD-Player** emulator.
2. Launch Nexory Premium.
3. Enter your license key on the login screen.
4. Once authenticated, the main menu will be displayed.

---

## Login Screen

When Nexory opens, the first screen requires a **valid license key** to be entered. The key is bound to your machine and verified automatically. If a key has already been saved on your computer, login happens automatically.

If the key expires or is banned, access will be automatically blocked.

---

## Side Menu

The application features a sidebar with **9 navigable sections**.

- **Hover over** the sidebar to expand it and see the name of each section.
- **Click** on any item to navigate to that page.
- The active section is highlighted with a different color, and an animated indicator follows the selection.

---

## Main Features

The main page contains **10 features** with individual toggles to activate and deactivate.

| Feature | Description |
|---|---|
| **AIMBOT HEAD** | Injects auto-aim targeted at the head |
| **AIMBOT AI** | Injects AI-based auto-aim |
| **SCOPE 4X** | Modifies the scope to 4x zoom |
| **SCOPE 2X** | Modifies the scope to 2x zoom |
| **SNIPER SCOPE** | Modifies the sniper scope |
| **SNIPER AIM** | Modifies the sniper aim |
| **CHAMS MENU** | Injects chams menu (player visualization) |
| **BLUE CHAMS** | Injects blue-colored chams |
| **RED CHAMS** | Injects red-colored chams |
| **RGB CHAMS** | Injects chams with animated RGB effect |

### How to Use

1. Make sure the **HD-Player** emulator is running.
2. Click the **toggle** next to the feature name to activate it.
3. Wait for the success or failure notification.
4. To **deactivate**, click the toggle again — memory changes will be reverted automatically.
5. **DLL-type features** (CHAMS MENU, BLUE CHAMS, RED CHAMS, RGB CHAMS) require the **emulator to be restarted** to be fully unloaded.

### Keyboard Shortcuts (Hotkeys)

Each feature has a **hotkey badge** displayed next to its toggle.

- **Click the badge** to start configuring the shortcut.
- **Press the desired key** to register it as a hotkey.
- Press **DEL** to remove the hotkey (set to none).
- Press **ESC** to cancel without making changes.

---

## Custom Codes

In the code creation section, you can build your own personalized injections. There are **two modes** available:

### Read/Write Mode

1. Enter the **code name**.
2. Enter the **search hex** (byte pattern to be located in the emulator's memory).
3. Select the **Read/Write** mode from the dropdown menu.
4. For each offset, define:
   - **Label** — descriptive name for identification.
   - **Read Offset** — address from which the value will be read.
   - **Write Offset** — address where the value will be written.
   - **Write Type** — choose between `bytes`, `int`, or `float`.
5. Click **"+"** to add more offset rows if needed.
6. Click **Add** to save the code.

### Search & Replace Mode

1. Enter the **code name**.
2. Enter the **search hex** (original byte sequence to be found).
3. Select the **Search & Replace** mode from the dropdown menu.
4. Enter the **replace hex** (new bytes that will replace the originals).
5. Click **Add** to save the code.

### Managing Your Codes

All created codes appear in the **My Codes** section. For each code you can:

- **Activate/Deactivate** using the corresponding toggle.
- **Assign a hotkey** by clicking the shortcut badge.
- **Delete** the code by clicking the delete button (trash icon).

---

## User Profile

The profile section displays your license information:

- **Username** associated with the key.
- **Machine ID** bound to the license.
- **Key** (partially hidden for security, showing only the first and last characters).
- **Remaining time** — when less than 3 days remain, a warning notification is displayed automatically.

---

## Visual Settings

On the settings page you can customize the application's appearance:

- **Gradient** — Enables a dark gradient background across the application pages.
- **RGB** — Enables continuous RGB animation on the window border and visual elements. The color cycles in real time.

Both preferences are **saved automatically** and restored every time the application starts.

---

## Title Bar

- **Drag** the title bar to move the window across the screen.
- **Double-click** the title bar to maximize or restore the window size.
- Three buttons in the upper-right corner:
  - **Minimize** — Reduces the window to the taskbar.
  - **Restart** — Closes and reopens the application.
  - **Close** — Fully exits the application.

---

## Notifications

The application displays internal notifications for every action performed:

| Type | When It Appears |
|---|---|
| **Success** | Injection completed, code added, feature deactivated |
| **Failure** | Emulator not found, byte pattern not found, injection error |
| **Warning** | License nearing expiration (less than 3 days remaining) |

---

## Requirements

- **Operating System:** Windows
- **Emulator:** HD-Player must be running for injection features to work.
- **License:** A valid license key is required to access the application. The key is bound to the machine and cannot be used on different computers.
