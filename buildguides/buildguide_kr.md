# 빌드 가이드

これは **_鍵盤で GO!_** (けんばんで GO!, Kenban de GO!) 의 빌드 가이드입니다.

![Kenban-de-go](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/kenban_de_go.png)
![Kenban-de-go-subtitle](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/kenban_de_go_subtitle.png)

## 조립 타입

세 가지 조립 타입이 가능합니다:

- MX 빌드
- EC 빌드 (OEM 스타일 부품)
- EC 빌드 (Naevies 부품)

모든 빌드 예시는 왼손 측면입니다. 오른손 측면 조립은 왼손 측면의 미러 이미지입니다.

본 가이드에서 보여지는 빌드 과정은 "FR4 케이스" 버전을 참조합니다.

_부품 손상을 방지하기 위해 지시사항과 주의사항에 주의해 주세요._

<details>
  <summary style="font-size:1.1em; font-weight:600;">MX 빌드</summary>

## 부품

### 필수 부품

| 이름               | 개수    | 비고                                              |
| :----------------- | :------ | :------------------------------------------------ |
| PCB                | 1 세트  |                                                   |
| 백플레이트         | 1 세트  |                                                   |
| MX 스위치 플레이트 | 1 세트  |                                                   |
| 키 스위치          | 42 - 46 | Cherry MX 호환만 가능                             |
| 키캡               | 42 - 46 | 1u 40개, 1.5u 2개                                 |
| 케이스 스페이서 M2 | 8       | M2x9mm                                            |
| 케이스 나사 M2     | 16      | M2x5mm (스위치와 간섭 방지를 위해 최대 ⌀4mm 헤드) |
| 고무 발            | 8       |                                                   |
| TRS/TRRS 케이블    | 1       | TRS (3극) 및 TRRS (4극) 케이블 모두 호환          |
| Type-C 케이블      | 1       |                                                   |

### 선택 부품

| 이름          | 개수     | 비고                                                                                                             |
| :------------ | :------- | :--------------------------------------------------------------------------------------------------------------- |
| 로터리 엔코더 | 0 - 4 개 | 로터리 엔코더 EC12 호환 제품                                                                                     |
| OLED          | 0 - 2 개 | 0.91" 128x32 OLED 디스플레이 모듈 및 헤더 (128x64 OLED 지원되지만 다른 펌웨어와 간섭 회피를 위한 장착 방법 필요) |

## 조립 단계

### 1: 플레이트에 스페이서 부착

M2x5mm 나사를 사용하여 스페이서를 스위치 플레이트의 지정된 구멍에 고정합니다.

스페이서용 나사 구멍은 플레이트의 작은 원형 도금 스루홀로 표시되어 있습니다.

빌드하는 레이아웃(3x6 또는 3x5)에 따라 아래 이미지와 같이 스페이서를 위한 적절한 구멍을 선택해야 합니다 (일부 위치는 레이아웃에 관계없이 공유됩니다).

![mx-spacer-plate-locations](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/mx/mx-spacer-plate-locations.png)

![mx-spacer-plate](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/mx/mx-spacer-plate.png)

### 2: 플레이트와 PCB에 스위치 부착

4개의 대각선 모서리 스위치를 스위치 플레이트에 삽입하여 단단히 고정되었는지 확인합니다.

![mx-switch-corners-plate](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/mx/mx-switch-corners-plate.png)

스위치 플레이트를 PCB와 정렬하고 스위치가 PCB에 완전히 장착될 때까지 단단히 눌러 결합합니다.

![mx-switch-corners-plate-pcb](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/mx/mx-switch-corners-plate-pcb.png)

그 후, 나머지 스위치를 스위치 플레이트와 PCB에 장착합니다.

![mx-switch-plate-pcb](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/mx/mx-switch-plate-pcb.png)

### 3: 백플레이트를 1과 2의 조립체에 부착

2단계의 조립체를 뒤집어(뒷면이 위로 오도록) 백플레이트를 조립체와 정렬합니다.

1단계에서 스페이서를 부착한 위치의 대칭 위치에 M2x5mm 나사를 사용하여 백플레이트를 조립체에 고정합니다.

![mx-backplate-assembly](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/mx/mx-backplate-assembly.png)

### 4: 고무 발 부착

고무 발을 백플레이트의 지정된 모서리에 부착합니다.

![mx-rubber-feets](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/mx/mx-rubber-feets.png)

