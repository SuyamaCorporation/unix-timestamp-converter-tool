# Unixタイムスタンプ 変換 ツール

Unixタイムスタンプと人間読み可能な日時を双方向に変換するツール。複数タイムゾーン表示・ミリ秒/秒切替に対応。

## 機能
- Unixタイムスタンプ(秒/ミリ秒切替)入力 → UTC・JST・US Eastern・US Pacificの4タイムゾーン表示
- 逆方向: datetime-local入力 → Unixタイムスタンプ(秒/ミリ秒)変換
- 「現在時刻」ボタンで即時入力
- 相対時刻表示（〇秒前/後、〇分前/後、〇日前/後）
- 各フィールドにワンクリックコピーボタン

## 技術
- Vanilla JS + Tailwind CSS CDN
- Intl.DateTimeFormat APIによるタイムゾーン変換
- localStorage不使用（ステートレス変換ツール）
