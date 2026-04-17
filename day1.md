■ Day1：HTTPを見る（完全まとめ）


■ ① Webの正体

Webページは

👉 HTML（コード）でできている



■ ② 通信の流れ

① ブラウザ
→ URLに対して GETリクエスト を送る

② サーバー
→ HTML（レスポンス）を返す

③ ブラウザ
→ HTMLを解釈して画面に表示



■ ③ Networkタブで見たもの

■ Name
→ 何を取りに行ったか（HTML / 画像 / JS）

■ Status
→ 結果

・200 → 新しく取得
・304 → 変更なし（キャッシュ使用）


■ Type
→ 種類

・document → HTML（ページ本体）
・script → JS
・img → 画像

■ Time（ms）
→ 通信時間



■ ④ Headersで見たもの

Request URL
👉 どこにアクセスしたか

Request Method
👉 GET（取得）

Status Code
👉 結果（200 / 304）



■ ⑤ ResponseとPreview

Response
👉 サーバーから返ってきたHTML（コード）

Preview
👉 HTMLを表示した見た目



■ ⑥ キャッシュの理解（重要）

・1回目 → 200 → データ取得
・2回目 → 304 → データ取得しない

👉 前に保存したデータを使う



■ ⑦ 本質

👉 Web = リクエストとレスポンス



■ 一言

👉 「ブラウザは裏で通信している」