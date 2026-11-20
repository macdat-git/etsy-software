# 7.8 inch DDU with LEDs

SimHub files and setup guide for the MacDat 7.8 inch Sim Racing DDU with LEDs.

## Download

**[Download the latest DDU files (.zip)](https://github.com/macdat-git/etsy-software/releases?q=ddu-7.8inch-leds)**: open the newest release and click the `.zip` under **Assets**.

You can also download individual files from this folder:

| File | What it is |
|---|---|
| `Quick Start Guide.docx` | Step-by-step SimHub setup with screenshots |
| `Any Game - All Red RPM Leds.ledsprofile` | All-red RPM lights, any game |
| `Any Game - F1 RPM Colors.ledsprofile` | F1-style RPM light colors, any game |
| `F1 Games Match Fanatec Formula 2.5 Wheel.ledsprofile` | F1 games, matches the Fanatec Formula 2.5 wheel LEDs |
| `Forza Motorsport Fanatec Formula 2.5 Wheel.ledsprofile` | Forza Motorsport, matches the Fanatec Formula 2.5 wheel LEDs |
| `IRacing - 16 LED RPMs.ledsprofile` | iRacing 16-LED RPM lights |

## Requirements

- Windows PC
- The latest version of [SimHub](https://www.simhubdash.com/)
- A USB-C cable and a free USB port or powered USB hub

## Quick setup

### Screen

1. Install or update [SimHub](https://www.simhubdash.com/).
2. Connect the DDU to your PC or USB hub with a USB-C cable.
3. In SimHub, open **Devices**, click **+**, then **Add new device**.
4. Scroll to **Vocore**, select **Generic Vocore Screen**, and click **OK**. The DDU activates.
5. If you have more than one screen, enable **Connect to specific screen** and pick the new DDU's hardware ID. Try each one until the new DDU shows the dashboard.
6. Use **Screen Settings** to change rotation or touch-screen options.

### LEDs

1. In SimHub, open **Arduino**.
2. Choose **Multiple Arduinos** if you have other Arduino devices, otherwise **Single Arduino**.
3. The DDU appears in the list. This can take a few seconds.
4. Open the **RGB Leds** tab, then **Profiles Manager → Import profile**, and pick one of the `.ledsprofile` files.

See the Quick Start Guide for screenshots of each step.

## Need help?

Message MacDat through your Etsy order page.
