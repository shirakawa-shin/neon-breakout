# NEON BREAKOUT

ブラウザで遊べるネオン風ブロック崩し。HTML 1 ファイル・外部ライブラリなし・効果音も WebAudio で生成しています。

## 遊び方

| 操作 | キー |
| --- | --- |
| パドル移動 | ← → / A D / マウス / タッチ |
| 発射・決定 | Space / Enter / クリック |
| 一時停止 | P / Esc |
| ミュート | M |

- 全 5 ステージ。クリアすると難易度を上げて 2 周目へ
- 連続でブロックを壊すとコンボ倍率（最大 ×10）
- 灰色のブロックは壊せません

### パワーアップ

| アイコン | 効果 |
| --- | --- |
| ×3 | マルチボール |
| ↔ | パドル拡大 |
| S | スローボール |
| ⚡ | レーザー自動発射 |
| ♥ | 残機 +1 |

## GitHub Pages で公開する

1. このリポジトリを GitHub に push
2. **Settings → Pages → Build and deployment** で Source を `Deploy from a branch`、Branch を `main` / `/ (root)` にして Save
3. 数十秒後に `https://<ユーザー名>.github.io/<リポジトリ名>/` で遊べます

ローカルで遊ぶだけなら `index.html` をブラウザで開くだけで OK です。
