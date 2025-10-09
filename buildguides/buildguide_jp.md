# 組み立てガイド

これは『**_鍵盤で GO!_**』（けんばんで GO!）の組み立てガイドです。

![Kenban-de-go](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/kenban_de_go.png)
![Kenban-de-go-subtitle](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/kenban_de_go_subtitle.png)

## 組み立てタイプ

利用可能な組み立てタイプは以下の 3 種類です：

- MX ビルド
- EC ビルド（OEM スタイル部品使用）
- EC ビルド（Naevies 部品使用）

すべての組み立て例は左側面から見たものです。右側面の組み立ては左側面の鏡像となります。

本ガイドで紹介する組み立て手順は「FR4 ケース」バージョンを前提としています。

_部品を破損させないため、必ず説明書と注意事項をよくご確認ください。_

<details>
  <summary style="font-size:1.1em; font-weight:600;">MXビルド</summary>

## 必要な部品

### 必須部品

| 名称                  | 数量        | 備考                                                            |
| :-------------------- | :---------- | :-------------------------------------------------------------- |
| PCB                   | 1 セット    |                                                                 |
| バックプレート        | 1 セット    |                                                                 |
| MX スイッチ用プレート | 1 セット    |                                                                 |
| キースイッチ          | 42 ～ 46 個 | チェリー MX 互換品のみ使用可能                                  |
| キーキャップ          | 42 ～ 46 個 | 1u サイズ 40 個、1.5u サイズ 2 個                               |
| ケーススペーサー M2   | 8 個        | M2x9mm                                                          |
| ケース用ネジ M2       | 16 本       | M2x5mm（スイッチとの干渉を避けるため、頭部直径 4mm 以下を推奨） |
| ゴム足                | 8 個        |                                                                 |
| TRS/TRRS ケーブル     | 1 本        | TRS（3 極）ケーブルと TRRS（4 極）ケーブルの両方に対応          |
| Type-C ケーブル       | 1 本        |                                                                 |

### オプション部品

| 名称                   | 数量      | 備考                                                                                                                                               |
| :--------------------- | :-------- | :------------------------------------------------------------------------------------------------------------------------------------------------- |
| ロータリーエンコーダー | 0 ～ 4 個 | ロータリーエンコーダー EC12 対応製品                                                                                                               |
| OLED                   | 0 ～ 2 個 | 0.91 インチ 128x32 OLED ディスプレイモジュールとヘッダー（128x64 OLED も使用可能ですが、干渉防止のため別のファームウェアと取り付け位置が必要です） |

## 組み立て手順

### 1: プレートにスペーサーを取り付ける

M2x5mm ネジを使用して、スイッチプレートの指定位置にスペーサーを固定します。

スペーサー用のネジ穴は、プレート上に小さな円形のメッキ貫通穴で示されています。

構築するレイアウトが 3x6 または 3x5 のどちらであるかに応じて、以下の画像に示す適切な穴位置にスペーサーを選択してください（一部の位置はレイアウトに関係なく共通です）。

![mx-spacer-plate-locations](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/mx/mx-spacer-plate-locations.png)

![mx-spacer-plate](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/mx/mx-spacer-plate.png)

### 2: スイッチをプレートと PCB に取り付ける

4 隅の対角線上にあるスイッチをスイッチプレートに挿入し、確実に固定します。

![mx-switch-corners-plate](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/mx/mx-switch-corners-plate.png)

スイッチプレートを PCB と位置合わせし、スイッチが PCB にしっかりと収まるまでしっかりと押し合わせます。

![mx-switch-corners-plate-pcb](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/mx/mx-switch-corners-plate-pcb.png)

その後、残りのスイッチをスイッチプレートと PCB に取り付けます。

![mx-switch-plate-pcb](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/mx/mx-switch-plate-pcb.png)

### 3: 1 と 2 で組み立てたユニットにバックプレートを取り付ける

2 の手順で組み立てたユニットを上下逆さまにし、バックプレートをユニットと位置合わせします。

