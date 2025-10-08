# 组装指南

这是 **_鍵盤で GO!_** (けんばんで GO!, Kenban de GO!) 的组装指南。

![Kenban-de-go](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/kenban_de_go.png)
![Kenban-de-go-subtitle](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/kenban_de_go_subtitle.png)

## 组装类型

提供三种组装类型：

- MX 版本
- EC 版本 (OEM 风格部件)
- EC 版本 (Naevies 部件)

所有展示的组装均为左手侧。右手侧的组装是左手侧的镜像。

本指南中展示的组装过程指的是 "FR4 外壳" 版本。

_请注意说明和注释，以避免损坏组件。_

<details>
  <summary style="font-size:1.1em; font-weight:600;">MX 版本</summary>

## 部件

### 必需部件

| 名称          | 数量    | 备注                                  |
| :------------ | :------ | :------------------------------------ |
| PCB           | 1 套    |                                       |
| 背板          | 1 套    |                                       |
| MX 轴板       | 1 套    |                                       |
| 机械轴        | 42 - 46 | 仅限樱桃 MX 兼容轴                    |
| 键帽          | 42 - 46 | 1u 40 个, 1.5u 2 个                   |
| 外壳垫柱 M2   | 8       | M2x9mm                                |
| 外壳螺丝 M2   | 16      | M2x5mm (最大 ⌀4mm 头以避免与开关干涉) |
| 橡胶脚垫      | 8       |                                       |
| TRS/TRRS 线缆 | 1       | TRS (3 极) 和 TRRS (4 极) 线缆均兼容  |
| Type-C 线缆   | 1       |                                       |

### 可选部件

| 名称       | 数量     | 备注                                                                                      |
| :--------- | :------- | :---------------------------------------------------------------------------------------- |
| 旋转编码器 | 0 - 4 个 | EC12 兼容的旋转编码器产品                                                                 |
| OLED       | 0 - 2 个 | 0.91" 128x32 OLED 显示模块和排针 (支持 128x64 OLED，但需要不同的固件和安装方式以避免干涉) |

## 组装步骤

### 1: 将垫柱安装到定位板上

使用 M2x5mm 螺丝，将垫柱固定到定位板上的指定孔位。

定位板上用于固定垫柱的螺丝孔由小的圆形金属化通孔标记。

根据您正在构建的布局，3x6 或 3x5，您需要选择相应的孔位来安装垫柱，如下图所示（某些位置无论布局如何都是共用的）。

![mx-spacer-plate-locations](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/mx/mx-spacer-plate-locations.png)

![mx-spacer-plate](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/mx/mx-spacer-plate.png)

### 2: 将开关安装到定位板和 PCB 上

将四个对角的开关插入定位板，确保它们牢固就位。

![mx-switch-corners-plate](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/mx/mx-switch-corners-plate.png)

将定位板与 PCB 对齐，并用力将它们按压在一起，直到开关完全插入 PCB。

![mx-switch-corners-plate-pcb](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/mx/mx-switch-corners-plate-pcb.png)

之后，将其余的开关安装到定位板和 PCB 上。

![mx-switch-plate-pcb](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/mx/mx-switch-plate-pcb.png)

### 3: 将背板安装到步骤 1 和 2 的组件上

将步骤 2 的组件翻转过来，使背面朝上，并将背板与组件对齐。

使用 M2x5mm 螺丝，在步骤 1 中安装垫柱的镜像位置，将背板固定到组件上。

![mx-backplate-assembly](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/mx/mx-backplate-assembly.png)

### 4: 安装橡胶脚垫

将橡胶脚垫粘贴到背板上的指定角落。

![mx-rubber-feets](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/mx/mx-rubber-feets.png)

### 5: 安装键帽

将键帽安装到开关上，确保它们牢固就位。

</details>

<details>
  <summary style="font-size:1.1em; font-weight:600;">EC 版本 (OEM 风格部件)</summary>

## 部件

### 必需部件

