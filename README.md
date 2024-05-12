# これは何？

alps-asd でアプリケーション状態の遷移図を書き出すディレクトリ

# alps-asd とは

アプリケーションの状態遷移と行動を可視化するツール
状態間の遷移や可能なアクションを直感的に捉えることができる

公式ドキュメント
https://alps-asd.github.io/manuals/1.0/ja/index.html

# 環境構築

事前準備

- Docker がインストールされている

環境構築

- リポジトリをクローン
- asd コマンドをインストールする
  - `curl -L https://alps-asd.github.io/app-state-diagram/asd.sh > ./asd && chmod +x ./asd && sudo mv ./asd /usr/local/bin`
- ASD で表示する
  - `asd --watch ./profile.xml`
