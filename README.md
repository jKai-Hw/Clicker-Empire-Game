# Clicker-Empire-Game

# chat-app
オンラインで相手を探してメッセージのやり取りができるSPAアプリです。
Vue.jsの学習のアウトプットとして作成しました。

## Technologies
- JavaScript
- Bootstrap
- Font Awesome
- Google fonts

## URL
https://jkai-hw.github.io/Clicker-Empire-Game/

## Description
初めて、外部APIとの非同期通信、モジュールやルーティング、状態管理のライブラリを使用して作成したアプリケーションです。
主に公式ドキュメントを読みながら、課題の手順に沿って作成しました。

メッセージデータの取り扱いは、Messageオブジェクトを作成しそれを連想配列に格納しました。特定のデータへのアクセスの計算量少なくし、簡単にアクセスできるよう注意しました。
また、日時のデータをMessageオブジェクトに含めることによって、Talk履歴を新しい順に表示できるようにしました。

getterやsetterを用いたVuexの状態管理で堅牢に管理できるようにもしました。

レスポンシブにも対応しております。DevToolsでご覧になる際は、対象のサイズ表示にしてから一度リロードしてご覧ください。

![Gif](https://user-images.githubusercontent.com/75964449/207264299-559d30e5-2f3f-4eef-bb85-f417d19ce724.gif)