| 名称          | 数量    | 备注                                                                                                 |
| :------------ | :------ | :--------------------------------------------------------------------------------------------------- |
| PCB           | 1 套    |                                                                                                      |
| 背板          | 1 套    |                                                                                                      |
| EC 定位板     | 1 套    |                                                                                                      |
| EC 外壳       | 42 - 46 | Topre 或 OEM 风格的外壳需要修改（稍后展示）\ Dynacap 不需要任何修改                                  |
| EC 滑块       | 42 - 46 | Topre OEM 或 MX 兼容                                                                                 |
| EC 静音环     | 42 - 46 | 如果您想要更安静的输入体验                                                                           |
| EC 胶碗       | 42 - 46 | 由于布局原因，需要切割以获得正确对齐                                                                 |
| EC 弹簧       | 42 - 46 |                                                                                                      |
| 键帽          | 42 - 46 | 1u 40 个, 1.5u 2 个 (根据滑块选择 Topre 十字柱或 MX 十字柱)                                          |
| 外壳垫柱 M2   | 8       | M2x9mm                                                                                               |
| 外壳螺丝 M2   | 16      | M2x5mm (最大 ⌀4mm 头以避免与开关干涉)                                                                |
| EC 螺丝 M2    | 24 - 28 | M2x8mm (最大 ⌀4mm 头以避免与开关干涉) 用于 EC 组件的压缩固定。数量根据选择的 3x5 或 3x6 布局而不同。 |
| 橡胶脚垫      | 8       |                                                                                                      |
| TRS/TRRS 线缆 | 1       | TRS (3 极) 和 TRRS (4 极) 线缆均兼容                                                                 |
| Type-C 线缆   | 1       |                                                                                                      |

### 可选部件

| 名称       | 数量     | 备注                                                                                      |
| :--------- | :------- | :---------------------------------------------------------------------------------------- |
| 旋转编码器 | 0 - 4 个 | EC12 兼容的旋转编码器产品                                                                 |
| OLED       | 0 - 2 个 | 0.91" 128x32 OLED 显示模块和排针 (支持 128x64 OLED，但需要不同的固件和安装方式以避免干涉) |

## 修改 EC 外壳

如果您使用 Topre 或 OEM 风格的外壳，则需要修改它们以适应这款键盘的布局。修改涉及切割外壳的一部分，以确保压缩螺丝有适当的间隙和配合度。

按照下图所示，切割指示部分来修改外壳。

![ec-housing-modification](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-housing-modification.png)

您需要对以下标记位置使用的所有外壳进行此修改：

![ec-housing-modification-locations](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-housing-modification-locations.png)

Dynacap 外壳不需要任何修改，因为它们设计时有足够的间隙。

## 组装步骤

### 1: 将垫柱安装到定位板上

使用 M2x5mm 螺丝，将垫柱固定到定位板上的指定孔位。

定位板上用于固定垫柱的螺丝孔由小的圆形金属化通孔标记。

根据您正在构建的布局，3x6 或 3x5，您需要选择相应的孔位来安装垫柱，如下图所示（某些位置无论布局如何都是共用的）。

![ec-spacer-plate-locations](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-spacer-plate-locations.png)

![ec-spacer-plate](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-spacer-plate.png)

### 2: 将 EC 外壳安装到定位板上

将步骤 1 的组件翻转过来，使背面朝上，并将 EC 外壳插入定位板的所有位置，确保它们牢固就位。

![ec-housings-plate](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-housings-plate.png)

注意外壳的方向，外壳上的小圆形切口应在左右两侧，如下图所示。

![ec-housings-plate-orientation](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-housings-plate-orientation.png)

### 3: 支撑步骤 2 的组件并插入 EC 滑块

步骤 2 的组件需要被支撑起来，以便以"自由落体"的方式将 EC 滑块插入外壳（即滑块可以自由落下），这将确保胶碗和弹簧的正确对齐。

之后，将 EC 滑块插入外壳。如果您想要更安静的输入体验，也可以在插入滑块之前在此阶段插入静音环。

![ec-sliders](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-sliders.png)

### 4: 放置胶碗

由于布局原因，您需要切割胶碗以获得正确对齐。切割部分在下图中标示（这里我们假设是 1x4 的胶碗条，如果您使用不同的配置，请相应调整）。

![ec-domes-cut](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-domes-cut.png)

之后，将胶碗放在外壳上，确保它们与外壳的卡口正确对齐。

![ec-domes](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-domes.png)

### 5: 放置弹簧

将弹簧放在胶碗顶部，确保它们居中且不倾斜。

![ec-springs](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-springs.png)

下图高亮显示了弹簧，使其更可见。注意在侧视图中弹簧没有倾斜。

![ec-springs-profile](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-springs-profile.png)

### 6: 将 PCB 放置在组件上

_这是一个精细的步骤，请谨慎并冷静地进行！_

小心地将 PCB 与组件对齐，确保 PCB 与组件正确对齐。
此步骤可能需要一些力气来压缩组件，请耐心并慢慢来。

此时，用一只手牢牢抓住组件，压缩定位板和 PCB，同时用另一只手将 M2x8mm 螺丝插入指定孔中，从定位板侧将 PCB 固定到组件上。

从 4 个角的螺丝开始，然后处理剩余的螺丝。一旦 4 个角固定好，您就可以继续添加剩余的螺丝。

