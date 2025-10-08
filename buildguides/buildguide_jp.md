# ビルドガイド

これは **_鍵盤で GO!_** (けんばんで GO!, Kenban de GO!) のビルドガイドです。

![Kenban-de-go](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/kenban_de_go.png)
![Kenban-de-go-subtitle](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/kenban_de_go_subtitle.png)

## 組み立てタイプ

以下の 3 つの組み立てタイプが利用可能です：

- MX ビルド
- EC ビルド (OEM スタイルパーツ)
- EC ビルド (Naevies パーツ)

すべてのビルド例は左手側を示しています。右手側の組み立ては左手側の鏡像となります。

このガイドで紹介されている組み立てプロセスは「FR4 ケース」バージョンを参照しています。

_部品の損傷を避けるため、説明と注意事項に注意してください。_

<details>
  <summary style="font-size:1.1em; font-weight:600;">MX ビルド</summary>

## パーツ

### 必須パーツ

| 名前                | 数量     | 備考                                                |
| :------------------ | :------- | :-------------------------------------------------- |
| PCB                 | 1 セット |                                                     |
| バックプレート      | 1 セット |                                                     |
| MX スイッチプレート | 1 セット |                                                     |
| キースイッチ        | 42 - 46  | Cherry MX 互換のみ                                  |
| キーキャップ        | 42 - 46  | 1u 40 個, 1.5u 2 個                                 |
| ケーススペーサー M2 | 8        | M2x9mm                                              |
| ケースネジ M2       | 16       | M2x5mm (スイッチとの干渉回避のため最大 ⌀4mm ヘッド) |
| ゴム足              | 8        |                                                     |
| TRS/TRRS ケーブル   | 1        | TRS (3 極) と TRRS (4 極) ケーブルの両方に対応      |
| Type-C ケーブル     | 1        |                                                     |

### オプションパーツ

| 名前                   | 数量     | 備考                                                                                                                                                  |
| :--------------------- | :------- | :---------------------------------------------------------------------------------------------------------------------------------------------------- |
| ロータリーエンコーダー | 0 - 4 個 | ロータリーエンコーダー EC12 互換製品                                                                                                                  |
| OLED                   | 0 - 2 個 | 0.91 インチ 128x32 OLED 表示モジュールとヘッダー (128x64 OLED もサポートされていますが、異なるファームウェアと干渉回避のための取り付け方法が必要です) |

## 組み立て手順

### 1: プレートにスペーサーを取り付ける

M2x5mm ネジを使用して、スペーサーをスイッチプレートの指定された穴に固定します。

スペーサー用のネジ穴は、プレート上の小さな円形のメッキスルーホールでマークされています。

組み立てるレイアウト（3x6 または 3x5）に基づいて、以下の画像のようにスペーサー用の適切な穴を選択する必要があります（一部の位置はレイアウトに関係なく共有されています）。

![mx-spacer-plate-locations](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/mx/mx-spacer-plate-locations.png)

![mx-spacer-plate](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/mx/mx-spacer-plate.png)

### 2: プレートと PCB にスイッチを取り付ける

4 つの対角のスイッチをスイッチプレートに挿入し、確実に固定されていることを確認します。

![mx-switch-corners-plate](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/mx/mx-switch-corners-plate.png)

スイッチプレートを PCB に合わせ、スイッチが PCB に完全に装着されるまで強く押し込みます。

![mx-switch-corners-plate-pcb](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/mx/mx-switch-corners-plate-pcb.png)

その後、残りのスイッチをスイッチプレートと PCB に取り付けます。

![mx-switch-plate-pcb](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/mx/mx-switch-plate-pcb.png)

### 3: バックプレートをステップ 1 と 2 のアセンブリに取り付ける

ステップ 2 のアセンブリを裏返し（裏面が上になるように）、バックプレートをアセンブリに合わせます。

ステップ 1 でスペーサーを取り付けた位置の鏡像位置で M2x5mm ネジを使用して、バックプレートをアセンブリに固定します。

