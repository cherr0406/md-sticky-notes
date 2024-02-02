# MD Sticky Notes

## About

tauriを使ってMarkdown記法が使える付箋アプリを作ってみる

## Development

package manager: bun

Tauri + NextJS

### Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode) + [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)

## Development Tasks

1. 基本機能の整備
    1. ウィンドウの表示
       - [x] ウィンドウの表示
       - [x] ウィンドウから新規メモウィンドウを開く
       - [ ] 起動時にメモウィンドウから開始する
       - [ ] メインウィンドウ（メモ一覧）を表示する
    2. Markdown記法を有効にする
       - [ ] Markdown記法をメモに反映する
       - [ ] リアルタイムでプレビュー化する
       - [ ] 改行時に自動でインデントやリストを挿入する
       - [ ] カスタムCSSで見た目を変更できるようにする
    3. メモを保存できるようにする
2. デザインの整備
    1. メモウィンドウのデザイン
    2. メインウィンドウのデザイン
3. データベースの整備
    1. メモの保存
    2. メモの読み込み
    3. メモの削除
    4. メモの編集