![ec-pcb-assembly](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-pcb-assembly-play.png)

这里有一个 GIF 展示了压缩组件和插入螺丝的过程。

![ec-pcb-assembly-gif](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-pcb-assembly.gif)

### 7: 将背板安装到步骤 6 的组件上

将步骤 6 的组件翻转过来，使背面朝上，并将背板与组件对齐，然后使用 M2x5mm 螺丝，在步骤 1 中安装垫柱的镜像位置，将背板固定到组件上。

![ec-backplate-assembly](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-backplate-assembly.png)

### 8: 安装橡胶脚垫

将橡胶脚垫粘贴到背板上的指定角落。

![ec-rubber-feets](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/ec/ec-rubber-feets.png)

### 9: 安装键帽

将键帽安装到开关上，确保它们牢固就位。

</details>

## 可选修改

<details>
<summary style="font-size:1.1em; font-weight:600;">可选 #1: 3x5 键布局</summary>

如果您想使用 3x5 键布局，可以相应地修改定位板和 PCB。您可以选择在键盘的一侧或两侧进行此修改。

需要将定位板的最外列折断。

**注意**：此修改不可逆，请谨慎操作。

![3x5-layout-plate-snap](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/3x5-layout-plate-snap.png)

在折断 PCB 之前，请确保使用小刀或切割器切断连接到该列开关的线路。这是为了在修改后防止任何电气问题。

![3x5-layout-pcb-cut](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/3x5-layout-pcb-cut.png)

切断线路后，您可以折断 PCB 的最外列。

</details>

<details>
<summary style="font-size:1.1em; font-weight:600;">可选 #2: 焊接旋转编码器代替开关</summary>

如果使用旋转编码器，它可以代替开关安装在*以下一个或两个*位置。在这种情况下，需要从背面进行焊接。

![rotary-encoder-location-pcb-top](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/rotary-encoder-location-pcb-top.png)

![rotary-encoder-location-pcb-bottom](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/rotary-encoder-location-pcb-bottom.png)

</details>

<details>
<summary style="font-size:1.1em; font-weight:600;">可选 #3: 焊接 OLED 代替开关</summary>

如果使用 OLED，它可以代替开关安装在此位置。在这种情况下，需要从背面进行焊接。

![oled-location-pcb](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/oled-location-pcb.png)

您还需要折断部分定位板以为 OLED 腾出空间。

![plate-snap-oled](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/plate-snap-oled.png)

我们建议您使用母排针 (1x4) 以便将来轻松更换 OLED。

![oled-header-top](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/oled-header-top.png)

![oled-header-bottom](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/oled-header-bottom.png)

![oled](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/oled.png)

此外，虽然这需要定制外壳和更多的 DIY 工作，但您可以通过飞线将 OLED 的 4 个引脚引出到外壳侧面，从而同时使用开关/编码器和 OLED。

</details>

## 固件

### 布局和开关类型选择

<details>
  <summary style="font-size:1.1em; font-weight:400;">布局选择</summary>

完成组装后，您**必须**选择您使用的布局和开关类型。默认情况下，键盘配置为 EC 模式。

使用 [VIA](https://www.usevia.app/) 您可以轻松配置布局和键位分配。

</details>

<details>
  <summary style="font-size:1.1em; font-weight:400;">开关类型选择</summary>

为了选择开关类型，您将在 `Hybrid Tools` -> `Actuation` 标签页下的 `Switch Type` 下拉菜单中选择相应的选项，`MX` 或 `EC`。

![via-switch-type](https://raw.githubusercontent.com/Cipulot/Kenban-de-GO-Build-Guides/refs/heads/main/img/via-switch-type.png)

</details>

### EC 校准

如果您使用的是 EC 版本，则需要在组装后校准键盘。

此过程是确保键盘正常运作所必需的（即使按键看起来工作，也不能保证所有按键都能正常工作）。

请参考以下指南进行校准过程：[EC PCB 校准](https://cipulot.squarespace.com/guides#:~:text=Notion%20Webpage-,EC%20PCB%20Calibration,-Brief%20video%20guide)

## 重要提示

**<u>请勿在 USB 线缆连接时插拔 TRRS 线缆！</u>**

如果在 USB 线缆连接时插拔 TRRS 线缆，可能会损坏键盘的微控制器。
在插拔 TRRS 线缆之前，请务必确保 USB 线缆已断开连接。

## 联系我们

如果您有任何问题或需要帮助，请随时通过我的 [Discord 服务器](https://discord.gg/YKZSqHG8bJ) 或专业网站 [Cipulot PCB 设计](https://www.lusvsolutions.com/contact) 与我们联系。
