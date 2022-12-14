# 職務経歴書

## 基本情報

|key|value|
|---|---|
|氏名|金子晴秋|
|生年月日|1995/10/01|
|居住地|東京都|
|最終学歴|武蔵大学/経済学部|

---

## 保有スキル

- フロントエンドの開発・運用、設計、要件定義（Nuxt.js、Dart/Angular、Next.js)
- サーバーサイドの開発・運用、設計、要件定義（Rust、Go、Kotlin、Python)
- アジャイル（XP)

---

## 技術スタック

### 言語

<p>
  <img alt="Rust" src="https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=Rust&logoColor=white">
  <img alt="Go" src="https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=Go&logoColor=white">
  <img alt="Dart" src="https://img.shields.io/badge/-Dart-0175C2?style=flat-square&logo=Dart&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/-TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" />
  <img alt="Python" src="https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=Python&logoColor=white" />
  <img alt="Kotlin" src="https://img.shields.io/badge/-Kotlin-0095D5?style=flat-square&logo=Kotlin&logoColor=white" />
</p>

### フレームワーク・その他

<p>
  <img alt="Nuxt.js" src="https://img.shields.io/badge/-Nuxt.js-00DC82?style=flat-square&logo=Nuxt.js&logoColor=white" />
  <img alt="Next.js" src="https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=Next.js&logoColor=white" />
  <img alt="Docker" src="https://img.shields.io/badge/-Docker-46a2f1?style=flat-square&logo=docker&logoColor=white" />
  <img alt="Kubernetes" src="https://img.shields.io/badge/-Kubernetes-326CE5?style=flat-square&logo=Kubernetes&logoColor=white" />
  <img alt="Buildkite" src="https://img.shields.io/badge/-Buildkite-14CC80?style=flat-square&logo=Buildkite&logoColor=white" />
  <img alt="Elasticsearch" src="https://img.shields.io/badge/-Elasticsearch-005571?style=flat-square&logo=Elasticsearch&logoColor=white" />
</p>

---

## 職務経歴詳細

### 株式会社ユーザベース（2021/05〜現在）