1 の手順で取り付けたスペーサーの鏡面位置に M2x5mm ネジを使用して、バックプレートをユニットに固定します。

![mx-backplate-assembly](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/mx/mx-backplate-assembly.png)

### 4: ゴム足を取り付ける

バックプレートの指定位置にある 4 隅にゴム足を固定します。

![mx-rubber-feets](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/mx/mx-rubber-feets.png)

### 5: キーキャップを取り付ける

キーキャップをスイッチの上に配置し、確実に固定します。

</details>

<details>
  <summary style="font-size:1.1em; font-weight:600;">EC基板（OEMスタイル部品仕様）</summary>

## 使用部品

### 必須部品

| 部品名称            | 数量        | 備考                                                                                         |
| :------------------ | :---------- | :------------------------------------------------------------------------------------------- |
| PCB 基板            | 1 セット    |                                                                                              |
| バックプレート      | 1 セット    |                                                                                              |
| EC スイッチ基板     | 1 セット    |                                                                                              |
| EC ハウジング       | 42 ～ 46 個 | Topre または OEM スタイルの場合はハウジングの加工が必要（後述） \ Dynacap の場合は加工不要   |
| EC スライダー       | 42 ～ 46 個 | Topre OEM または MX 互換タイプ                                                               |
| EC 静音リング       | 42 ～ 46 個 | より静かな打鍵感を求める場合                                                                 |
| EC ドームスイッチ   | 42 ～ 46 個 | レイアウトに合わせて適切な位置合わせのための切断加工が必要                                   |
| EC スプリング       | 42 ～ 46 個 |                                                                                              |
| キーキャップ        | 42 ～ 46 個 | 1u サイズ 40 個、1.5u サイズ 2 個（スライダー選択に応じて Topre ステムまたは MX タイプ）     |
| ケーススペーサー M2 | 8 個        | M2x9mm                                                                                       |
| ケース用ネジ M2     | 16 本       | M2x5mm（スイッチとの干渉を避けるため頭部直径 4mm 以下を推奨）                                |
| EC 用ネジ M2        | 24 ～ 28 本 | M2x8mm（EC 基板組み立て時の圧縮用。3x5 レイアウトまたは 3x6 レイアウトの場合は本数が異なる） |
| ゴム足              | 8 個        |                                                                                              |
| TRS/TRRS ケーブル   | 1 本        | TRS（3 極）ケーブルと TRRS（4 極）ケーブルの両方に対応                                       |
| Type-C ケーブル     | 1 本        |                                                                                              |

### オプション部品

| 部品名称               | 数量      | 備考                                                                                                                                           |
| :--------------------- | :-------- | :--------------------------------------------------------------------------------------------------------------------------------------------- |
| ロータリーエンコーダー | 0 ～ 4 個 | ロータリーエンコーダー EC12 対応製品                                                                                                           |
| OLED ディスプレイ      | 0 ～ 2 個 | 0.91 インチ 128x32 OLED ディスプレイモジュールとヘッダー（128x64 OLED も使用可能だが、干渉防止のためファームウェアと取り付け方法の変更が必要） |

## EC ハウジングの加工について

Topre または OEM スタイルのハウジングを使用する場合、このキーボードのレイアウトに合わせて加工が必要です。具体的には、圧縮ネジが適切に収まるよう、ハウジングの一部を切断する作業を行います。

以下の画像を参考に、指定箇所を切断する加工を行ってください。

![ec-housing-modification](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-housing-modification.png)

以下の市場向け製品で使用するすべてのハウジングについて、この加工作業を実施する必要があります。

![ec-housing-modification-locations](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-housing-modification-locations.png)

Dynacap ハウジングは十分なクリアランスを確保した設計となっているため、加工は不要です。

## 組み立て手順

### 1: スペーサーをスイッチプレートに取り付ける

M2x5mm ネジを使用して、スイッチプレートの指定位置にスペーサーを固定します。

スペーサー用のネジ穴は、プレート上に小さな円形のメッキ貫通穴として表示されています。

