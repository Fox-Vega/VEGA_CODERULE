# VEGA CodeRule

---

## 1. 関数の命名規則

- **run** — パーツを動かす（モーター・サーボなど）
- **read** — センサー値・メッセージを読む
- **get** — 状態・値を取得する
- **fetch** — read と get の両方（読み取り＋取得）
- **set** — モードや設定値をセットする

---

## 2. 変数・定数・引数の命名規則（tag）

### 基本形式
- **object_USE** — 使用するか
- **object_PIN** — ピン番号
- **object_REC** — 記録
- **object_MODE** — モード
- **object_UPDATEms** — 前回の更新
- **object_STARTms** — 開始時間
- **object_ENDms** — 終了時間
- **object_DURATIONms** — 持続時間
- **object_START** — 開始位置
- **object_END** — 終了位置
- **object_VALUE** — 数値
- **object_PREV** — 前回値
- **object_LIMIT** — 制限値
- **object_ZONE** — （片側の）エリア・範囲
- **object_SIZE** — 大きさ
- **object_SET** — セットフラグ
- **object_NUM** — 個数・番号
- **object_SPEED** — 速度
- **object_BRIGHTNESS** — 明るさ
- **object_COLOR** — 色
- **object_RADIUS** — 半径
- **object_DIAMETER** — 直径
- **object_ANGLE** — 角度
- **object_REL_AZIMUTH** — 相対方位角（機体の中心から見た時、機体の正面を0とした0-360の角度）
- **object_REL_MOTOR_AZIMUTH** — 相対方位角（機体の中心から見た時、モーター軸を0とした0-360の角度）
- **object_REL_LINE_AZIMUTH** — 相対方位角（機体の中心から見た時、白線に対する垂線と白線との交点を0とした0-360の角度）
- **object_REL_ANGLE** — 相対角（機体の中心から見た時、機体の前面を0とした-180-180または0-180の角度）
- **object_REL_REAR_ANGLE** — 相対角（機体の中心から見た時、機体の後面を0とした-180-180または0-180の角度）
- **object_GLOBAL_AZIMUTH** — 絶対方位角（コートの中心から見た時、相手ゴールの中央を0とした0-360の角度）

- **object_tag_** — 仮