![mx-backplate-assembly](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/mx/mx-backplate-assembly.png)

### 4: ゴム足を取り付ける

ゴム足をバックプレートの指定されたコーナーに貼り付けます。

![mx-rubber-feets](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/mx/mx-rubber-feets.png)

### 5: キーキャップを取り付ける

キーキャップをスイッチの上に置き、確実に装着されていることを確認します。

</details>

<details>
  <summary style="font-size:1.1em; font-weight:600;">EC ビルド (OEMスタイルパーツ)</summary>

## パーツ

### 必須パーツ

| 名前                    | 数量     | 備考                                                                                                                             |
| :---------------------- | :------- | :------------------------------------------------------------------------------------------------------------------------------- |
| PCB                     | 1 セット |                                                                                                                                  |
| バックプレート          | 1 セット |                                                                                                                                  |
| EC スイッチプレート     | 1 セット |                                                                                                                                  |
| EC ハウジング           | 42 - 46  | Topre または OEM スタイルはハウジングの修正が必要（後述） \ Dynacap は修正不要                                                   |
| EC スライダー           | 42 - 46  | Topre OEM または MX 互換                                                                                                         |
| EC サイレンシングリング | 42 - 46  | より静かなタイピング体験を希望する場合                                                                                           |
| EC ドーム               | 42 - 46  | レイアウトのため正しい位置合わせのためにカットが必要                                                                             |
| EC スプリング           | 42 - 46  |                                                                                                                                  |
| キーキャップ            | 42 - 46  | 1u 40 個, 1.5u 2 個 (スライダーの選択に応じて Topre ステムまたは MX)                                                             |
| ケーススペーサー M2     | 8        | M2x9mm                                                                                                                           |
| ケースネジ M2           | 16       | M2x5mm (スイッチとの干渉回避のため最大 ⌀4mm ヘッド)                                                                              |
| EC ネジ M2              | 24 - 28  | M2x8mm (スイッチとの干渉回避のため最大 ⌀4mm ヘッド) EC アセンブリの圧縮用。3x5 または 3x6 レイアウトの選択により数が異なります。 |
| ゴム足                  | 8        |                                                                                                                                  |
| TRS/TRRS ケーブル       | 1        | TRS (3 極) と TRRS (4 極) ケーブルの両方に対応                                                                                   |
| Type-C ケーブル         | 1        |                                                                                                                                  |

### オプションパーツ

| 名前                   | 数量     | 備考                                                                                                                                                  |
| :--------------------- | :------- | :---------------------------------------------------------------------------------------------------------------------------------------------------- |
| ロータリーエンコーダー | 0 - 4 個 | ロータリーエンコーダー EC12 互換製品                                                                                                                  |
| OLED                   | 0 - 2 個 | 0.91 インチ 128x32 OLED 表示モジュールとヘッダー (128x64 OLED もサポートされていますが、異なるファームウェアと干渉回避のための取り付け方法が必要です) |

## EC ハウジングの修正

Topre または OEM スタイルのハウジングを使用する場合、このキーボードのレイアウトに合わせて修正する必要があります。修正には、圧縮ネジの適切なクリアランスとフィットを確保するためにハウジングの一部をカットすることが含まれます。

以下の画像に示すように、指示された部分をカットしてハウジングを修正します。

![ec-housing-modification](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-housing-modification.png)

以下のマークされた位置で使用するすべてのハウジングに対してこの修正を行う必要があります：

![ec-housing-modification-locations](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-housing-modification-locations.png)

Dynacap ハウジングは十分なクリアランスで設計されているため、修正は必要ありません。

## 組み立て手順

### 1: プレートにスペーサーを取り付ける

M2x5mm ネジを使用して、スペーサーをスイッチプレートの指定された穴に固定します。

スペーサー用のネジ穴は、プレート上の小さな円形のメッキスルーホールでマークされています。

組み立てるレイアウト（3x6 または 3x5）に基づいて、以下の画像のようにスペーサー用の適切な穴を選択する必要があります（一部の位置はレイアウトに関係なく共有されています）。

