# MacDat Etsy Software

Companion software and configuration files for MacDat products sold on Etsy.

Find your product below and follow the instructions in its folder.

| Product | Folder | Downloads |
|---|---|---|
| Flag Box | [flag-box](flag-box/) | [Releases](https://github.com/macdat-git/etsy-software/releases?q=flag-box) |
| 4 inch DDU | [ddu-4inch](ddu-4inch/) | [Releases](https://github.com/macdat-git/etsy-software/releases?q=ddu-4inch) |
| 5 inch DDU | [ddu-5inch](ddu-5inch/) | [Releases](https://github.com/macdat-git/etsy-software/releases?q=ddu-5inch) |
| 7.8 inch DDU | [ddu-7.8inch](ddu-7.8inch/) | [Releases](https://github.com/macdat-git/etsy-software/releases?q=ddu-7.8inch) |
| 7.8 inch DDU with LEDs | [ddu-7.8inch-leds](ddu-7.8inch-leds/) | [Releases](https://github.com/macdat-git/etsy-software/releases?q=ddu-7.8inch-leds) |

## Downloading

1. Open your product's folder above.
2. Click the **Releases** link and download the latest `.zip` under **Assets**.
3. Follow the install steps in the product's folder.

## Need help?

Message MacDat through your Etsy order page.

---

## Maintainer notes

- Each product has its own folder. Keep source files, configs, and install docs there.
- Release tags are prefixed with the folder name so each product's releases can be filtered, e.g. `flag-box-v1.0.0`, `ddu-5inch-v1.2.0`.
- Publish a release with the GitHub CLI:

  ```powershell
  gh release create flag-box-v1.0.0 .\dist\flag-box-v1.0.0.zip --title "Flag Box v1.0.0" --notes "Initial release"
  ```
