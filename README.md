# VEGA Coding Rules

VEGA プロジェクトで使用する **動詞ルール（関数名）** と  
**変数・定数の命名規則** をまとめたガイドライン。

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
- **USE_name** — 使用する対象
- **name_PIN** — ピン番号
- **REC_name** — 受信データ
- **name_MODE** — モード
- **LAST_name** — 最後の時刻（timestamp）
- **name_START** — 開始時刻
- **name_END** — 終了時刻
- **PREV_name** — 前回値
- **name_LIMIT** — 制限値
- **name_ZONE** — エリア・範囲
- **name_SET** — セット済みかどうか（boolean）
- **name_NUM** — 数値カウンタ

### 推奨
- **name_deg** — 角度（度）
- **name_azimuth** — 方位角（北基準の角度）
