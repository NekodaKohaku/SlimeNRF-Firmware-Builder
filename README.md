<p align="right">
  Languages:
  <a href="README.md">EN</a> |
  <a href="README.zh-TW.md">繁體中文</a>
  <a href="README.ja.md">日本語</a>
</p>

# SlimeNRF-Firmware-Builder

Build SlimeNRF firmware in the cloud with **GitHub Actions** — no local toolchain required.
This repository is for users who cannot reliably build firmware on their own machines.

## Quick start
1. **Fork** this repository to your GitHub account.
2. Open the **Actions** tab in your fork and enable workflows if prompted.
3. Run the **Build firmware** workflow, choose the options you need, and start the run.
4. When it finishes, download the compiled firmware from the **Releases** section.

## Configurable options
- **Clock (ICM)** — adjust the IMU clock behavior to match your hardware/needs.  
- **Sleep (WOM)** — enable/adjust Wake-On-Motion for low-power behavior.  
- **Pin mapping** — customize pin assignments for your board/variant.

> You can pass these via workflow inputs (when you manually dispatch a run) or by editing the workflow file under `.github/workflows/` in your fork.

## Acknowledgements & Provenance
This project originated from [Shine-Bright-Meow/SlimeNRF-Firmware-CI](https://github.com/Shine-Bright-Meow/SlimeNRF-Firmware-CI).
It is now maintained independently and is not affiliated with or endorsed by the upstream project or its maintainers.
Huge thanks to the upstream authors and contributors.

*If your usage requires it, please also keep the original license/notice files from upstream.*
