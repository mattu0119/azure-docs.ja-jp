---
title: Live Video Analytics on IoT Edge リリース ノート - Azure
description: このトピックでは、Live Video Analytics on IoT Edge のリリース、機能強化、バグ修正、および既知の問題に関するリリース ノートを提供します。
ms.topic: conceptual
ms.date: 04/27/2020
ms.openlocfilehash: 28260728532d9db52b8d36488c2e456bd11803ea
ms.sourcegitcommit: 3d79f737ff34708b48dd2ae45100e2516af9ed78
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/23/2020
ms.locfileid: "87091781"
---
# <a name="live-video-analytics-on-iot-edge-release-notes"></a>Live Video Analytics on IoT Edge リリース ノート

>この URL (`https://docs.microsoft.com/api/search/rss?search=%22Live+Video+Analytics+on+IoT+Edge+release+notes%22&locale=en-us`) をコピーして、お使いの RSS フィード リーダーに貼り付け、更新内容を確認するためにこのページに再度アクセスするタイミングに関する通知を受け取るようにしてください。

この記事では、次の項目に関する情報を提供します。

* 最新のリリース
* 既知の問題
* バグの修正
* 非推奨の機能

## <a name="july-13-2020"></a>2020 年 7 月 13 日

モジュールの 2020 年 7 月の更新に関するこのリリース タグは次のとおりです。

```
     mcr.microsoft.com/media/live-video-analytics:1.0.2
```

> [!NOTE]
> クイックスタートおよびチュートリアルでは、配置マニフェストで 1 のタグ (live-video-analytics:1) を使用します。 そのため、このようなマニフェストを再配置するだけで、エッジとデバイスでモジュールが更新されます。

### <a name="new-features"></a>新機能
* シグナル ゲート プロセッサ ノードの下流に資産シンク ノードとファイル シンク ノードを持つグラフ トポロジを作成できるようになりました。 例については、[こちら](https://github.com/Azure/live-video-analytics/tree/master/MediaGraph/topologies/evr-motion-assets-files)をご覧ください。

### <a name="bug-fixes"></a>バグの修正
* 必要なプロパティの検証機能の強化

## <a name="june-1-2020"></a>2020 年 6 月 1 日

このリリースは、Live Video Analytics on IoT Edge の最初のパブリック プレビュー リリースです。 リリース タグは、次のとおりです。

```
     mcr.microsoft.com/media/live-video-analytics:1.0.0
```

### <a name="supported-functionalities"></a>サポートされる機能
* AI モジュールを使用してライブ ビデオ ストリームを分析し、必要に応じて、エッジ デバイスまたはクラウドにビデオを記録する
* IoT Edge によって[サポートされている ](../../iot-edge/support.md)Linux AMD64 オペレーティング システム上で使用する
* Azure portal または Visual Studio Code を使用して、IoT Hub 経由でモジュールをデプロイおよび構成する
* 次のダイレクト メソッド呼び出しを使用して、リモートまたはローカルに[グラフ トポロジーおよびグラフ インスタンス](media-graph-concept.md#media-graph-topologies-and-instances)を管理する

    *   GraphTopologyGet
    *   GraphTopologySet
    *   GraphTopologyDelete
    *   GraphTopologyList
    *   GraphInstanceGet
    *   GraphInstanceSet
    *   GraphInstanceDelete
    *   GraphInstanceList


## <a name="next-steps"></a>次のステップ

[概要](overview.md)