- **ユーザベースでの基本的な開発スタイル**
  1. アジャイル開発：XP(エクストリーム・プログラミング）の考えをベースに実践しています
  2. TDD(全体 e2e、単体 e2e、Unit Test)
  3. DDD とマイクロサービス（一部モノレポ）
  4. トランクベース開発 

**【プロダクト SPEEDA の R＆D 機能の新規機能開発・技術的負債の返済】**
- **プロジェクト概要：**
  - 製造業の知的財産部や研究開発部門のユーザーに使ってもらう機能の開発や Biz サイドとのコミュニケーションを取っていました
- **規模**
  - 7 名〜9 名
- **期間**
  - 2021/05 ~ 2022/06
- **プロジェクト詳細**
  - Dart/Angular でフロントの設計、開発
  - Python で BFF を設計、開発
  - サーバーサイドを Rust、 Kotlin で設計、開発
  - パートナーから貰うデータを取り込むための仕組み作り
  - 多めのデータをユーザーへ不便なく届けるための改善
  - 責務の切り分け（フロントで行うべきではなかった、ビジネスロジックを適切な API へ移行など）
  - CI/CD の一部改善（テスト実行、デプロイまでの改善や時間の短縮など）
- **その他**
  - チームメンバーとのコミュニケーション活性化
    - チームアップの開催
    - 1on1 や NewJoiner への期待値をしっかりと伝えるなど
    - 自分の持つ知識の共有やこうして欲しいという思いを伝えることを意識
  - PdM とのコミュニケーション
    - 次期 クウォーター でやりたい機能の壁打ちや懸念点を話す
    - 機能への疑問点やプロダクトチームから提案を率先

**【プロダクト SPEEDA の R＆D の Biz メンバーに使ってもらう簡易管理画面の作成】**
- **プロジェクト概要：**
  - 社内の一人プロジェクトという制度を活用
    - 開発の全てを一人で行うプロジェクトになります
  - R＆D 部門の Biz メンバーが R＆D 機能の持つデータへのアクセスや一部機能で使っているデータの更新がしにくい状況になっていたのでそれを解消すべく開発を行いました
- **規模**
  - 1 名
- **期間**
  - 2022/06 ~ 2022/06 末
- **プロジェクト詳細**
  - Nuxt.js(3 系）でフロントの設計、開発
  - Go で BFF を設計、開発
  - サーバーサイドを Rust で設計、開発
  - CRUD 機能の開発
  - 多めのデータから任意のキーワードで検索できるように Elastic Search を採用
  - 検索で Hit したデータを見やすくするためにグラフ化
  - Deploy はすぐに出来る様にしたが、e2e は無し（Unit Test だけは流れます）
- **その他**
  - PdM とのコミュニケーション
    - 細かい頻度で会話し、PoC して改善を繰り返したので出来上がる機能と PdM とのイメージがズレることなく開発

**【プロダクト NewsPicks Stage の開発】**
- **プロジェクト概要：**
  - セミナーという概念を乗り越えて映像コミュニティとして機能するプロダクトを目指して開発を行っています
- **規模**
  - 5 名
- **期間**
  - 2022/07 ~ 09 
- **プロジェクト詳細**
  - Next.js でフロントの設計、開発
  - サーバーサイドを Rust で設計、開発
  - モジューラモノリスにサーバーサイドを移行中

**【プロダクト プロダクト SPEEDA R＆D 特許検索機能の開発】**
- **プロジェクト概要：**
  - とある機能の検索機能開発と企業毎の論文執筆者を見ることが出来る機能の開発
- **規模**
  - 8 名
- **期間**
  - 2022/10 ~ 現在
- **プロジェクト詳細**
  - 2000 万件ほどのデータを elasticsearch に移行するためのパイプライン構築
  - マイクロサービス（API)の切り出し、パイプラインの構築
  - 別API のモジューラモノリス化
  - SQLのパフォーマンス調査

### その他やっていたこと
- 会社の経営チームへの参加
- エンジニアの採用
- 社内副業の参加 

### 株式会社エビリー（2019/06〜2021/04）

**【kamui tracker の新機能開発】**
- **プロジェクト概要：**
  - とある周期で来るキーワードを集計して、そのキーワードに紐づく
    成功している動画を 20 件表示して、クリエイターの参考にしてもらう機能の開発
    主に要件を詳細化、機能の開発、リリースなどを行なっています
  - 規模：4〜5 名ほどでスクラム開発
       
**【機能】**
- クリエイターがとある周期で来るかつ、良く検索されるキーワードから動画企画を参考に出来る機能
- どの周期でそのキーワードが検索されるかをわかるようにグラフを表示
- そのキーワードに紐づく評価された動画を 20 件程表示する
- キーワードだけを参考にしても意味がないので、評価された動画サムネイルが目立つように表示

**【バックエンド：Ruby、Python】**
- 既存のデータからキーワードを集計
  - 一年間ずっと出るような明らかに設定した周期性が無いキーワードを除外
- そのキーワードに紐づく周期データを外部 API を活用して取得
- 外部 API から取得した系列データを使って設定した周期性があるかを判断する 
  - Python のライブラリなどを使い自己相関係数のデータを抽出
- これらのバッチ処理を作成

**【フロントエンド：Nuxt.js、TypeScript】**
- キーワードだけを参考にしても意味がないので、評価された動画サムネイルが目立つように表示
  - この部分をプロダクトオーナーと議論、どのような画面構成が一番プロダクトを通して伝えたいことが正確に伝わるよう UI を設計
- ちょうど Nuxt.js に移行した時期でもあり、Atomic Design を参考にしつつコンポーネント作成
- Jest でユニットテストの作成もこの際に導入

**その他**
 - Python のライブラリ管理として poetry を追加
 - EC2 で poetry を含めた Python が正常に動作するかを検証
 - GitHubActions に Python 周りの設定を追加

- **プロジェクトに取り組む際気を付けていたこと：**
  1. なぜその機能を開発するのか
     - プロダクトオーナーから来る要件などに対して、その機能をなぜ開発するのかという
       ことを擦り合わせることを大切にしてきました。プロダクトオーナーがプロダクトを通し
       てユーザーに提供したい価値や実現したいことを把握、私からこうするのが良いのではな
       いかという改善案などを提示するように努めています  
  2. ユーザーへのミスリードに繋がっていないか
     - バックエンド側で作成するデータやフロントエンドでの見せ方などバックエンド、フロン
       トエンド共にユーザーへ提供したい価値がプロダクトを通して間違った方向に提示されて
       いないかを気をつけています
  3. 挑戦する、それを楽しむ
     - 自分が経験していないことや他人が取り組みたがらないことにもまずは取り組みました。
       かつそれ自体を楽しむことを心がけていました