# golang + MySQLの開発環境
## できること
- goの実行
- goのビルド(開発中)
- MySQLとの連携
- 募集中...

## 使い方
1. ファイルを置く(下記参考)
1. maruを実行する
    - maruの引数
        - start : dockerコンテナの実行
        - stop : dockerコンテナの停止 = 終了
        - restart : stopしてstartします
        - clean : dockerコンテナの削除、ソースやライブラリは消えません。様子が変だったりしたら実行してください。
        - zura : ずら

## ファイル内容
- golang : Goのソースやライブラリを置く。
    - ./golang/src/work/main.goが実行されます。
- mysql : あらかじめ設定していきたいデータベースを置く。
    - SQLで置いてください。
    - アルファベット順に実行されるのでファイル名の一文字目を数字にしておくといいです。
- maru : 実行するとイメージとかいろいろが実行されます。
- README.md : これ
- docker/ : dockerのあれこれ(触らない)
- docker-compose.yml : docker-composeのあれこれ(触らない)

## 注意
MySQLのポートは3306、golangのポートは8080です。  
変更したい場合はdocker-compose.ymlの箇所を変更してください。  