### 5: 키캡 부착

키캡을 스위치 위에 놓고 단단히 장착되었는지 확인합니다.

</details>

<details>
  <summary style="font-size:1.1em; font-weight:600;">EC 빌드 (OEM 스타일 부품)</summary>

## 부품

### 필수 부품

| 이름               | 개수    | 비고                                                                                                                        |
| :----------------- | :------ | :-------------------------------------------------------------------------------------------------------------------------- |
| PCB                | 1 세트  |                                                                                                                             |
| 백플레이트         | 1 세트  |                                                                                                                             |
| EC 스위치 플레이트 | 1 세트  |                                                                                                                             |
| EC 하우징          | 42 - 46 | Topre 또는 OEM 스타일은 하우징 수정 필요 (나중에 표시) \ Dynacap은 수정 불필요                                              |
| EC 슬라이더        | 42 - 46 | Topre OEM 또는 MX 호환                                                                                                      |
| EC 무음 링         | 42 - 46 | 더 조용한 타이핑 경험을 원할 경우                                                                                           |
| EC 돔              | 42 - 46 | 레이아웃 때문에 정확한 정렬을 위해 커팅 필요                                                                                |
| EC 스프링          | 42 - 46 |                                                                                                                             |
| 키캡               | 42 - 46 | 1u 40개, 1.5u 2개 (슬라이더 선택에 따라 Topre 스템 또는 MX)                                                                 |
| 케이스 스페이서 M2 | 8       | M2x9mm                                                                                                                      |
| 케이스 나사 M2     | 16      | M2x5mm (스위치와 간섭 방지를 위해 최대 ⌀4mm 헤드)                                                                           |
| EC 나사 M2         | 24 - 28 | M2x8mm (스위치와 간섭 방지를 위해 최대 ⌀4mm 헤드) EC 조립체의 압축 고정용. 선택한 3x5 또는 3x6 레이아웃에 따라 개수가 다름. |
| 고무 발            | 8       |                                                                                                                             |
| TRS/TRRS 케이블    | 1       | TRS (3극) 및 TRRS (4극) 케이블 모두 호환                                                                                    |
| Type-C 케이블      | 1       |                                                                                                                             |

### 선택 부품

| 이름          | 개수     | 비고                                                                                                             |
| :------------ | :------- | :--------------------------------------------------------------------------------------------------------------- |
| 로터리 엔코더 | 0 - 4 개 | 로터리 엔코더 EC12 호환 제품                                                                                     |
| OLED          | 0 - 2 개 | 0.91" 128x32 OLED 디스플레이 모듈 및 헤더 (128x64 OLED 지원되지만 다른 펌웨어와 간섭 회피를 위한 장착 방법 필요) |

## EC 하우징 수정

Topre 또는 OEM 스타일 하우징을 사용하는 경우, 이 키보드의 레이아웃에 맞게 수정해야 합니다. 수정은 압축 나사를 위한 적절한 클리어런스와 맞춤을 보장하기 위해 하우징의 일부를 커팅하는 것을 포함합니다.

아래 이미지와 같이 표시된 부분을 커팅하여 하우징을 수정합니다.

![ec-housing-modification](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-housing-modification.png)

다음 표시된 위치에서 사용할 모든 하우징에 대해 이 수정을 해야 합니다:

![ec-housing-modification-locations](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-housing-modification-locations.png)

Dynacap 하우징은 충분한 클리어런스로 설계되어 있어 어떠한 수정도 필요하지 않습니다.

## 조립 단계

### 1: 플레이트에 스페이서 부착

M2x5mm 나사를 사용하여 스페이서를 스위치 플레이트의 지정된 구멍에 고정합니다.

스페이서용 나사 구멍은 플레이트의 작은 원형 도금 스루홀로 표시되어 있습니다.

빌드하는 레이아웃(3x6 또는 3x5)에 따라 아래 이미지와 같이 스페이서를 위한 적절한 구멍을 선택해야 합니다 (일부 위치는 레이아웃에 관계없이 공유됩니다).

![ec-spacer-plate-locations](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-spacer-plate-locations.png)

![ec-spacer-plate](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-spacer-plate.png)

### 2: EC 하우징을 플레이트에 부착

1단계의 조립체를 뒤집어(뒷면이 위로 오도록) EC 하우징을 스위치 플레이트의 모든 위치에 삽입하여 단단히 고정되었는지 확인합니다.

