# Pr Export Notify

Premiere Pro の書き出し・レンダリング完了を通知音でお知らせする、軽量な macOS メニューバーアプリです。

*A lightweight macOS menu bar app that plays a notification sound when Adobe Premiere Pro finishes exporting / rendering.*

**🇯🇵 [日本語](#日本語) ・ 🇬🇧 [English](#english)**

### ⬇️ ダウンロード / Download

**[最新版をダウンロード / Download the latest release](https://github.com/gcalgcal/PrExportNotify/releases/latest)**

[Releases](https://github.com/gcalgcal/PrExportNotify/releases/latest) ページの `PrExportNotify.dmg` をダウンロードして開き、`PrExportNotify` フォルダを `Applications` にドラッグしてください。
Download `PrExportNotify.dmg` from the [Releases](https://github.com/gcalgcal/PrExportNotify/releases/latest) page, open it, and drag the `PrExportNotify` folder into `Applications`.

---
## English

### Features

- 📤 Automatically detects when Premiere Pro finishes exporting / rendering / encoding
- 🔔 Plays a notification sound on completion (10 languages supported)
- 🎵 Supports custom notification sounds (place `alert.wav` in the same folder)
- 🚀 Launch at login (macOS 13 or later)
- 🪶 Lightweight menu bar app (does not appear in the Dock)

### Requirements

- macOS 11 (Big Sur) or later
- Adobe Premiere Pro
- Accessibility permission (required for window detection)

### Installation

1. Download and open `PrExportNotify.dmg`
2. Drag the `PrExportNotify` folder into `Applications`
   (moving the whole folder keeps the app and `alert.wav` together)
3. Launch `Applications/PrExportNotify/PrExportNotify.app`
   (notarized, so it opens without warnings)
4. Allow PrExportNotify in **System Settings → Privacy & Security → Accessibility**

### Usage

Click the bell icon in the menu bar to open the menu.

| Item | Description |
|------|-------------|
| Monitoring | Toggle monitoring ON / OFF |
| Launch at Login | Auto-start at login (macOS 13+) |
| Test Sound | Play the notification sound |
| Quit | Quit the app |

### Custom Sound

A default notification sound is bundled inside the app, so it works out of the box.
To change it, replace the [`alert.wav`](alert.wav) file next to the app with your own
WAV file (keep the filename `alert.wav`).

---
## 日本語

### 特長

- 📤 Premiere Pro の書き出し・レンダリング・エンコードの完了を自動検出
- 🔔 完了時に通知音を再生（10言語対応）
- 🎵 カスタム通知音に対応（`alert.wav` を同じフォルダに配置）
- 🚀 ログイン時に自動起動（macOS 13 以降）
- 🪶 メニューバー常駐型・軽量（Dock に表示されません）

### 動作環境

- macOS 11 (Big Sur) 以降
- Adobe Premiere Pro
- アクセシビリティ権限（ウィンドウ検出のため）

### インストール

1. `PrExportNotify.dmg` をダウンロードして開く
2. 表示された `PrExportNotify` フォルダを `Applications` にドラッグ
   （フォルダごと移動すると、アプリと `alert.wav` が一緒に入ります）
3. `Applications/PrExportNotify/PrExportNotify.app` をダブルクリックで起動
   （公証済みのため警告なしで開けます）
4. **システム設定 → プライバシーとセキュリティ → アクセシビリティ** で PrExportNotify を許可

### 使い方

メニューバーのベルアイコンをクリックするとメニューが開きます。

| 項目 | 説明 |
|------|------|
| 監視中 | 監視の ON / OFF |
| ログイン時に起動 | ログイン時の自動起動（macOS 13 以降） |
| テスト再生 | 通知音をテスト再生 |
| 終了 | アプリを終了 |

詳しい使い方は [README_JP.rtf](README_JP.rtf) を参照してください。

### カスタム通知音

デフォルトの通知音はアプリに組み込まれているため、そのままでも音が鳴ります。
通知音を変えたい場合は、アプリと同じフォルダにある [`alert.wav`](alert.wav) を
お好きな WAV ファイルに置き換えてください（ファイル名は `alert.wav` のまま）。

---

## License

[MIT License](LICENSE)

## Support

[@kowaza on X](https://x.com/kowaza)
