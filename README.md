# VEGA CodeRule

VEGA プロジェクトで使用する **動詞ルール（関数名）** と **変数・定数の命名規則** をまとめたガイドライン。

---

## 1. 動詞ルール（関数・処理名）

- **run** — パーツを動かす（モーター・サーボなど）
- **read** — センサー値・メッセージを読む
- **get** — 状態・値を取得する
- **fetch** — read と get の両方（読み取り＋取得）
- **set** — モードや設定値をセットする

---

## 2. 命名規則（変数・定数）

### 基本形式
- **name_USE** — 使用するか
- **name_PIN** — ピン番号
- **name_REC** — 記録
- **name_MODE** — モード
- **name_UPDATE_ms** — 前回の更新
- **name_START_ms** — 開始時刻
- **name_END_ms** — 終了時刻
- **name_PREV** — 前回値
- **name_LIMIT** — 制限値
- **name_ZONE** — エリア・範囲
- **name_SET** — セット済みか
- **name_NUM** — センサー個数など

### 推奨
- **name_DEG** — 角度（度）
- **name_AZIMUTH** — 方位角（機体正面を基点とした0-360の角度）
- **name_RELATIVE_AZIMUTH** — 相対角（機体正面を基点とした-180-180の角度）
- **name_WORLD_AZIMTUH** — 方位角（相手ゴールを基点とした0-360の角度）