![ec-spacer-plate-locations](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-spacer-plate-locations.png)

![ec-spacer-plate](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-spacer-plate.png)

### 2: EC ハウジングをプレートに取り付ける

ステップ 1 のアセンブリを裏返し（裏面が上になるように）、EC ハウジングをスイッチプレートのすべての位置に挿入し、確実に固定されていることを確認します。

![ec-housings-plate](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-housings-plate.png)

ハウジングの向きに注意してください。ハウジングの小さな側面の円形カットアウトは、以下の画像のように左右の側面にある必要があります。

![ec-housings-plate-orientation](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-housings-plate-orientation.png)

### 3: ステップ 2 のアセンブリを支え、EC スライダーを挿入する

ステップ 2 のアセンブリは、EC スライダーがハウジングに「自由落下」方式で挿入できるように支える必要があります（つまり、スライダーが自由に落ちるように）。これにより、後でドームとスプリングの適切な位置合わせが保証されます。

その後、EC スライダーをハウジングに挿入します。より静かなタイピング体験を希望する場合は、スライダーを挿入する前にこの段階でサイレンシングリングも挿入できます。

![ec-sliders](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-sliders.png)

### 4: ドームを配置する

レイアウトのため、ドームを正しい位置合わせのためにカットする必要があります。カット部分は以下の画像で示されています（ここでは 1x4 ドームストリップを想定しています。異なる構成を使用する場合は適宜調整してください）。

![ec-domes-cut](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-domes-cut.png)

その後、ドームをハウジングの上に配置し、ハウジングのノッチと正しく位置合わせされていることを確認します。

![ec-domes](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-domes.png)

### 5: スプリングを配置する

ドームの上にスプリングを置き、中心にあり傾いていないことを確認します。

![ec-springs](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-springs.png)

以下の画像は、スプリングをより見やすくするために強調表示しています。側面図でスプリングが傾いていないことに注意してください。

![ec-springs-profile](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-springs-profile.png)

### 6: PCB をアセンブリの上に置く

_このステップは繊細なので、注意深く冷静に進めてください！_

PCB をアセンブリと慎重に位置合わせし、PCB がアセンブリと正しく位置合わせされていることを確認します。
このステップではアセンブリを圧縮するのに多少の力が必要な場合があるので、忍耐強く時間をかけて行ってください。

この時点で、片手でアセンブリをしっかりと掴み、プレートと PCB を一緒に圧縮します。もう一方の手で M2x8mm ネジを指定された穴に挿入し、プレート側から PCB をアセンブリに固定します。

4 つのコーナーのネジから始め、その後残りのネジを進めます。4 つのコーナーが固定されたら、残りのネジを追加できます。

![ec-pcb-assembly](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-pcb-assembly-play.png)

ここに、アセンブリを圧縮しネジを挿入するプロセスを示す GIF があります。

![ec-pcb-assembly-gif](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-pcb-assembly.gif)

### 7: バックプレートをステップ 6 のアセンブリに取り付ける

ステップ 6 のアセンブリを裏返し（裏面が上になるように）、バックプレートをアセンブリに合わせます。その後、ステップ 1 で取り付けたスペーサーの位置の鏡像位置で M2x5mm ネジを使用して、バックプレートをアセンブリに固定します。

![ec-backplate-assembly](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-backplate-assembly.png)

### 8: ゴム足を取り付ける

ゴム足をバックプレートの指定されたコーナーに貼り付けます。

![ec-rubber-feets](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-rubber-feets.png)

### 9: キーキャップを取り付ける

キーキャップをスイッチの上に置き、確実に装着されていることを確認します。

</details>

## オプション改造

<details>
<summary style="font-size:1.1em; font-weight:600;">オプション #1: 3x5 キーレイアウト</summary>

3x5 キーレイアウトを使用したい場合は、スイッチプレートと PCB をそれに応じて修正できます。この修正はキーボードの片側または両側で行うことができます。

スイッチプレートの最も外側の列を折り取る必要があります。

