
■ Day4 完全まとめ


■ やったこと

/api/players にアクセス
ブラウザでJSON確認
curl.exe で同じAPIを叩いた



■ 起きている流れ

curl → HTTPリクエスト送信
→ Laravel（Controller）
→ DB取得
→ JSONで返却



■ 重要ポイント

URL = 機能
/api/players = データ取得API
ブラウザもcurlも同じことをしている



■ HTTPの理解

通信 = ヘッダー + 本文
curl → 本文取得
curl -I → ヘッダーのみ



■ ステータスコード

200 → 成功
404 → URLミス
500 → サーバーエラー



■ ミスと理解

https は使えない（未設定）
http を使う必要がある



■ 到達状態

ブラウザを使わずにAPIへ直接アクセスできる