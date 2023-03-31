# データエンジニアリング(DE)基礎（工学部）

信州大学「データエンジニアリング(DE)基礎（工学部）」 教材リポジトリ

## eALPSコース

学部・研究科共通 > データエンジニアリング(DE)基礎(T) ※年度で更新されない場所で設置してある

* https://lms.ealps.shinshu-u.ac.jp/common/course/view.php?id=147


## 教材形式

* Google colab版: 直接colab環境で実行できる形式（変更したければ個々人のGoogleドライブへコピーが必要）
* Jupyter Notebook版: ローカルでipynbを実行するためのファイル一式 ZIPで固める
* PDF版: Jupyter Notebook版からのPDFエクスポート (PDF)
* HTML版: Jupyter Notebook版(Slide指定あり）からのReveal.js slides版をエクスポート (HTML)

## GitHubからeALPSへのデプロイ方法

1. 基本的に，Google colab版をmasterとしてから，Jupyter Notebook版としてコピー後 調整する． (.ipynb)
2. Jupyter Notebook : Slide指定でRISEの動作を確認後， Reveal.js slides版をエクスポートする． (.html)
3. Jupyter Notebook : 印刷プレビュー経由でPDF保存する．(.pdf)
4. Jupyter Notebook版はZIP圧縮ファイルとすること．(.ipynb ⇒ .zip)

## 目次

* chap.1. ビッグデータとデータエンジニアリング
  * 1.1 ICT（情報通信技術）の進展，ビッグデータ
  * 1.2 ビッグデータの収集と蓄積，クラウドサービス
  * 1.3 ビッグデータ活用事例
  * 1.4 社会で活用されているデータ（種類と所有者）
  * 1.5 検索エンジンとSNS，オープンデータ

* chap.2. データ表現
  * 2.1 コンピュータで扱うデータ（数値、文章、画像、音声、動画など）
  * 2.2 構造化データ、非構造化データ
  * 2.3 情報量の単位（ビット、バイト）、二進数、文字コード
  * 2.4 配列、木構造（ツリー）、グラフ
  * 2.5 画像の符号化、画素（ピクセル）、⾊の3要素（RGB）
  * 2.6 ⾳声の符号化、周波数、標本化、量⼦化

* chap.3. データ収集
  * 3.1 IoT（Internet of Things）
  * 3.2 IoTを支える要素技術（通信プロトコル，無線ネットワーク）
  * 3.3 エッジデバイス、センサーデータ
  * 3.4 Webクローラー、スクレイピング
 
* chap.4. データベース
  * 4.1 テーブル定義、ER図
  * 4.2 主キーと外部キー
  * 4.3 リレーショナルデータベース（RDB）
  * 4.4 データ操作⾔語（DML）、SQL

* chap.5. データ加⼯
  * 5.1 集計処理、四則演算処理
  * 5.2 ソート処理、サンプリング処理
  * 5.3 クレンジング処理（外れ値、異常値、欠損値）
  * 5.4 結合処理（内部結合、外部結合）
  * 5.5 データ型変換処理
  * 5.6 データの標準化、ダミー変数

* chap.6. ITセキュリティ
  * 6.1 セキュリティの3要素（機密性、可用性、完全性）
  * 6.2 データの暗号化、復号化
  * 6.3 データの盗聴、改ざん、なりすまし
  * 6.4 電⼦署名、公開鍵認証基盤（PKI）
  * 6.5 ユーザ認証とアクセス管理
  * 6.6 マルウェアによるリスク（データの消失・漏洩、サービスの停⽌など）

* chap.7. プログラミング基礎（前半）※東大MIセンターのものを利用する
* chap.8. プログラミング基礎（後半）※東大MIセンターのものを利用する


# memo

## 数理DS コア3科目（年度更新されない版） URL

* DS基礎 https://lms.ealps.shinshu-u.ac.jp/common/course/view.php?id=146
* DE基礎 https://lms.ealps.shinshu-u.ac.jp/common/course/view.php?id=147
* AI基礎 https://lms.ealps.shinshu-u.ac.jp/common/course/view.php?id=148

## 工学部 学部共通科目 データサイエンス科目（2023 R5年度版）　URL

* DS基礎(2023) https://lms.ealps.shinshu-u.ac.jp/2023/t/course/view.php?id=413
* DE基礎(2023) https://lms.ealps.shinshu-u.ac.jp/2023/t/course/view.php?id=414
* AI基礎(2023) https://lms.ealps.shinshu-u.ac.jp/2023/t/course/view.php?id=415


## 学外連携・その他 eALPS URL

### 経産省 共同研究講座

* 産学連携 / デジタル人材育成共同研究講座
https://lms.ealps.shinshu-u.ac.jp/other/course/index.php?categoryid=15

* データサイエンス概論
https://lms.ealps.shinshu-u.ac.jp/other/course/view.php?id=82
* データエンジニアリング概論
https://lms.ealps.shinshu-u.ac.jp/other/course/view.php?id=88
* 機械学習概論
https://lms.ealps.shinshu-u.ac.jp/other/course/view.php?id=89
* AIエンジニアリング概論（佐藤真平先生）
※新規コース設置中

### 工学教育寄附講座

* 産学連携 / 工学教育寄附講座
https://lms.ealps.shinshu-u.ac.jp/other/course/index.php?categoryid=16

* データサイエンス概論
https://lms.ealps.shinshu-u.ac.jp/other/course/view.php?id=96
* データエンジニアリング概論
https://lms.ealps.shinshu-u.ac.jp/other/course/view.php?id=97
* 機械学習概論
https://lms.ealps.shinshu-u.ac.jp/other/course/view.php?id=98
* 画像認識へのAIの適用（宮尾先生）
https://lms.ealps.shinshu-u.ac.jp/other/course/view.php?id=99
* AI技術による自然言語処理ツール入門（小形先生）
https://lms.ealps.shinshu-u.ac.jp/other/course/view.php?id=100
