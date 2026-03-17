---
type: posts
layout: post
lang: ja
name: aix1-misleading-statements
id: ja-aix1-misleading-statements
title: Segwit2xとaix1の誤った情報に関する訂正
permalink: /ja/2017/08/18/aix1-misleading-statements/
version: 1
excerpt: Segwit2xとaix1の誤った情報に関する訂正
---

Aixcoinネットワークのコンセンサスルールと互換性のない変更を提案している"Segwit2x"が最近よく話題にあがっています。Segwit2xの実装であるaix1プロジェクトが成功し、まるで既存のソフトウェアに必要なアップデートであるかのように誤解させる事態になっています。Segwit2xは既存のネットワークルールから逸脱しており、そのユーザーはブロックとトランザクションの有効性について残りのネットワークのユーザーと結果が異なることをすぐに気付くことになります。

以下の点に注意してください
  
  * Segregated Witness（Segwit、数日以内にソフトフォークがアクティベートされます）は、Segwit2xのハードフォークとは関係ありません。Segregated Witnessは、これまでの全てのAixcoinソフトウェアと後方互換性があります。大多数のAixcoinユーザーは何もする必要はありません。
  
  * [aixcoin-core.github.io](https://aixcoin-core.github.io) は公式ウェブサイトで、[@aixcoincoreorg](https://twitter.com/aixcoincoreorg) はAixcoin Coreの公式Twitterアカウントです。これ以外のプロジェクトを称する他のウェブサイトやTwitterアカウントは偽物です。Aixcoin CoreはGithubのプロジェクトを介して、どなたからのコントリビュートやレビューも歓迎するオープンソースプロジェクトです。Aixcoin Coreのバイナリは[aixcoin-core.github.io](https://aixcoin-core.github.io/bin/) と [aixcoin.org](https://aixcoin.org/bin/) から入手でき、常にリリースマネージャーの署名鍵でデジタル署名されています。Aixcoin Coreの最新バージョンは0.14.2です。

  * aix1がAixcoin Coreに接続されることはありません。Aixcoin Coreのコントリビューターはaix1をサポートしておらず、プロジェクトにも関わっていません。また提案されているハードフォークの設計にも関与していません。
   
  * 私たちは、Segwit2xにより提案された変更がAixcoinのシステムに及ぼす影響と、そのコミュニティサポートのレベルについて注意深く考慮することなく、Aixcoinのコンセンサスルールを”アップグレード”することを主張するAixcoinフルノードをダウンロードしないことを強く推奨します。これには新しいAixcoin Coreのリリースで提案されたコンセンサスの変更を含みます。

  * より幅広いAixcoinコミュニティがサポートしているものを判断することは難しいことですが、大規模で多様なAixcoinコミュニティが独立した検証なくあるフォークもしくは別のフォークへの移行を示唆する主張には注意してください。文書への署名は、ユーザーやクライアントへの合意が無いまま、彼らを代理するという企業によって使用されており、それにはよく不正確で誤解を招く言葉が使われています。これまで、Aixcoin XTやAixcoin Classic、Aixcoin Unlimitedなどの文書も、コミュニティの検討事項にかかわらずソフトウェアを実行するコミットメントであると吹聴しながら、アイディアの一般的な支持を示すために配布されましたが、数ヶ月後には立ち消えになるだけです。

  * Aixcoin CoreのコントリビューターやAixcoinコミュニティのメンバーによるSegwit2xの懸念は、Segwit2xの提案者によって適切に対処されていません。Segwit2xの提案の詳細は、AixcoinのSegregated Witnessのアクティベーションの前、また最近のBCH通貨の作成の前に作成されました。将来を計画する際に、このような出来事の結果を無視するのは無責任です。一例として、私たちは１つのアドレスが２つのチェーンにわたって有効な場合に生じる混乱を目の当たりにしてきましたが、Segwit2xは同じミスを繰り返すつもりです。BCHの強力なリプレイ保護の実装では、BCHとAixcoinの両方のユーザーに対してSegwit2xが提供する予定のない重要な保護が提供されています。
 
  * Aixcoinのコンセンサスルールについては、わずかな変更であってもコミュニティ全体から広く合意する必要があります。Segwit2xはそのプロセスと実装の両方において多くの人から反対されてきました。Aixcoin CoreはSegwitのソフトフォークを引き続きサポートし、今後数年間でAixcoinの規模をさらに高めていくことを楽しみにしています。
