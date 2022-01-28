2022/1/28 更新
# CaseClosed-Database
[名探偵コナン編纂室](https://websunday.net/conandb/)のページからBeautifulSoupを使って登場キャラなどのデータを取得するコード(python)※画像を除く
Windows11にて動作確認済

# 利用に関する注意
私的利用に限ります。(スクレイピングの勉強、Pythonの勉強、個人的な名探偵コナンに関する考察に使うなど)
著作権等は以下のサイトで確認してください。

[画像使用・著作権 | 小学館](https://www.shogakukan.co.jp/picture)

# 使い方

・pythonをインストールする

・このレポジトリをgit cloneするもしくはzipファイルをダウンロードして解凍

・BeautifulSoupなど未インストールのパッケージがあればそれもインストールする

・このレポジトリのルートディレクトリでConanData.pyを実行

```sh
python ConanData.py
```

出来上がったデータセットがConanData.jsonです。

また、ConanData.jsonから作成したcsvデータがdataset_csvにあります。

# FileTitle.py

各話の通算話数、掲載巻数、File番号、事件名、タイトルのデータセットVolume-Index-Case-Title.csvを取得できます。

# Case.py

各事件の通算事件数、事件数、説明文が読めるNumber-Title-Explain.csvが取得できます。

# MainCharacter.py GuestCharacter.py

編纂室においての事件ごとのメインキャラ、ゲストキャラの一覧表である
Title-MainCharacter.csvとTitle-GuestCharacter.csvが取得できます。

# Place.py

事件が起こった場所のデータセットTitle-Place.csvが取得できます。
