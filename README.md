# Pr Export Notify

Premiere Pro の書き出し・レンダリング完了を通知音でお知らせする、軽量な macOS メニューバーアプリです。

*A lightweight macOS menu bar app that plays a notification sound when Adobe Premiere Pro finishes exporting / rendering.*

**🇯🇵 [日本語](#日本語) ・ 🇬🇧 [English](#english)**

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

1. `PrExportNotify.app` をアプリケーションフォルダ等にコピー
2. ダブルクリックで起動（公証済みのため警告なしで開けます）
3. **システム設定 → プライバシーとセキュリティ → アクセシビリティ** で PrExportNotify を許可

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

アプリと同じフォルダに `alert.wav` を配置すると、その音が通知音として使われます。
配置しない場合はシステムサウンド「Glass」が再生されます。
サンプル音 [`alert_sample.wav`](alert_sample.wav) を `alert.wav` にリネームして利用できます。

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

1. Copy `PrExportNotify.app` to your Applications folder
2. Double-click to launch (notarized, so it opens without warnings)
3. Allow PrExportNotify in **System Settings → Privacy & Security → Accessibility**

### Usage

Click the bell icon in the menu bar to open the menu.

| Item | Description |
|------|-------------|
| Monitoring | Toggle monitoring ON / OFF |
| Launch at Login | Auto-start at login (macOS 13+) |
| Test Sound | Play the notification sound |
| Quit | Quit the app |

### Custom Sound

Place an `alert.wav` file in the same folder as the app to use it as the notification sound.
If absent, the system sound "Glass" is played instead.
You can rename the bundled [`alert_sample.wav`](alert_sample.wav) to `alert.wav` to use it.

---

## License

[MIT License](LICENSE)

## Support

[@kowaza on X](https://x.com/kowaza)
