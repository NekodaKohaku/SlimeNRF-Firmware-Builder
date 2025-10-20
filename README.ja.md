<p align="right">
  言語:
  <a href="README.md">EN</a> |
  <a href="README.zh-TW.md">繁體中文</a> |
  <a href="README.ja.md">日本語</a>
</p>

# SlimeNRF-Firmware-Builder

**GitHub Actions** を使ってクラウド上で SlimeNRF のファームウェアをビルドします。ローカルのツールチェーンは不要です。
本プロジェクトは、ローカル環境で安定してビルドできないユーザー向けです。

## クイックスタート
1. このリポジトリを自分のアカウントへ **Fork** します。
2. Fork 先の **Actions** タブで、ワークフローを有効化します（必要な場合）。
3. **Build firmware** ワークフローを手動実行します。
4. 完了後、実行結果の **Releases** セクションからビルド済みファームウェアをダウンロードします。

## 設定可能なオプション
- **Clock (ICM)** —— ハードウェア／要件に合わせて IMU のクロック動作を調整。
- **Sleep (WOM)** —— 省電力化のために Wake-On-Motion を有効化／調整。
- **Pin mapping** —— ボード／バリアントに合わせてピン割り当てをカスタマイズ。

> これらのパラメータは、フォーク後にフォーク先の `.github/workflows/` 配下にあるワークフローファイルを編集して設定できます。

## 謝辞・由来（Acknowledgements & Provenance）
本プロジェクトは [Shine-Bright-Meow/SlimeNRF-Firmware-CI](https://github.com/Shine-Bright-Meow/SlimeNRF-Firmware-CI) を基に改変したものです。
上流プロジェクトの作者およびコントリビューターに感謝いたします。