![ec-housings-plate](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-housings-plate.png)

하우징의 방향에 유의하십시오. 하우징의 작은 측면 원형 컷아웃은 아래 이미지와 같이 좌우 측면에 위치해야 합니다.

![ec-housings-plate-orientation](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-housings-plate-orientation.png)

### 3: 2단계 조립체를 받치고 EC 슬라이더 삽입

2단계의 조립체는 EC 슬라이더가 하우징에 "자유 낙하" 방식으로 삽입될 수 있도록 받쳐져야 합니다(즉, 슬라이더가 자유롭게 떨어지도록). 이는 이후 돔과 스프링의 적절한 정렬을 보장합니다.

그 후, EC 슬라이더를 하우징에 삽입합니다. 더 조용한 타이핑 경험을 원한다면, 슬라이더를 삽입하기 전에 이 단계에서 무음 링도 삽입할 수 있습니다.

![ec-sliders](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-sliders.png)

### 4: 돔 놓기

레이아웃 때문에 돔을 정확한 정렬을 위해 커팅해야 합니다. 커팅 부분은 아래 이미지에 표시되어 있습니다 (여기서는 1x4 돔 스트립을 가정합니다. 다른 구성을 사용하는 경우 이에 맞게 조정하십시오).

![ec-domes-cut](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-domes-cut.png)

그 후, 돔을 하우징 위에 놓고 하우징 노치와 올바르게 정렬되었는지 확인합니다.

![ec-domes](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-domes.png)

### 5: 스프링 놓기

돔 위에 스프링을 놓고 중앙에 위치하며 기울어지지 않았는지 확인합니다.

![ec-springs](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-springs.png)

다음 이미지는 스프링을 더 잘 보이도록 강조 표시했습니다. 측면 뷰에서 스프링이 기울어지지 않았음을 확인하십시오.

![ec-springs-profile](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-springs-profile.png)

### 6: 조립체 위에 PCB 놓기

_이 단계는 섬세하므로 신중하고 차분하게 진행해 주세요!_

PCB를 조립체와 조심스럽게 정렬하여 PCB가 조립체와 올바르게 정렬되었는지 확인합니다.
이 단계는 조립체를 압축하는 데 약간의 힘이 필요할 수 있으므로 인내심을 가지고 시간을 갖어 진행해 주세요.

이때 한 손으로 조립체를 단단히 잡고 플레이트와 PCB를 함께 압축한 상태에서, 다른 손으로 M2x8mm 나사를 지정된 구멍에 플레이트 측에서 PCB를 조립체에 고정하도록 삽입합니다.

4개의 모서리 나사부터 시작한 후 나머지 나사를 진행합니다. 4개의 모서리가 고정되면 나머지 나사를 추가할 수 있습니다.

![ec-pcb-assembly](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-pcb-assembly-play.png)

여기 조립체를 압축하고 나사를 삽입하는 과정을 보여주는 GIF가 있습니다.

<p align="center">
  <img src="https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-pcb-assembly.gif" alt="EC PCB assembly" style="display:block; margin:0 auto;" loading="eager" />
</p>

### 7: 백플레이트를 6단계 조립체에 부착

6단계의 조립체를 뒤집어(뒷면이 위로 오도록) 백플레이트를 조립체와 정렬한 다음, 1단계에서 부착한 스페이서 위치의 대칭 위치에 M2x5mm 나사를 사용하여 백플레이트를 조립체에 고정합니다.

![ec-backplate-assembly](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-backplate-assembly.png)

### 8: 고무 발 부착

고무 발을 백플레이트의 지정된 모서리에 부착합니다.

![ec-rubber-feets](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-rubber-feets.png)

### 9: 키캡 부착

키캡을 스위치 위에 놓고 단단히 장착되었는지 확인합니다.

</details>

## 선택적 수정

<details>
<summary style="font-size:1.1em; font-weight:600;">선택 #1: 3x5 키 레이아웃</summary>

3x5 키 레이아웃을 사용하려면 스위치 플레이트와 PCB를 그에 맞게 수정할 수 있습니다. 키보드의 한쪽 또는 양쪽 모두에서 이 수정을 선택할 수 있습니다.

스위치 플레이트의 가장 바깥쪽 열을 떼어내야 합니다.

**참고**: 이 수정은 되돌릴 수 없으므로 신중하게 진행하십시오.

