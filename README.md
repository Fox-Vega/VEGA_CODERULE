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
- **<object>_USE** — 使用するか
- **<object>_PIN** — ピン番号
- **<object>_REC** — 記録
- **<object>_MODE** — モード
- **<object>_UPDATEms** — 前回の更新
- **<object>_STARTms** — 開始時刻
- **<object>_ENDms** — 終了時刻
- **<object>_PREV** — 前回値
- **<object>_LIMIT** — 制限値
- **<object>_ZONE** — エリア・範囲
- **<object>_SET** — セット済みか
- **<object>_NUM** — センサー個数など

### 推奨
- **<object>_ANGLE** — 角度
- **<object>_REL_AZIMUTH** — 相対方位角（機体の中心から見た時、機体の正面を0とした0-360の角度）
- **<object>_REL_ANGLE** — 相対角（機体の中心から見た時、機体の正面を0とした-180-180の角度）
- **<object>_GLOBAL_AZIMUTH** — 絶対方位角（コートの中心から見た時、相手ゴールの中央を0とした0-360の角度）
