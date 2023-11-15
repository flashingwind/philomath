# 読書会

## 大西『論理学』参加者向け

- 課題図書: [大西琢朗『論理学 (3STEP シリーズ)』(昭和堂、2021 年)](https://www.amazon.co.jp/dp/4812221048)

- I部 計算と表現
  - [1章 古典命題論理(1)——論理式で計算する](<I-1-古典命題論理(1)——論理式で計算する>)
  - [2章 古典命題論理(2)——推論の妥当性](<I-2-古典命題論理(2)——推論の妥当性>)
  - [3章 様相論理(1)——可能世界意味論](<I-3-様相論理(1)——可能世界意味論>)
  - [4章 様相論理(2)——対応理論](<I-4-様相論理(2)——対応理論>)

- 著者による[解答解説・正誤表](https://sites.google.com/site/onishitakuro/writing/3step-logic)

## レジュメの作成・編集

### 準備

1. GitHub のアカウントを作成し，SSH の鍵の生成とGitHubへの登録をして，自分の作ったアカウントで正常に commit，push ができるか確認後，飯田(<flashingwind@gmail.com>)にそのメールアドレスを通知してください。このレポジトリへの権限を登録します。
1. ローカル環境でプレビューしたい場合，適当な Markdown エディター(VSCode+Markdow 用拡張など)か，[docsify cli](https://github.com/docsifyjs/docsify-cli)を使う

### ブラウザーで編集する場合

1. 少量の編集ならば，[この画面](https://github.com/philomath-club/ohnishi-ronrigaku)の上の方から対象のファイルをを見つけて開き，ペンアイコンで編集。または`Add file`→`Create new file`で新規作成する。
2. `Commit changes…`により保存する(コメントはデフォルトのままでもかまいません)。

### PCで編集する場合

1. ドキュメントを保存しておきたい場所でターミナル(コマンドプロンプト)を開く
2. (初回のみ)クローン

   ```bash
   git clone git@github.com:philomath-club/ohnishi-ronrigaku.git
   cd ohnishi-ronrigaku
   ```

3. (2回目以降)最新の状態をプル。4 の操作後のフォルダー(ohnishi-ronrigaku)で，

   ```bash
   cd ohnishi-ronrigaku
   git pull
   ```

4. Markdown 形式で，ファイルを作成・編集: ohnishi-ronrigakuフォルダーで，VSCode起動。左のファイルリストから適当な過去の.mdファイルを開き，別名保存してテンプレートとしてください。

   ```bash
   code . #VSCodeの場合
   ```

5. 終わったらコミット，GitHub へプッシュ: 4 の操作後のフォルダー(ohnishi-ronrigaku)で，

   ```bash
   git add .
   git commit -m "I部1章追加"
   git push
   ```

   -m に渡す内容(コメント部分)は編集内容に合わせて変更してください。

### 連絡先

技術的な面の管理者: 飯田(<flashingwind@gmail.com>)
