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
- **object_USE** — 使用するか
- **object_PIN** — ピン番号
- **object_REC** — 記録
- **object_MODE** — モード
- **object_UPDATEms** — 前回の更新
- **object_STARTms** — 開始時間
- **object_ENDms** — 終了時間
- **object_VALUE** — 数値
- **object_PREV** — 前回値
- **object_LIMIT** — 制限値
- **object_ZONE** — エリア・範囲
- **object_SET** — セット済みか
- **object_NUM** — センサー個数など
- **object_SPEED** — 速度

### 推奨
- **object_ANGLE** — 角度
- **object_REL_AZIMUTH** — 相対方位角（機体の中心から見た時、機体の正面を0とした0-360の角度）
- **object_REL_LINE_AZIMUTH** — 相対方位角（機体の中心から見た時、白線に対する垂線と白線との交点を0とした0-360の角度）
- **object_REL_ANGLE** — 相対角（機体の中心から見た時、機体の前面を0とした-180-180または0-180の角度）
- **object_REL_REAR_ANGLE** — 相対角（機体の中心から見た時、機体の後面を0とした-180-180または0-180の角度）
- **object_GLOBAL_AZIMUTH** — 絶対方位角（コートの中心から見た時、相手ゴールの中央を0とした0-360の角度）
