# タスク管理ツール

- アプリURL：[ToDoApp](https://react-to-do-app-omega.vercel.app/)
- 参考記事：[Reactアプリ開発 入門 （基礎〜デプロイまで）](https://zenn.dev/777kkk/books/d4949816cf0c11)

## 作成目的
- Reactで開発を行いたかったため
- ちょっとした時に利用できるタスク管理ツールを作ってみたかったため

## 主な機能
- タスクの追加
- タスクの進捗を管理（残りタスク数のカウント）
- 完了したタスクの削除

## デプロイ環境
-  Vercel

## アプリの利用方法
### step1（アプリにアクセス）
- アプリにアクセスする

<img width="1263" alt="スクリーンショット 2023-01-30 9 16 06" src="https://user-images.githubusercontent.com/65697369/215364582-1f10326e-0891-4c8d-ac41-8bde7a2cfd0b.png">
（トップ画面）

### step2（タスクの追加）
- 入力フォームにタスクを入力する
- 入力フォーム右側の「＋ボタン」をクリックし、タスクを追加する

<img width="1263" alt="スクリーンショット 2023-01-30 9 16 31" src="https://user-images.githubusercontent.com/65697369/215364661-87a079cc-c0f8-4cbd-9d1c-7f2209eea29e.png">
（タスクを入力）

<img width="1263" alt="スクリーンショット 2023-01-30 9 16 44" src="https://user-images.githubusercontent.com/65697369/215364735-8766b523-8889-4c16-a6cb-76ed1e4f5747.png">
（タスクが追加されたことを確認）

### step3（進捗の入力）
- 完了したタスクについては、それをクリックする
- タスク左側のチェックボックスにチェックが入ることを確認する

<img width="1263" alt="スクリーンショット 2023-01-30 9 18 08" src="https://user-images.githubusercontent.com/65697369/215364857-fa280225-070f-40e6-a1c4-ab20abb4fa3d.png">


### step4（完了したタスクの削除）
- 完了したタスク（チェックボックスにチェックがついているもの）については、「＋ボタン」右側の「ゴミ箱ボタン」をクリックする

<img width="1263" alt="スクリーンショット 2023-01-30 9 18 17" src="https://user-images.githubusercontent.com/65697369/215365054-4b5501b6-f500-49d8-9e39-aacad91afbf2.png">


## コード利用時の注意点(ローカル)
- Font Awesomeの利用時：アカウントごとにKit Codeが異なるので、自分のものを`public/index.html`の\<head>内に指定してください。

## 今後の予定
- DBと連携したToDoアプリの開発

# Lisence
This project is licensed under the MIT License, see the LICENSE file for details