**注意**: この修正は元に戻せないので、注意して進めてください。

![3x5-layout-plate-snap](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/3x5-layout-plate-snap.png)

PCB を折る前に、ナイフまたはカッターを使用してその列のスイッチに接続されているトレースをカットしてください。これは修正後の電気的問題を防ぐためです。

![3x5-layout-pcb-cut](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/3x5-layout-pcb-cut.png)

トレースをカットした後、PCB の最も外側の列を折り取ることができます。

</details>

<details>
<summary style="font-size:1.1em; font-weight:600;">オプション #2: スイッチの代わりにロータリーエンコーダーをはんだ付け</summary>

ロータリーエンコーダーを使用する場合、スイッチの代わりに*以下の位置のいずれかまたは両方*に取り付けることができます。その場合、裏面からのはんだ付けが必要です。

![rotary-encoder-location-pcb-top](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/rotary-encoder-location-pcb-top.png)

![rotary-encoder-location-pcb-bottom](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/rotary-encoder-location-pcb-bottom.png)

</details>

<details>
<summary style="font-size:1.1em; font-weight:600;">オプション #3: スイッチの代わりにOLEDをはんだ付け</summary>

OLED を使用する場合、スイッチの代わりにこの位置に取り付けることができます。その場合、裏面からのはんだ付けが必要です。

![oled-location-pcb](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/oled-location-pcb.png)

また、OLED 用のスペースを作るためにプレートの一部を折り取る必要があります。

![plate-snap-oled](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/plate-snap-oled.png)

将来の OLED 交換を容易にするために、メスピンヘッダー（1x4）の使用を推奨します。

![oled-header-top](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/oled-header-top.png)

![oled-header-bottom](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/oled-header-bottom.png)

![oled](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/oled.png)

さらに、これはカスタムケースとより多くの DIY 作業が必要になりますが、フライングワイヤーを通じて OLED の 4 本のピンをケースの側面に引き出すことで、スイッチ/エンコーダーと OLED を一緒に使用できます。

</details>

## ファームウェア

### レイアウトとスイッチタイプの選択

<details>
  <summary style="font-size:1.1em; font-weight:400;">レイアウト選択</summary>

組み立てが完了したら、使用したレイアウトとスイッチタイプを**必ず**選択してください。デフォルトではボードは EC モードに設定されています。

[VIA](https://www.usevia.app/)を使用して、レイアウトとキー割り当てを簡単に設定できます。

</details>

<details>
  <summary style="font-size:1.1em; font-weight:400;">スイッチタイプ選択</summary>

使用したスイッチタイプを選択するには、`Hybrid Tools` -> `Actuation`タブの`Switch Type`ドロップダウンメニューから適切なオプション（`MX`または`EC`）を選択します。

![via-switch-type](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/via-switch-type.png)

</details>

### EC キャリブレーション

EC ビルドを使用している場合、組み立て後にボードをキャリブレーションする必要があります。

このプロセスはボードの適切な機能を保証するために必要です（キーが動作しているように見えても、すべてのキーが正しく動作することが保証されるわけではありません）。

キャリブレーションプロセスについては、以下のガイドを参照してください：[EC PCB キャリブレーション](https://cipulot.squarespace.com/guides#:~:text=Notion%20Webpage-,EC%20PCB%20Calibration,-Brief%20video%20guide)

## 重要な注意点

**<u>USB ケーブルが接続されている間に TRRS ケーブルを接続または切断しないでください！</u>**

USB ケーブルが接続されている間に TRRS ケーブルを抜き差しすると、キーボードのマイクロコントローラーが損傷する可能性があります。
TRRS ケーブルを抜き差しする前は、常に USB ケーブルが切断されていることを確認してください。

## 連絡先

ご質問やサポートが必要な場合は、[Discord サーバー](https://discord.gg/YKZSqHG8bJ)またはプロフェッショナルウェブサイト[Cipulot PCB Design](https://www.lusvsolutions.com/contact)を通じてお気軽にお問い合わせください。
