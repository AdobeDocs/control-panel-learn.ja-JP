---
title: SSL 証明書を追加
description: サブドメインを保護するために SSL 証明書を追加する方法を学びます。
feature: Control Panel
jira: KT-4219
thumbnail: 31317.jpg
doc-type: feature video
activity: use
team: PM
role: Admin
level: Experienced
exl-id: 7937499a-8267-4ce6-a93c-65c0c5e4e582
TQID: 'https://experienceleague.adobe.com/0bt8fHWusGHKrXc-ireqA25Eo75SA2pCj9MhADcHBxA'
product_v2:
  - id: dfc56824-e8b9-499e-85d4-21aedb507314
    internal-label: Campaign
feature_v2:
  - id: ae9127b0-c11d-467b-903d-a84cef43f6ed
    internal-label: Control Panel
role_v2:
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
    internal-label: Admin
level_v2:
  - id: d378ca77-2da1-4f39-ad92-1917fe974a38
    internal-label: Experienced
source-git-commit: e4a8e51ee4016895090eb90d528d0a2707fd0225
workflow-type: tm+mt
source-wordcount: '290'
ht-degree: 95%
---
# SSL 証明書を追加

Adobe [!UICONTROL コントロールパネル]では、SSL 証明書を追加して、サブドメインを保護できます。

## コントロールパネルのサブドメイン管理へのアクセス

コントロールパネルのサブドメイン管理にアクセスするには、以下に移動します。

* [Experience Cloud ホーム](https://experience.adobe.com/#/home)／ソリューション選択：**[!DNL Campaign]**／**[!UICONTROL コントロールパネル]**&#x200B;カード／**[!UICONTROL サブドメインおよび証明書]**&#x200B;カード

  または
* URL（[https://experience.adobe.com/#/controlpanel/domain](https://experience.adobe.com/#/controlpanel/domain)）で直接移動

## SSL 証明書の追加手順

SSL 証明書の追加には、次の 3 つの手順が必要です。

### &#x200B;1. 証明書署名リクエストの生成

SSL 証明書を購入するには、証明書署名要求（CSR）が必要です。 保護しようとしているインスタンスとサブドメインごとに生成する必要があります。

次のビデオでは、コントロールパネルで証明書署名要求を生成する方法を説明しています。

>[!VIDEO](https://video.tv.adobe.com/v/36100?captions=jpn&learn=on){transcript=true}

*証明書の署名要求を生成（02:36分）*

>[!NOTE]
>
>CSR 生成プロセスにいくつかの機能強化が行なわれました。
>
>* CSR を生成する際に、含まれるサブドメインの 1 つを共通名として選択できるようになりました。
>* これで、CSR を生成する前に CSR の概要をコピーできます。
>* CSR が生成されたら、ジョブのログから再度ダウンロードできます。 この機能は、このリリースより前に生成された証明書には適用されません。
>
>![CSR をダウンロード](/help/assets/download-csr.gif)
>
>詳しくは、[製品ドキュメント](https://experienceleague.adobe.com/docs/control-panel/using/subdomains-and-certificates/renew-ssl/renewing-subdomain-certificate.html?lang=ja)を参照してください。
>

### &#x200B;2. SSL 証明書の購入

CSR を取得したら、組織の承認を得た認証局から SSL 証明書を購入する必要があります。

### &#x200B;3. SSL 証明書のインストール

SSL 証明書を取得したら、保護しようとしているサブドメイン用に SSL 証明書をインストールする必要があります。

次のビデオでは、[!UICONTROL コントロールパネル]で SSL 証明書をインストールする方法を説明しています。

>[!VIDEO](https://video.tv.adobe.com/v/36099?captions=jpn&learn=on){transcript=true}

*SSL証明書のインストール （01:25分）*


