# Repairing a display with the Pixel Xpress Flasher

[← All guides](../README.md)

Use this if your display won't start, keeps restarting, shows a blank screen, or support asks you
to reinstall its software. The **Pixel Xpress Flasher** is a free program for **Windows** and
**Mac**. It reinstalls all of the display's software over a USB cable.

**Your pictures and Wi-Fi settings are kept** unless you choose to erase them.

## What you need

- A Windows 10/11 PC or a Mac with macOS 14 (Sonoma) or newer
- A **USB data cable** for the display. Some cables only charge; if the display isn't found, try
  another cable.
- The Pixel Xpress Flasher, from the **[Releases page](https://github.com/customrailcreations/PixelXpressDocumentation/releases)**:
  - Windows: `PixelXpressFlasher-Setup-<version>.exe`
  - Mac with Apple chip (M1 or newer): `PixelXpressFlasher-<version>-macos-arm64.dmg`
  - Mac with Intel chip: `PixelXpressFlasher-<version>-macos-x86_64.dmg`

  Not sure which Mac you have? Apple menu → **About This Mac**: "Chip: Apple M…" means Apple chip,
  "Processor: Intel" means Intel.

## Install the Flasher

**Windows**
1. Open the downloaded `PixelXpressFlasher-Setup-….exe`.
2. If a blue **"Windows protected your PC"** box appears, click **More info**, then **Run anyway**.
3. Follow the steps. No administrator password is needed. A **Pixel Xpress Flasher** shortcut is
   added to the Start menu (and the desktop if you choose).

**Mac**
1. Open the downloaded `.dmg` file.
2. Drag **PixelXpress Flasher** into **Applications**.
3. The first time you open it, macOS may say it can't check the app. Open **System Settings →
   Privacy & Security**, scroll down, and click **Open Anyway** next to PixelXpress Flasher.

## Reflash the display

1. Open **Pixel Xpress Flasher**.
2. **Unplug** the display's USB cable from the computer, or disconnect its power.
3. Find the small **update button** on the display's circuit board (it's not one of the A, B, X, Y
   buttons).
4. **Hold the update button down** and plug the USB cable into the computer. Then let go.
5. Click **Reflash my display**. The Flasher finds the display and installs the software.
6. Wait for **"Done! The display restarts by itself."** The display restarts and shows your
   pictures, or the Pixel Xpress logo if it has none.

While you do this, a new drive appears on the computer. That's normal; you don't need to open it. On a Mac, a "Disk Not Ejected Properly" message afterwards is also normal.

## Still not working? Erase and reflash

1. Repeat the steps above, but tick **"Also erase settings and pictures (only if it still won't
   start)"** before clicking **Reflash my display**, and confirm.
2. The Flasher erases the display completely, then installs the software. It may ask you to put
   the display in update mode a second time; follow the on-screen steps.
3. Afterwards, set the display up again in the app: **Delete Device** (if it's still listed), then
   **Scan Devices**. See [Getting started](getting-started.md). Re-upload your pictures.

## If the Flasher can't find the display

- Make sure you **held the update button while plugging in**, not after.
- Try another USB cable (it must carry data) and another USB port. Avoid USB hubs.
- Check that a new drive appears on the computer after plugging in with the update button held.
  If it doesn't, the cable or port is the problem.
- If support sent you a software file, use **Choose file…** in the Flasher to select it.