![3x5-layout-plate-snap](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/3x5-layout-plate-snap.png)

PCB를 떼어내기 전에, 나이프나 커터를 사용하여 해당 열의 스위치에 연결된 트레이스를 커팅해야 합니다. 이는 수정 후 발생할 수 있는 전기적 문제를 방지하기 위함입니다.

![3x5-layout-pcb-cut](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/3x5-layout-pcb-cut.png)

트레이스를 커팅한 후 PCB의 가장 바깥쪽 열을 떼어낼 수 있습니다.

</details>

<details>
<summary style="font-size:1.1em; font-weight:600;">선택 #2: 스위치 대신 로터리 엔코더 납땜</summary>

로터리 엔코더를 사용하는 경우, 스위치 대신 *다음 위치 중 하나 또는 모두*에 부착할 수 있습니다. 이 경우, 뒷면에서 납땜이 필요합니다.

![rotary-encoder-location-pcb-top](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/rotary-encoder-location-pcb-top.png)

![rotary-encoder-location-pcb-bottom](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/rotary-encoder-location-pcb-bottom.png)

</details>

<details>
<summary style="font-size:1.1em; font-weight:600;">선택 #3: 스위치 대신 OLED 납땜</summary>

OLED를 사용하는 경우, 스위치 대신 이 위치에 부착할 수 있습니다. 이 경우, 뒷면에서 납땜이 필요합니다.

![oled-location-pcb](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/oled-location-pcb.png)

또한 OLED를 위한 공간을 마련하기 위해 플레이트의 일부를 떼어내야 합니다.

![plate-snap-oled](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/plate-snap-oled.png)

향후 OLED 교체를 쉽게 하기 위해 암 핀 헤더(1x4)를 사용하는 것을 권장합니다.

![oled-header-top](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/oled-header-top.png)

![oled-header-bottom](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/oled-header-bottom.png)

![oled](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/oled.png)

또한, 이는 커스텀 케이스와 더 많은 DIY 작업이 필요하지만, 플라잉 와이어를 통해 OLED의 4개 핀을 케이스 측면으로 빼내어 스위치/엔코더와 OLED를 함께 사용할 수 있습니다.

</details>

## 펌웨어

### 레이아웃 및 스위치 타입 선택

<details>
  <summary style="font-size:1.1em; font-weight:400;">레이아웃 선택</summary>

조립을 완료한 후, 사용한 레이아웃과 스위치 타입을 **반드시** 선택해야 합니다. 기본적으로 보드는 EC 모드로 설정되어 있습니다.

[VIA](https://www.usevia.app/)를 사용하여 레이아웃과 키 할당을 쉽게 구성할 수 있습니다.

</details>

<details>
  <summary style="font-size:1.1em; font-weight:400;">스위치 타입 선택</summary>

사용한 스위치 타입을 선택하기 위해 `Hybrid Tools` -> `Actuation` 탭 아래의 `Switch Type` 드롭다운 메뉴에서 적절한 옵션(`MX` 또는 `EC`)을 선택합니다.

![via-switch-type](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/via-switch-type.png)

</details>

### EC 캘리브레이션

EC 빌드를 사용하는 경우, 조립 후 보드를 캘리브레이션해야 합니다.

이 과정은 보드의 올바른 기능을 보장하기 위해 필요합니다 (키가 작동하는 것처럼 보여도 모든 키가 제대로 작동한다는 보장은 없습니다).

캘리브레이션 과정은 다음 가이드를 참조하십시오: [EC PCB 캘리브레이션](https://cipulot.squarespace.com/guides#:~:text=Notion%20Webpage-,EC%20PCB%20Calibration,-Brief%20video%20guide)

## 중요 참고사항

**<u>USB 케이블이 연결된 상태에서 TRRS 케이블을 연결하거나 분리하지 마십시오!</u>**

USB 케이블이 연결된 상태에서 TRRS 케이블을 연결하거나 분리하면 키보드의 마이크로컨트롤러가 손상될 수 있습니다.
TRRS 케이블을 연결하거나 분리하기 전에 항상 USB 케이블이 분리되어 있는지 확인하십시오.

## 연락처

질문이 있거나 도움이 필요하시면 [Discord 서버](https://discord.gg/YKZSqHG8bJ) 또는 전문 웹사이트 [Cipulot PCB Design](https://www.lusvsolutions.com/contact)을 통해 문의해 주십시오.