構築するレイアウトが 3x6 か 3x5 かに応じて、以下の画像に示す適切な穴位置にスペーサーを選択してください（一部の位置はレイアウトに関係なく共通です）。

![ec-spacer-plate-locations](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-spacer-plate-locations.png)

![ec-spacer-plate](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-spacer-plate.png)

### 2: EC ハウジングをスイッチプレートに取り付ける

手順 1 で組み立てた部品を上下反転させ、スイッチプレートの全位置に EC ハウジングを挿入し、確実に固定します。

![ec-housings-plate](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-housings-plate.png)

ハウジングの向きに注意してください。ハウジングの小さな側面の円形切り欠きは、下図のように左右両側に位置するようにしてください。

![ec-housings-plate-orientation](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-housings-plate-orientation.png)

### 3: 手順 2 の組み立て部品を固定し、EC スライダーを挿入する

手順 2 の組み立て部品は、EC スライダーをハウジングに「自由落下」させるように（スライダーが自由に落ちるように）持ち上げておく必要があります。これにより、後でドームとスプリングの適切な位置合わせが確保されます。

その後、EC スライダーをハウジングに挿入します。タイピング時の静音性を高めたい場合は、スライダーを挿入する前にこの段階で静音リングも取り付けることができます。

![ec-sliders](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-sliders.png)

### 4: ドームを配置する

レイアウトに合わせてドームを適切な位置にカットする必要があります。カット部分は下図に示されています（ここでは 1x4 ドームストリップを想定しています。異なる構成を使用する場合は、適宜調整してください）。

![ec-domes-cut](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-domes-cut.png)

その後、ドームをハウジングの上に配置し、ハウジングの切り欠きと正しく位置合わせされていることを確認します。

![ec-domes](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-domes.png)

### 5: スプリングを配置する

ドームの上にスプリングを置き、中心に配置して傾かないようにします

![ec-springs](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-springs.png)

以下の画像では、スプリングをより見やすくするために強調表示しています。側面から見た場合、スプリングが傾いていないことに注意してください。

![ec-springs-profile](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-springs-profile.png)

### 6: PCB を組み立て部品の上に配置する

_この工程は繊細な作業ですので、慎重に落ち着いて行ってください_

PCB を組み立て部品と正確に位置合わせし、PCB が組み立て部品と正しく整列していることを確認してください。
この工程では組み立て部品を圧縮する必要がある場合がありますので、焦らずに時間をかけて作業してください。

この時点で、片手で組み立て部品をしっかりと押さえながらプレートと PCB を密着させ、もう一方の手で M2x8mm ネジを指定された穴に挿入し、プレート側から PCB を組み立て部品に固定します。

まず 4 隅のネジから始め、残りのネジを順次取り付けます。4 隅のネジが固定できたら、残りのネジの取り付けに進んでください。

![ec-pcb-assembly](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-pcb-assembly-play.png)

以下の GIF は、組み立て部品を圧縮してネジを取り付ける工程を示しています。

<p align="center">
  <img src="https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-pcb-assembly.gif" alt="EC PCB組み立て" style="display:block; margin:0 auto;" loading="eager" />
</p>

### 7: バックプレートを手順 6 の組み立て部品に取り付ける

手順 6 で組み立てた部品を上下反転させ、バックプレートを組み立て部品と位置合わせし、手順 1 で取り付けたスペーサーの鏡面位置に M2x5mm ネジを使用してバックプレートを組み立て部品に固定します。

![ec-backplate-assembly](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-backplate-assembly.png)

### 8: ゴム足を取り付ける

バックプレートの指定位置にゴム足を取り付けます。

![ec-rubber-feets](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-rubber-feets.png)

### 9: キーキャップを取り付ける

キーキャップをスイッチの上に置き、しっかりと固定されていることを確認します。

</details>

## オプション改造

<details>
<summary style="font-size:1.1em; font-weight:600;">オプション①：3x5キー配列への変更</summary>

