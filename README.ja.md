<p align="right">
  言語:
  <a href="README.md">EN</a> |
  <a href="README.zh-TW.md">繁體中文</a> |
  <a href="README.ja.md">日本語</a>
</p>

# SlimeNRF-Firmware-Builder

ローカルのツールチェーンは不要。**GitHub Actions** を使ってクラウドで SlimeNRF のファームウェアをビルドします。
このリポジトリは、自分の環境でうまくビルドできないユーザーのためのビルダーです。

## クイックスタート
1. このリポジトリを自分のアカウントへ **Fork** します。
2. Fork 先の **Actions** タブを開き、ワークフローを有効化します（必要な場合）。
3. **Build firmware** ワークフローを手動実行し、必要な入力を設定して開始します。
4. 完了後、**Artifacts** から生成されたファームウェアをダウンロードします。

## 設定可能なオプション
- **Clock (ICM)** — IMU のクロック動作を調整。
- **Sleep (WOM)** — 低消費電力化のために Wake-On-Motion を有効化／調整。
- **Pin mapping** — ボード固有のピン割り当てをカスタマイズ。

> フォーク後、フォーク先の .github/workflows/ 配下にあるワークフローファイルを編集してこれらのパラメータを設定できます。

## 謝辞・由来（Acknowledgements & Provenance）
本プロジェクトは [Shine-Bright-Meow/SlimeNRF-Firmware-CI](https://github.com/Shine-Bright-Meow/SlimeNRF-Firmware-CI) に由来します。
