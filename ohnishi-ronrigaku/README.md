# 読書会

## 大西『論理学』

- 課題図書: [大西琢朗『論理学 (3STEPシリーズ)』(昭和堂、2021年)](https://www.amazon.co.jp/dp/4812221048)
- [解答解説・正誤表](https://sites.google.com/site/onishitakuro/writing/3step-logic)

- I部 計算と表現
  - [1章 古典命題論理(1)——論理式で計算する](<I部 計算と表現-1>)
  - [1章 古典命題論理(2)——推論の妥当性](<I部 計算と表現-2>)

## レジュメの作成・編集

1. 準備:
  1. GitHubのアカウントを作成し，SSHキーの設定をして，自分の作ったアカウントに正常にcommit，pushができるか確認後，飯田(<flashingwind@gmail.com>)にそのメールアドレスを通知してください。このレポジトリへの権限を登録します。
  2. ローカル環境でプレビューしたい場合，適当なMarkdownエディター(VSCode+Markdow用拡張など)か，(docsify cli)[https://github.com/docsifyjs/docsify-cli]を使う
3. ドキュメントを保存しておきたい場所でターミナル(コマンドプロンプト)を開く
4. クローン(初回)

    ```bash
    git clone git@github.com:philomath-club/ohnishi-ronrigaku.git
    cd ohnishi-ronrigaku
    ```

    ```bash
    git clone https://github.com/philomath-club/ohnishi-ronrigaku.git
    cd ohnishi-ronrigaku
    ```

5. 最新の状態をプル(2回目以降)。4の操作後のフォルダー(ohnishi-ronrigaku)で，

    ```bash
    git pull
    ```

2. 4の操作後のフォルダー(ohnishi-ronrigaku)で，Markdown形式で，ファイルを作成・編集
3. コミット，GitHubへプッシュ。4の操作後のフォルダー(ohnishi-ronrigaku)で，

    ```
    git add .
    git commit -m "I部1章追加"
    git push
    ```

    -mに渡す内容は編集内容に合わせて変更してください。
