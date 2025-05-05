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
source-git-commit: 81c5210502e719d6dfe0a000c511e3da4b17275a
workflow-type: tm+mt
source-wordcount: '269'
ht-degree: 100%

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

### 1. 証明書署名要求の生成

SSL 証明書を購入するには、証明書署名要求（CSR）が必要です。保護しようとしているインスタンスとサブドメインごとに生成する必要があります。

次のビデオでは、コントロールパネルで証明書署名要求を生成する方法を説明しています。

>[!VIDEO](https://video.tv.adobe.com/v/36100?learn=on&captions=jpn){transcript=true}

*証明書署名要求の生成（2 分 36 秒）*

>[!NOTE]
>
>CSR 生成プロセスにいくつかの機能強化が行なわれました。
>
>* CSR を生成する際に、含まれるサブドメインの 1 つを共通名として選択できるようになりました。
>* これで、CSR を生成する前に CSR の概要をコピーできます。
>* CSR が生成されたら、ジョブのログから再度ダウンロードできます。この機能は、このリリースより前に生成された証明書には適用されません。
>
>![CSR をダウンロード](/help/assets/download-csr.gif)
>
>詳しくは、[製品ドキュメント](https://experienceleague.adobe.com/docs/control-panel/using/subdomains-and-certificates/renew-ssl/renewing-subdomain-certificate.html?lang=ja)を参照してください。
>

### 2. SSL 証明書の購入

CSR を取得したら、組織の承認を得た認証局から SSL 証明書を購入する必要があります。

### 3. SSL 証明書のインストール

SSL 証明書を取得したら、保護しようとしているサブドメイン用に SSL 証明書をインストールする必要があります。

次のビデオでは、[!UICONTROL コントロールパネル]で SSL 証明書をインストールする方法を説明しています。

>[!VIDEO](https://video.tv.adobe.com/v/36099?learn=on&captions=jpn){transcript=true}

*SSL 証明書のインストール（1 分 25 秒）*


