---
title: オーストラリア国内のお客様の識別データの保存 - Azure AD
description: Azure Active Directory によってオーストラリア国内のお客様の識別関連データがどこに保存されるかについて説明します。
services: active-directory
author: ajburnle
manager: daveba
ms.author: ajburnle
ms.service: active-directory
ms.subservice: fundamentals
ms.workload: identity
ms.topic: conceptual
ms.date: 7/21/2020
ms.custom: it-pro, seodec18, references_regions
ms.collection: M365-identity-device-management
ms.openlocfilehash: 494b949594574a55df405ec0447fa6c59f386f7d
ms.sourcegitcommit: fbb66a827e67440b9d05049decfb434257e56d2d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/05/2020
ms.locfileid: "87799039"
---
# <a name="customer-data-storage-for-australian-and-new-zealand-customers-in-azure-active-directory"></a>Azure Active Directory でのオーストラリアとニュージーランドの顧客データの保存

Azure Active Directory (Azure AD) の顧客データは、お客様が Microsoft オンライン サービスにサインアップしたときに指定した国に基づいて地理的な場所に保存されます。 Microsoft オンライン サービスには、Office 365 や Azure があります。 

Azure AD およびその他の Microsoft サービスのデータが配置される場所の詳細については、Microsoft セキュリティ センターの[お客様のデータの場所](https://www.microsoft.com/trustcenter/privacy/where-your-data-is-located)に関するセクションを参照してください。

2020 年 2 月 26 日から、Microsoft は、オーストラリアまたはニュージーランドの請求先住所を含む新しいテナントについて、Azure AD の顧客データをオーストラリアのデータセンター内に格納し始めました。 2020 年 5 月 1 日から 2020 年 10 月 31 日までの期間に、Microsoft は、オーストラリアまたはニュージーランドの請求先住所が保存された既存のテナントをオーストラリアのデータセンターに移行します。お客様に操作の必要ありません。 移行プロセスは、お客様のダウンタイムを必要とせず、移行中、テナントの機能に影響を与えません。

また、一部の Azure AD 機能では、オーストラリアでの顧客データの格納がまだサポートされていません。 特定の機能の情報については、[Azure AD データ マップ](https://msit.powerbi.com/view?r=eyJrIjoiYzEyZTc5OTgtNTdlZS00ZTVkLWExN2ItOTM0OWU4NjljOGVjIiwidCI6IjcyZjk4OGJmLTg2ZjEtNDFhZi05MWFiLTJkN2NkMDExZGI0NyIsImMiOjV9)に関するページを参照してください。 たとえば、Microsoft Azure Multi-Factor Authentication の場合、顧客データは米国内に格納され、グローバルに処理されます。 「[Azure Multi-Factor Authentication のデータの保存場所と顧客データ](https://docs.microsoft.com/azure/active-directory/authentication/concept-mfa-data-residency)」を参照してください。

> [!NOTE]
> Azure AD と統合される Microsoft の製品およびサービス、ならびにサードパーティのアプリケーションは、顧客データにアクセスすることができます。 使用する製品、サービス、アプリケーションをそれぞれ評価して、その特定の製品、サービス、アプリケーションによる顧客データの処理方法を確認し、それらが会社のデータ ストレージ要件を満たしているかどうかを判断してください。 Microsoft サービスのデータ保存場所の詳細については、Microsoft セキュリティ センターの[データの保存場所](https://www.microsoft.com/trustcenter/privacy/where-your-data-is-located)に関するセクションを参照してください。

