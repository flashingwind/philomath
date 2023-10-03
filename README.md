# 読書会

## 大西『論理学』

- I部 計算と表現
  - [1章 古典命題論理(1)——論理式で計算する](</ohnishi-ronrigaku/I部 計算と表現-1>)
  - [1章 古典命題論理(2)——推論の妥当性](</ohnishi-ronrigaku/I部 計算と表現-2>)

## レジュメの作成・編集

0. GitHubのアカウントを作成し，SSHキーの設定をして，自分の作ったアカウントに正常にcommit，pushができるか確認後，飯田(<flashingwind@gmail.com>)にそのメールアドレスを通知してください。このレポジトリへの権限を登録します。
1. 適当な場所でターミナル(コマンドプロンプト)を開く
2. クローン(初回)

    ```bash
    git clone git@github.com:philomath-club/ohnishi-ronrigaku.git
    cd ohnishi-ronrigaku
    ```

    ```bash
    git clone https://github.com/philomath-club/ohnishi-ronrigaku.git
    cd ohnishi-ronrigaku
    ```

3. 最新の状態をプル(2回目以降)

    ```bash
    git pull
    ```

2. Markdown形式で，ファイルを作成・編集
3. コミット，GitHubへプッシュ

    ```
    git add .
    git commit -m "I部1章追加(例)"
    git push
    ```
