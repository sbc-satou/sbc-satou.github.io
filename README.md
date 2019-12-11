## 概要
[draw.io](https://www.draw.io)をAlibaba Cloudに対応させたものです。  

## ライセンス
本ツールは[draw.io](https://github.com/jgraph/drawio)を元に作成されています。  
ライセンスは[Apache License2.0](http://www.apache.org/licenses/LICENSE-2.0)に準拠します。

## 使い方
1. ブラウザで[index.html](https://sbc-satou.github.io/drawio/src/main/webapp/index.html)にアクセスします。
2. 既存のダイアグラムを開くか否かを聞かれるので、`Create New Diagram`（新規作成）を選択します。
<img width="311" alt="新規作成" src="https://user-images.githubusercontent.com/28669526/70611403-7c7cd400-1c48-11ea-8dcb-aea0a2aa6824.png">

3. テンプレート選択画面にて、`Cloud`カテゴリより任意のAlibaba Cloudテンプレート（`cloud/aliyun_xxx.xml`）を選択し、`Create`ボタンを押下します。  
※空のテンプレートから作成する場合でも、`blankDiagram`ではなく`cloud/aliyun_blank_template.xml`を選択してください。
<img width="518" alt="テンプレート選択" src="https://user-images.githubusercontent.com/28669526/70611553-b948cb00-1c48-11ea-93b8-670b48ad3043.png">

4. 左メニューにAlibaba Cloudのアイコンが表示されるため、Let's draw!!
<img width="1209" alt="Let's draw!!" src="https://user-images.githubusercontent.com/28669526/70611615-cfef2200-1c48-11ea-91e4-9dd0dd9b7f94.png">

## 注意点
- Webサイトの公開に際しては、`Github`の`Github Pages`機能を用いてホスティングしています。  
そのため、オンライン機能（Google Drive連携/Github連携等）を制限しています。
- 上記手順でAlibaba Cloudのテンプレート指定した場合にのみ、Alibaba CloudのShapes（アイコン集）が表示されます。  
他のテンプレートを指定した場合や、`＋More Shapes`からはAlibaba CloudのShapesを読み込むことは出来ません。
- 本ツールは予告なく仕様変更、または公開を終了する可能性があります。

## 参考
- 元のソース（draw.io）:https://github.com/jgraph/drawio
- icon素材：https://www.iconfont.cn/plus/user/detail?&uid=41718
- 参考サイト：https://qiita.com/ohiro18/items/02c5da6d6590dfe3ed0d