3x5 キー配列を採用したい場合、スイッチプレートと PCB を適切に改造する必要があります。キーボードの片面または両面のいずれかでこの改造を行うことが可能です。

スイッチプレートの最外周列は切り離す必要があります。

**重要**：この改造は元に戻すことができないため、十分に注意して作業を行ってください。

![3x5配列プレート切断](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/3x5-layout-plate-snap.png)

PCB を切断する前に、その列に接続されているスイッチ用の配線をナイフやカッターで切断してください。これにより、改造後の電気的不具合を防ぐことができます。

![3x5配列PCB切断](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/3x5-layout-pcb-cut.png)

配線を切断したら、PCB の最外周列を切り離します。

</details>

<details>
<summary style="font-size:1.1em; font-weight:600;">オプション②：スイッチの代わりにロータリーエンコーダを半田付け</summary>

ロータリーエンコーダを使用する場合、以下のいずれかまたは両方の位置にスイッチの代わりに取り付けることが可能です。この場合、裏面からの半田付けが必要となります。

![ロータリーエンコーダ取り付け位置（PCB上面）](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/rotary-encoder-location-pcb-top.png)

![ロータリーエンコーダ取り付け位置（PCB下面）](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/rotary-encoder-location-pcb-bottom.png)

</details>

<details>
<summary style="font-size:1.1em; font-weight:600;">オプション③：スイッチの代わりにOLEDを半田付け</summary>

OLED を使用する場合、この位置にスイッチの代わりに取り付けることが可能です。この場合も裏面からの半田付けが必要となります。

![OLED取り付け位置（PCB）](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/oled-location-pcb.png)

また、OLED を取り付けるためにプレートの一部を切断する必要があります。

![プレート切断（OLED用スペース確保）](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/plate-snap-oled.png)

将来的な OLED の交換を容易にするため、メス型ピンヘッダ（1x4）の使用をお勧めします。

![OLED用ヘッダ（上面）](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/oled-header-top.png)

![OLED用ヘッダ（下面）](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/oled-header-bottom.png)

![OLEDモジュール](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/oled.png)

さらに、専用ケースの製作や追加の DIY 作業が必要になりますが、OLED の 4 ピンをケースの側面にフライングワイヤで引き出すことで、スイッチ/エンコーダと OLED を同時に使用することも可能です。

</details>

## ファームウェア

### 配列とスイッチタイプの選択

<details>
  <summary style="font-size:1.1em; font-weight:400;">配列選択</summary>

組み立てが完了したら、必ず使用した配列とスイッチタイプを選択してください。デフォルトでは基板は EC モードに設定されています。

[VIA](https://www.usevia.app/)を使用することで、簡単に配列設定やキー割り当てを構成できます。

</details>

<details>
  <summary style="font-size:1.1em; font-weight:400;">スイッチタイプ選択</summary>

EC ビルドを使用する場合、組み立て後に基板のキャリブレーションを行う必要があります。

この作業は、キーが正常に動作しているように見えても、全てのキーが正しく機能することを保証するために必須です。

キャリブレーション手順については、以下のガイドを参照してください：[EC PCB キャリブレーション](https://cipulot.squarespace.com/guides#:~:text=Notion%20Webpage-,EC%20PCB%20Calibration,-Brief%20video%20guide)

</details>

## 重要な注意事項

**<u>USB ケーブルが接続されている状態で TRRS ケーブルの抜き差しを行わないでください！</u>**

USB ケーブルが接続されている状態で TRRS ケーブルを接続・切断すると、キーボードのマイクロコントローラが損傷する可能性があります。
TRRS ケーブルの接続・切断を行う際は、必ず USB ケーブルを取り外してから作業してください。

## お問い合わせ

ご質問やサポートが必要な場合は、私の[Discord サーバー](https://discord.gg/YKZSqHG8bJ)またはプロフェッショナル向けウェブサイト[Cipulot PCB Design](https://www.lusvsolutions.com/contact)までお気軽にお問い合わせください。
