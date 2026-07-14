[README.md](https://github.com/user-attachments/files/29998347/README.md)
# JAL 御翔印 集印地図

JALグループの御翔印(空港版御朱印)取扱空港を日本地図上に表示し、訪問済みの空港をチェック☑できるWebアプリです。

## 機能

- 全55空港を日本地図上に空港名つきでプロット(奄美・沖縄はインセット表示)
- 地図上のマーク、または地域別チェックリストをタップして押印チェック
- 押印済み空港は朱印風マークに変化、全体・地域別の進捗を表示
- チェック状態はブラウザの localStorage に自動保存
- 依存ライブラリなしの単一 HTML ファイル(index.html)

## 使い方

ブラウザで `index.html` を開くだけで動作します。GitHub Pages で公開する場合:

1. このリポジトリの **Settings → Pages** を開く
2. Source を「Deploy from a branch」、Branch を `main` / `(root)` に設定して Save
3. 数分後に `https://<ユーザー名>.github.io/<リポジトリ名>/` で公開されます

## 注意事項

収録空港はJALグループ国内就航空港に基づく参考リストです。御翔印の取扱空港・デザインは変更されることがあるため、最新情報はJAL公式サイトの御翔印ページでご確認ください。

空港の追加・削除は `index.html` 内の `REGIONS` 配列を編集してください。

## License

MIT
