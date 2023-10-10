# 読書会

## 大西『論理学』

- 課題図書: [大西琢朗『論理学 (3STEPシリーズ)』(昭和堂、2021年)](https://www.amazon.co.jp/dp/4812221048)
- [解答解説・正誤表](https://sites.google.com/site/onishitakuro/writing/3step-logic)

- I部 計算と表現
  - [1章 古典命題論理(1)——論理式で計算する](<I部 計算と表現-1.1>)
  - [1章 古典命題論理(2)——推論の妥当性](<I部 計算と表現-1.2>)

## レジュメの作成・編集

1. 準備:
    1. GitHubのアカウントを作成し，SSHの鍵の生成・設定をして，自分の作ったアカウントに正常にcommit，pushができるか確認後，飯田(<flashingwind@gmail.com>)にそのメールアドレスを通知してください。このレポジトリへの権限を登録します。
    2. ローカル環境でプレビューしたい場合，適当なMarkdownエディター(VSCode+Markdow用拡張など)か，[docsify cli](https://github.com/docsifyjs/docsify-cli)を使う
    3. 少量の編集ならば，[レポジトリーをブラウザーで開いて](https://github.com/philomath-club/ohnishi-ronrigaku)，ファイルを選択ペンアイコンで編集。または「Add file」で新規作成する。
3. ドキュメントを保存しておきたい場所でターミナル(コマンドプロンプト)を開く
4. (初回のみ)クローン

    ```bash
    git clone git@github.com:philomath-club/ohnishi-ronrigaku.git
    cd ohnishi-ronrigaku
    ```

5. (2回目以降)最新の状態をプル。4の操作後のフォルダー(ohnishi-ronrigaku)で，

    ```bash
    cd ohnishi-ronrigaku
    git pull
    ```

2. 4の操作後のフォルダー(ohnishi-ronrigaku)で，Markdown形式で，ファイルを作成・編集

    ```bash
    code . #VSCodeの場合
    ```

3. コミット，GitHubへプッシュ。4の操作後のフォルダー(ohnishi-ronrigaku)で，

    ```bash
    git add .
    git commit -m "I部1章追加"
    git push
    ```

    -mに渡す内容は編集内容に合わせて変更してください。
