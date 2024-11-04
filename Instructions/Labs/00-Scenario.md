---
lab:
  title: 応用ワークショップシナリオ
---

# 応用ワークショップ: Dynamics 365 カスタマー エクスペリエンス ソリューションを構成する

受講者がコース全体で習得したスキルを実際の例に適用できるように MB-280 コースが設計されている場合の応用ワークショップ部分です。 このシナリオには、Dynamics 365 Sales、Customer Insights - Journeys、Customer Insights - Data にわたるさまざまな要素が含まれています。 

以下に示すシナリオに基づいて、架空の会社のビジネス要件を満たすように Dynamics 365 環境を作成し構成します。 対処するすべての項目を必ずしも解決する必要がないことに注意してください。 割り当てられた時間と含まれている内容により、あなたは一部の項目にしか対処できないかもしれませんが、それはかまいませんし、元々そういう仕様です。 

**重要:** これを実現するための正しい方法や間違った方法が必ずしもあるわけではありません。 シナリオで概説されている条件に基づき、さまざまな要素の一括活用に対する考え方に応じてソリューションを生成および構成してください。

1 日の終わりに、各受講者には、作成したソリューションの一部または全部を順を追って説明する時間が 5 から 10 分与えられます。 

## シナリオ: Contoso Home Security 
Contoso Home Security は、直販の家庭向けセキュリティ機器および監視の会社です。 その製品には、スマート ドアベル、スマート サーモスタット、セキュリティ システム、湿度センサーなどがあります。 直接販売であるため、同社の製品はオンラインで、または米国の主要な 11 都市の小売店で販売されています。 オンラインの顧客には、アカウント担当者が割り当てられます。 その役割は、顧客をフォローアップし、さらなる製品やサービスを提供しようとすることです。 

今後の演習では、その詳細なビジネス要件について説明します。

## 時間管理 

この課題のすべての側面を完了するには丸 1 日 (6.5 時間) かかります。 最初にすべての期待事項を確認してから、時間管理を開始します。 フェーズ 1 では小グループでのディスカッションを行う予定ですが、1 人で作業している場合は、残りの課題に役立つように、個人でブレインストーミングを行う時間を確保してください。 ほとんどの時間はフェーズ 2 と 3 に費やします。 フェーズ 4 を開始するタイミングはインストラクターが指示しますが、これには約 1 時間かかると想定してください。

次のように計画されています。
- **フェーズ 1:** 小グループでのディスカッション
- **フェーズ 2:** ソリューションの設計
- **フェーズ 3:** ソリューションのビルド
- **フェーズ 4:** ソリューションの共有と比較

### フェーズ 1: 小グループでのディスカッション

ソリューションの設計方法を小グループで話し合います。 組織のビジネス要件を解決するためのソリューションにアプローチする方法について、ブレーンストーミング セッションを行います。

次の点について検討してください。
1. Contoso のデータ モデルはどのようなものか
2. どのような構成変更が必要か
3. 無関係な情報が提供されているか

### フェーズ 2: ソリューションの設計
次に、ソリューションへのアプローチ方法を計画する必要があります。 紙に (またはデジタル機器など、自分に合った方法で) 書いて、To Doリストを作成します。

次の点について検討してください。
1. 新しいソリューションを作成する必要があるか なぜそうなのでしょう? または、なぜそうではないのでしょう?
2. 既存のアセットを編集すべきか、それともゼロから始めるべきか
3. 新しいセキュリティ ロールを更新または作成する必要があるか

### フェーズ 3: ソリューションのビルド
ソリューションを構成する段階になりました。

次の点について検討してください。
1. 特定の構成変更を行う必要があるアプリケーションは何か
2. 構成を変更する順序は重要か どこから着手するか
3. ユーザー エクスペリエンス設計に関する知識を使用して、構成の変更をユーザーにとって最適に機能させるにはどうすればよいか

### フェーズ 4: ソリューションを共有して比較する
小グループと作業を共有します。 カスタマー エクスペリエンス アナリストとしてのエクスペリエンスと、ソリューションのユーザーとしてのエクスペリエンスを比較します。

次の点について検討してください。
1. 他のチームが行ったものの違いは何ですか? それでもビジネス要件を満たしますか?
2. ソリューションをどのように改善しますか?