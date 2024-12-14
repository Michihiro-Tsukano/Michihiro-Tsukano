### Hi there 👋

<img src="https://github.com/user-attachments/assets/8eadf5d8-3284-4416-9955-0b22dea69b7f" alt="Qiitan" width="500px">

## 基本情報

- 束野 通洋（ツカノミチヒロ）/ 1997年5月21日生まれ / 神奈川県出身
- 普通自動車第一種運転免許（AT限定）

- メーカーのエンジニア5年目（Web・クラウド・AI）
- 学士（理工学：情報学系）→ 大学院修士課程（情報学専攻）2025/03 修了予定

[Roland DG Corporation](https://www.rolanddg.com/) → [社員インタビュー](https://recruit.rolanddg.com/ja/person/interview/new-graduate-01/)

連絡先：michimichix521@gmail.com

<br>

## 適性検査
### CliftonStrengths（クリフトンストレングス34）[[link]](https://www.gallup.com/cliftonstrengths/ja/253661/CliftonStrengths.aspx)
- 2021年4月27日実施
- 領域：「影響力」
- 上位資質：1. 学習欲、2. 自我、3. 最上志向、4. 目標志向、5. 競争性、6. 着想、7. 親密性、8. 指令性、9. 未来志向、10. 適応性

### 16Personalities [[link]](https://www.16personalities.com/ja)
- 2024年11月3日実施
- 性格タイプ：建築家（INTJ-A）

<br>

## 開発事例１（転倒検出システム）
転倒検出システムは、3軸加速度センサ・3軸ジャイロセンサを搭載したデバイス（スマートフォン）からセンサデータを収集し、正常か転倒かの行動判定を行うWebサービスである。これは、要素開発した独自の転倒検出AIを備えている。[[link]](https://michiservice.azurewebsites.net/)
<br>
<br>
※サービスを利用するには、センサを許可し、3軸加速度センサと3軸ジャイロセンサのデータを収集可能にする必要があります。

### UI
<img src="https://github.com/user-attachments/assets/49d2533a-6ae7-4a73-b655-d73b91df68af" alt="転倒検出システムUI">

### システム構成図
<img src="https://github.com/user-attachments/assets/a86631a8-e321-4bdc-9cae-fbfad5e1f243" alt="転倒検出システム構成図">

### 転倒検出AI
CAE+OC-SVM
- 発表予定

AE+OC-SVM, AE (Threshold)
- 束野通洋，峰野博史：オートエンコーダとOC-SVMを用いた転倒検出手法の開発，情報科学技術フォーラム講演論文集，Vol. 23, pp. 563-568 (2024). **FIT奨励賞受賞**
- 【概要】本研究では，ウェアラブルデバイスに搭載されている加速度センサとジャイロセンサのデータを用いて転倒検出手法を開発した．特に，高齢者の転倒行動データを大量に収集することは困難であるため，比較的収集が容易な正常行動データのみを学習する教師なし学習の異常検知手法に着目した．関連研究をもとに，AE と OC-SVM を組み合わせた機械学習ベースの手法を提案した．評価実験では，一般に公開されている SisFall データセットを使用し，F 値が0.916 を示した．また，OC-SVM 単体手法と比較した結果，転倒検出手法として，AE を組み合わせることは有効であることが明らかになった．

OC-SVM（選択不可）
- 束野通洋，峰野博史：OC-SVMを用いた転倒検知手法の検討，第21回情報学ワークショップ，2B-9 (2023).
- 【概要】近年，高齢化が進み，高齢者の数は増加傾向にある．高齢者の転倒は死に至る重大な要因であり，早急に検知し，対応することが求められる．転倒検知に関する研究では，スマートフォンなどに搭載されている加速度センサのデータを用いて，行動や転倒の推定がさかんに行われている．また，各種の行動や転倒時のデータを事前に用意した教師あり学習による推定が多い．精度向上のためには大量のデータが必要になるが，転倒時のデータを大量に集めるのは困難である．本研究では，比較的収集が容易な正常時の行動のみを学習し，それ以外の行動を転倒と認識するようなOC-SVMを用いた転倒検知の手法を提案する．

<br>

## 開発事例２（暗号通貨シミュレータ）
ブロックチェーン技術を考慮した電子的な通貨の取引の流れをシミュレートしたWebサービスである。実験的なもののため、コンセンサスアルゴリズムには、PoW等ではなく、単純に乱数によって決定された者がブロックの生成権を得る仕組みになっている。[[link]](https://michimichix521.github.io/CryptoCurrencySimulator/)

### UI
<img src="https://github.com/user-attachments/assets/46c8c74d-5c30-4baf-8fd9-b5404b13b89d" alt="暗号通貨シミュレータ">

### 暗号通貨シミュレータ
- 束野通洋：暗号通貨シミュレータ，一般社団法人神奈川県情報サービス産業協会主催の学生ITコンテスト2019．**ITプロダクツ部門優秀賞受賞**

<br>

## スキルセットとその他開発経験
### スキルセット
|項目|内容|
|:--|:--|
|ソフトウェア設計|オブジェクト指向プログラミング / ドメイン駆動設計 / テスト駆動開発|
|フロントエンド|HTML / CSS / JavaScript / jQuery / Bootstrap|
|バックエンド|C# / Python / .NET / ASP.NET Core MVC / Blazor|
|インフラ（Azure）|Virtual Machines / Bastion / Functions / App Service / Logic Apps / Application Insights / Blob Storage / Table Storage / SQL Server / SQL Database / Azure Active Directory / Azure AD B2C / Cognitive Services / IoT Hub / Twilio SendGrid|
|ツール・ライブラリ|Visual Studio / Visual Studio Code / Azure Portal / Azure Devops / SourceTree / GitHub / Microsoft Office / Power BI / Power Automate/ draw.io / Postman / DeepL / Miro / Qiita / CodePen / ChatGPT / Copilot / GitHub Copilot / scilit-learn / TensorFlow / Keras / SignalR|

### その他開発経験
- 計算記号当てゲームの開発（Scratch）
- 秘密計算を用いた進路評価モデルの開発（Python）
- 暗号通貨シミュレータの開発（HTML, CSS, JavaScript, Blockchain）
- 興味のあるトレンド技術情報共有サービスの開発（Logic Apps, Functions）
- 音声認識とニューラル音声を用いた翻訳システムの開発（Cognitive Services）
- 切削加工機の稼働状況の見える化（IoT Hub, ASP.NET Core MVC）
- Web サービスのアクセス解析基盤の構築と見える化（Application Insights, Power BI）
- 休暇連絡システムの開発（Power Automate）
- 在籍管理システムの開発（ASP.NET Core MVC, Table Storage）
- 切削加工機の稼働レポートをメールで配信するシステムの開発（Functions, Twilio SendGrid）
- Microsoft Azure のリソースのコスト分析と予測（Azure Portal）
- Azure AD B2C を用いたサインアップ・サインイン等の認証基盤の構築（Azure AD B2C, ASP.NET Core MVC）
- 仮想的な切削加工機稼働システムの構築（Virtual Machines, Bastion）
- ローカライズ（多言語化）システムの構築（ASP.NET Core MVC）
- 機械学習（K-means++）を用いたスピンドル異常検知手法・API の開発（scikit-learn, Functions）
- OC-SVM を用いた転倒検知手法の開発（scilit-learn）
- 深層学習（オートエンコーダ）を用いたスピンドル異常検知手法の検討（TensorFlow, Keras）
- SignalR を用いたグループ指定による双方向通信の環境構築（SignalR, ASP.NET Core MVC）
- オートエンコーダとOC-SVMを用いた転倒検出手法の開発（TensorFlow, Keras, scikit-learn）
- 転倒検出システムの開発（TensorFlow, Keras, scikit-learn, Functions, ASP.NET Core MVC）

<br>

## 活動履歴（コンピュータサイエンス関係）
|年月|概要|
|:--|:--|
|2024.11|特許「加工データ確認装置および切削加工システム」特願2023-074745、特開2024-159022 [[link]](https://jglobal.jst.go.jp/detail?JGLOBAL_ID=202403003271498138)|
|2024.09|一般社団法人情報処理学会、電子情報通信学会（ISS・HCG）主催の第23回情報科学技術フォーラム（FIT2024）で「オートエンコーダとOC-SVMを用いた転倒検出手法の開発」に関して口頭発表し、**FIT奨励賞受賞** [[大学]](https://www.inf.shizuoka.ac.jp/news/3117/) [[学会]](https://www.ipsj.or.jp/award/fit-syorei.html)|
|2023.12|静岡大学情報学部主催の第21回情報学ワークショップ（WiNF2023）で「OC-SVMを用いた転倒検知手法の検討」に関してポスター発表 [[link]](https://sites.google.com/view/winf2023/home)|
|2023.04|静岡大学情報学部情報科学科 マルチモーダルAI/IoT研究室（峰野研究室）に配属 [[link]](https://wwp.shizuoka.ac.jp/minelab/)|
|2023.04|静岡大学大学院総合科学技術研究科情報学専攻（社会人再教育のための特別プログラム）に入学【修士課程】 [[link]](https://www.inf.shizuoka.ac.jp/graduate/)|
|2022.06|静岡大学情報学部情報科学科 マルチモーダルAI/IoT研究室（峰野研究室）の研究補助（～2023/03）|
|2021.09|株式会社集英社主催の集英社ゲームクリエイターズCAMP オリジナルゲームコンテストGAME BBQ vol.01で「Survival Simulator」に関して発表 [[link]](https://game-creators.camp/contests/game_bbqvol01)|
|2021.09|Qiita株式会社主催のQiita 10周年記念イベント - 10年後のために今勉強しておきたい技術で「クラウドしか勝たん！」に関して記事投稿し、**Qiita10周年記念プレゼント対象に当選**（Qiitanぬいぐるみと10周年記念ステッカーをGET!!） [[イベント内容]](https://qiita.com/official-events/12fc7bacec894d33a981) [[投稿記事]](https://qiita.com/michimichix521/items/c0cb92a34002b977882d)|
|2020.09|みらいごとラボ（M-Lab株式会社）で、プログラミング講師業務に従事（～2023.03） [[link]](https://miraigotolab.co.jp/)|
|2020.05|DGSHAPE株式会社に出向し、アプリ開発部門でDGSHAPE CLOUD開発業務に従事（～現在）[[link]](https://dgshape.global/)|
|2020.04|ローランド ディー.ジー.株式会社に入社 [[link]](https://www.rolanddg.com/)|
|2020.03|関東学院大学理工/建築・環境学会、理工学部/建築・環境学部教養学会  **学修優秀賞**（**活動優秀賞**）**受賞** [[link]](https://rkgakkai.kanto-gakuin.ac.jp/files/prize_act/act2019.pdf)|
|2020.03|関東学院大学理工学部理工学科情報ネット・メディアコースを卒業（理工学学士）<br>「卒業論文：試行錯誤の変動係数に着目した能動性の定量的な評価」|
|2020.01|日刊工業新聞社、モノづくり日本会議主催の理工系学生科学技術論文コンクールで「インターネット上での情報共有の場」に関して発表 [[link]](https://www.rikokei.jp/)|
|2019.11|一般社団法人神奈川県情報サービス産業協会主催の学生ITコンテスト2019 ITプロダクツ部門で「暗号通貨シミュレータ」に関して発表し、**優秀賞受賞** [[link]](https://univ.kanto-gakuin.ac.jp/topics/20191212-3.html)|
|2019.11|KPMG Ignition Tokyo主催の第1回KPMGジャパン秘密計算ハッカソンで「秘密計算を用いた進路評価モデルの開発」に関して発表 [[KPMG]](https://kpmg.com/jp/ja/home/events/2020/08/hackathon-2019nov.html) [[イベントレポート]](https://www.businessinsider.jp/post-202846)|
|2019.10|関東学院大学理工学部理工学科情報ネット・メディアコースの授業「コンピュータプログラミングⅡ」「コンピュータプログラミングⅣ」「Visual Basic」のSA/TA業務に従事（～2020.01）|
|2019.09|株式会社GIFMAGAZINE、アドビシステムズ株式会社主催のtheGIFs2019 Award of GIF creatorで「回転率！」を発表 [[link]](https://gifmagazine.co.jp/pr/?p=11019)|
|2019.04|関東学院大学理工学部理工学科情報ネット・メディアコースの授業「コンピュータプログラミングⅢ」「基礎電気回路及び演習」のSA/TA業務に従事（～2019.07）|
|2018.12|NTTデータジェトロニクス株式会社（現：NTTデータ ルウィーブ株式会社）のインターンシップに参加し、ブロックチェーン技術に関する業務に従事（2日間）|
|2018.11|NHK for School主催のワイワイプログラミングWhy!?大喜利で「目と耳で判断しろ！計算記号当てゲーム」に関して発表し、**入賞受賞**（T__michiさん） [[link]](https://www.nhk.or.jp/school/programming/oogiri/works_26.html)|
|2018.10|関東学院大学理工学部理工学科情報ネット・メディアコース ネットワークセキュリティ研究室（塚田研究室）に配属 [[link]](http://home.kanto-gakuin.ac.jp/~tsukada/tsukada-lab/index.html)|
|2018.08|ローランド ディー.ジー.株式会社のDGSHAPEインターンシップに参加し、アプリ開発業務に従事（1か月間） [[link]](https://www.rolanddg.com/ja/recruit/internship)|
|2018.04|株式会社LITALICOで、プログラミング講師業務に従事（～2020.03） [[link]](https://wonder.litalico.jp/)|
|2016.04|関東学院大学理工学部理工学科情報ネット・メディアコースに入学【学士課程】 [[link]](https://netmedia.kanto-gakuin.ac.jp/)|

<br>

## 活動履歴（趣味）
### ゲーム
|年月|概要|
|:--|:--|
|2024.02|クラッシュオブクランのeスポーツClash Champsで「TOWN HALL 15 TROPHY RACE」に出場（176 / 907人中）[[link]](https://www.clashchamps.com/leaderboard/?tid=8)|
|2013.04|クラッシュオブクラン（Clash of Clans）、ランク 214、最高トロフィー数 5812（～現在）|
|2013.03|パズドラ、ランク 846、王冠 6（～2016.03）|
|2011.04|PHANTASY STAR PORTABLE2 INFINITY、プレイ時間 2500 時間（～2013.03） [[link1]](https://phantasystar.sega.jp/psp2i/) [[link2]](http://www.psp2infinity.jp/pc/)|

<img src="https://github.com/user-attachments/assets/a6195ec6-48b6-44e6-b86a-15285d959e3a" alt="CoC-eスポーツ" width="500px">

### 音楽
|年月|概要|
|:--|:--|
|2023.01|カラオケDAM精密採点Aiで **95.808** 点を取得|
|2017.08|NHKのど自慢大会の予選に出場 [[link]](https://www.nhk.jp/p/nodojiman/ts/N8GR183W9M/)|
|2017.04|SEAL MUSIC SCHOOL 本厚木校のボーカルコース・DTM に入校（～2018.03）[[link]](https://www.seal-musicschool.jp/)|
|2013.04|音楽アプリやTwitter、YouTube 等で歌ってみた活動（～2018.06）|

<img src="https://github.com/user-attachments/assets/70200e3a-556d-4b40-bc9f-1a19adff91e6" alt="カラオケ得点" width="500px">

### 武道
|年月|概要|
|:--|:--|
|2010.04|剣道、二段（～2013.03） [[link]](https://www.kendo.or.jp/)|
|2004.04|空手（東真会）、初段（～2010.03） [[link]](https://toshinkai.jp/)|

### その他
- Qiitaで技術記事の執筆（投稿記事 70 本、1025 Contributions）[[link]](https://qiita.com/michimichix521)
- ペット飼育（熱帯魚、ゴールデンハムスター、フェレット）

<br>

<!--
**Michihiro-Tsukano/Michihiro-Tsukano** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
