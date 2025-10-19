<p align="right">
  語言：
  <a href="README.md">EN</a> |
  <a href="README.zh-TW.md">繁體中文</a> |
  <a href="README.ja.md">日本語</a>
</p>

# SlimeNRF-Firmware-Builder

透過 **GitHub Actions** 在雲端建構 SlimeNRF 固件，無需本機工具鍊。
本專案給無法在自己電腦上可靠編譯的人使用。

## 快速開始
1. 將此倉庫 **Fork** 到你的 GitHub 帳號。
2. 在 Fork 的 **Actions** 分頁啟用工作流程（若有提示）。
3. 手動執行 **Build firmware** 工作流程。
4. 完成後，於執行紀錄的 **Releases** 區塊下載編譯好的韌體。

## 可調整項目
- **Clock (ICM)** —— 調整 IMU 時脈行為以符合你的硬體與需求。
- **Sleep (WOM)** —— 啟用／調整 Wake-On-Motion 以降低功耗。
- **Pin mapping** —— 自訂板子／變體的針腳配置。

> 以上參數可在 Fork 後編輯 .github/workflows/ 內的工作流程檔設定。

## 致謝與來源（Acknowledgements & Provenance）
本專案起源自 [Shine-Bright-Meow/SlimeNRF-Firmware-CI](https://github.com/Shine-Bright-Meow/SlimeNRF-Firmware-CI)。
特此致謝所有上游作者與貢獻者。
