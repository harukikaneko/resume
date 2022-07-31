# 職務経歴書

## 基本情報

|key|value|
|---|---|
|氏名|金子晴秋|
|生年月日|1995/10/01|
|居住地|東京都|
|最終学歴|武蔵大学経済学部|

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

- 

### 株式会社エビリー（2019/06〜2021/04）

kamui tracker の新機能開発
- **プロジェクト概要：**
   - とある周期で来るキーワードを集計して、そのキーワードに紐づく
    成功している動画を 20 件表示して、クリエイターの参考にしてもらう機能の開発
    主に要件を詳細化、機能の開発、リリースなどを行なっています。
       
成功体験
【新機能を要件定義からリリースまでを押し進められたこと】
＜機能＞
- クリエイターがとある周期で来るかつ、良く検索されるキーワードから動画企画を参考に出来る機能
- どの周期でそのキーワードが検索されるかをわかるようにグラフを表示
- そのキーワードに紐づく評価された動画を 20 件程表示する
- キーワードだけを参考にしても意味がないので、評価された動画サムネイルが目立つように表示

＜技術＞
【バックエンド：Ruby、Python】
- 既存のデータからキーワードを集計
　→一年間ずっと出るような明らかに設定した周期性が無いキーワードを除外
- そのキーワードに紐づく周期データを外部 API を活用して取得
- 外部 API から取得したとき系列データから設定した周期性があるかを判断するために自己相関係数を使い判定
　→Python のライブラリなどを使い自己相関係数のデータを抽出
- これらのバッチ処理を作成

【フロントエンド：Nuxt.js、TypeScript】
- キーワードだけを参考にしても意味がないので、評価された動画サムネイルが目立つように表示
　→この部分をプロダクトオーナーと議論、どのような画面構成が一番プロダクトを通して伝えたいことが正確に伝わるようになるか UI を設計
- ちょうど Nuxt に移行した時期でもあり、Atomic Design を参考にしつつコンポーネント作成
- Jest でユニットテストの作成もこの際に導入

その他
 - Python のライブラリ管理として poetry を追加
 - EC2 で poetry を含めた Python が正常に動作するかを検証
 - GitHubActions に Python 周りの設定を追加

- **プロジェクトに取り組む際に気を付けていたこと：**
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