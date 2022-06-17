# VueJsTrial

### node.jsインストール
#### Visual Studioでビルド時にエラーが発生する場合の対処法
~~~
- npm   エラー msb3073 npm run build コード 9009
~~~
- プロジェクトのnpmをインストール、更新を行う
- それでも、解消されない場合、環境変数の設定が原因
~~~
エラー msb3073 npm run build コード 9009
~~~
- PC、プロパティ、詳細設定タブ、環境変数、PATHの最後に「;C:\Program Files\nodejs\」追加
- コマンドプロンプト再起動し、npmコマンドを実行
