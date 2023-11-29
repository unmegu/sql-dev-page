# pages-practice.github.io
github pages練習用のリポジトリ

## 記事を投稿する方向け導入方法
### 大まかな流れ
1. 自分のローカルに今後作業をしていくディレクトリの作成
2. 1で作成したディレクトリにリモートのリポジトリ（今閲覧しているリポジトリ）をローカル環境に複製する(clone)

### 詳細な手順
1. ターミナルを開いて任意の場所にディレクトリを作成します
    このフォルダがリモートにすでにあるリポジトリ（今閲覧しているリポジトリ）をローカル環境に複製する場所になります．
    <!-- 以下の画像の場合，`work`フォルダの下に`sample-pages`フォルダを作成していることになります -->
    作業ディレクトリに`cd`コマンドなどで移動したのちに，以下の`mkdir`コマンドで新規ディレクトリを作成してください．
    （`$`はコマンドではないので入力しないでください）
    
    `$ mkdir <任意のディレクトリ名>`

    実際の記入例 

    `WorkSpace`というディレクトリの下に任意のディレクトリ`sample-pages`を作成しています
    ![mkdir_image](images/mkdir_image.png)

    GUIから操作することも可能ですが，この後の手順でCUIを使うことになるためCUIで操作しましょう．

2. 1で作成した作業ディレクトリに移動します

    `$ cd <1で作成した作業ディレクトリ名>`
    実際の記入例

    1で作成した`sample-pages`ディレクトリに移動しています
    ![test_image](images/cd_image.png)

3. ブラウザでGithubの[コチラ](https://github.com/KZ0219A/gemba_dev_tutorial)のリポジトリにアクセスしてください
<!-- 今は仮でsawadaさんのリポジトリに飛ぶようになっています -->

4. アクセスしたリポジトリの下の図の緑色の`<>Code`という部分をクリックしてHTTPもしくはSSHのボタンをクリックし，コピーしてください
 ![test_image](images/github_image.png)

5. ターミナルの画面に戻り，以下のコマンドを入力します．

`git@github.com:KZ0219A/gemba_dev_tutorial.git`の部分は，4でコピーしたものです
<!-- 今は仮でsawadaさんのリポジトリをcloneしています -->
`$ git clone git@github.com:KZ0219A/gemba_dev_tutorial.git`

実際に入力した図

だいたい下図のように`done`という形で終わっていれば成功です
 ![clone_image](images/clone_image.png)

 6. 確認のために`cd`今クローンしたリポジトリに移動して,中にあるファイルやフォルダを確認してみてください

 `$ cd gemba_dev_tutorial`
 
 `$ ls`

  ![ls_image](images/ls_image.png)

導入までの手順は以上になります．
