# Build Guide

This is the build guide for the ***鍵盤で GO!*** (けんばんでGO!, Kenban de GO!).

![Kenban-de-go](/img/kenban_de_go.png)
![Kenban-de-go-subtitle](/img/kenban_de_go_subtitle.png)

## Assembly Types

There are three types of assemblies available:
- MX Build
- EC Build (OEM-Style Parts)
- EC Build (Naevies Parts)

All builds showcased are the left-hand side. The right-hand side assembly is a mirror image of the left.

The build process showcased in this guide refers to the "FR4 Case" version.

_Please pay attention to the instructions and notes to avoid any damage to the components._

<details>
  <summary style="font-size:1.1em; font-weight:600;">MX Build</summary>

## Parts

### Required

| Name            | Count   | Remarks                                                     |
| :-------------- | :------ | :---------------------------------------------------------- |
| PCB             | 1 set   |                                                             |
| Backplate       | 1 set   |                                                             |
| MX Switch plate | 1 set   |                                                             |
| Key switches    | 42 - 46 | Only Cherry MX compatible                                   |
| Keycaps         | 42 - 46 | 1u 40 pcs, 1.5u 2 pcs                                       |
| Case Spacer M2  | 8       | M2x9mm                                                      |
| Case Screw M2   | 16      | M2x5mm (⌀4mm head max to avoid collision with switches)     |
| Rubber feets    | 8       |                                                             |
| TRS/TRRS cable  | 1       | Both TRS (3 poles) and TRRS (4 poles) cables are compatible |
| Type-C cable    | 1       |                                                             |

### Optional

| Name           | Count        | Remarks                                                                                                                                             |
| :------------- | :----------- | :-------------------------------------------------------------------------------------------------------------------------------------------------- |
| Rotary Encoder | 0 - 4 pieces | compatible product of the rotary encoder EC12                                                                                                       |
| OLED           | 0 - 2 pieces | 0.91" 128x32 OLED display module and headers (128x64 OLED supported but required different firmware and mounting differences to avoid interference) |

## Assembly

### 1: Attach spacers to the Plate

Utilizing the M2x5mm screws, affix the spacers to the designated holes on the switch plate.

The screw holes for the spacers are marked by small circular plated through holes on the plate.

Based on the layout you are building, 3x6 or 3x5, you will need to choose the appropriate holes for the spacers as shown in the images below (some locations are shared regardless of the layout).

![mx-spacer-plate-locations](/img/mx/mx-spacer-plate-locations.png)

![mx-spacer-plate](/img/mx/mx-spacer-plate.png)

### 2: Attach switches to Plate and PCB

Insert the switches on 4 opposite corners into the switch plate, ensuring they are securely positioned.

![mx-switch-corners-plate](/img/mx/mx-switch-corners-plate.png)

Align the switch plate with the PCB and firmly press them together until the switches are fully seated in the PCB.

![mx-switch-corners-plate-pcb](/img/mx/mx-switch-corners-plate-pcb.png)

After that, populate the remaining switches into the switch plate and PCB.

![mx-switch-plate-pcb](/img/mx/mx-switch-plate-pcb.png)

### 3: Attach the Backplate to the Assembly of 1 and 2

Flip the assembly of step 2 upside down, and align the backplate with the assembly.

Secure the backplate to the assembly using M2x5mm screws in the specular locations of the spacers you attached in step 1.

![mx-backplate-assembly](/img/mx/mx-backplate-assembly.png)

### 4: Attach rubber feets

Affix the rubber feet to the designated corners on the Backplate.

![mx-rubber-feets](/img/mx/mx-rubber-feets.png)

### 5: Attach keycaps

Place the keycaps onto the switches, ensuring they are firmly seated.

</details>

<details>
  <summary style="font-size:1.1em; font-weight:600;">EC Build (OEM-Style Parts)</summary>

## Parts

### Required

| Name               | Count   | Remarks                                                                                                                                         |
| :----------------- | :------ | :---------------------------------------------------------------------------------------------------------------------------------------------- |
| PCB                | 1 set   |                                                                                                                                                 |
| Backplate          | 1 set   |                                                                                                                                                 |
| EC Switch plate    | 1 set   |                                                                                                                                                 |
| EC Housings        | 42 - 46 | Topre or OEM-Style requires modification to the housing (shown later) \ Dynacap doesn't require any modifications                               |
| EC Sliders         | 42 - 46 | Topre OEM or MX compatible                                                                                                                      |
| EC Silencing Rings | 42 - 46 | If you want to have a quieter typing experience                                                                                                 |
| EC Domes           | 42 - 46 | Cutting for correct alignment will be reuired because of the layout                                                                             |
| EC Springs         | 42 - 46 |                                                                                                                                                 |
| Keycaps            | 42 - 46 | 1u 40 pcs, 1.5u 2 pcs (Topre stem or MX based on slider choice)                                                                                 |
| Case Spacer M2     | 8       | M2x9mm                                                                                                                                          |
| Case Screw M2      | 16      | M2x5mm (⌀4mm head max to avoid collision with switches)                                                                                         |
| EC Screws M2       | 24 - 28 | M2x8mm (⌀4mm head max to avoid collision with switches) for the compression in the EC assembly. Different count if 3x5 or 3x6 layout is chosen. |
| Rubber feets       | 8       |                                                                                                                                                 |
| TRS/TRRS cable     | 1       | Both TRS (3 poles) and TRRS (4 poles) cables are compatible                                                                                     |
| Type-C cable       | 1       |                                                                                                                                                 |

### Optional

| Name           | Count        | Remarks                                                                                                                                             |
| :------------- | :----------- | :-------------------------------------------------------------------------------------------------------------------------------------------------- |
| Rotary Encoder | 0 - 4 pieces | compatible product of the rotary encoder EC12                                                                                                       |
| OLED           | 0 - 2 pieces | 0.91" 128x32 OLED display module and headers (128x64 OLED supported but required different firmware and mounting differences to avoid interference) |

## Modifying the EC Housings

If you are using Topre or OEM-Style housings, you will need to modify them to fit the layout of this keyboard. The modification involves cutting a part of the housing to ensure proper clearance and fitment for the compression screws.

Modify the housings by cutting the indicated part as shown in the image below.

![ec-housing-modification](/img/ec/ec-housing-modification.png)

You will need to do this modification for all the housings you are going to use in the following market locations:

![ec-housing-modification-locations](/img/ec/ec-housing-modification-locations.png)

Dynacap housings do not require any modifications since they are designed with sufficient clearance.

## Assembly

### 1: Attach spacers to the Plate

Utilizing the M2x5mm screws, affix the spacers to the designated holes on the switch plate.

The screw holes for the spacers are marked by small circular plated through holes on the plate.

Based on the layout you are building, 3x6 or 3x5, you will need to choose the appropriate holes for the spacers as shown in the images below (some locations are shared regardless of the layout).

![ec-spacer-plate-locations](/img/ec/ec-spacer-plate-locations.png)

![ec-spacer-plate](/img/ec/ec-spacer-plate.png)

### 2: Attach the EC housings to Plate

Flip the assembly of step 1 upside down and insert the EC housings in all locations of switch plate, ensuring they are securely positioned.

![ec-housings-plate](/img/ec/ec-housings-plate.png)

Note the orientation of the housings, the small side circular cutout on the housings should be on the left and right sides like in the image below.

![ec-housings-plate-orientation](/img/ec/ec-housings-plate-orientation.png)

### 3: Prop the assembly of step 2 and insert the EC Sliders

The assembly of step 2 needs to be propped up to allow the insertion of the EC sliders into the housings in a "free fall" manner (such that the slider drops in freely), this will later ensure the proper alignment of the domes and springs.

After that, insert the EC sliders into the housings. If you want to have a quieter typing experience, you can also insert the silencing rings at this stage before you insert the sliders.

![ec-sliders](/img/ec/ec-sliders.png)

### 4: Lay down the domes

You will need to cut the domes for correct alignment because of the layout. The cut part is indicated in the image below (here we assume a 1x4 dome strip, if you are using a different configuration please adjust accordingly).

![ec-domes-cut](/img/ec/ec-domes-cut.png)

After that, lay down the domes on the housings, ensuring they are properly aligned with the housing notches.

![ec-domes](/img/ec/ec-domes.png)

### 5: Lay down the springs

Place the springs on top of the domes, ensuring they are centered and not tilted

![ec-springs](/img/ec/ec-springs.png)

The following image shows highlighted the springs to make them more visible. Notice that the springs are not tilted in the side view.

![ec-springs-profile](/img/ec/ec-springs-profile.png)

### 6: Lay down the PCB on the assembly

_This is a delicate step, so please proceed with caution and calmly!_

Carefully align the PCB with the assembly, ensuring that the PCB is properly aligned with the assembly.
This step may require some effort to compress the assembly, so please be patient and take your time.

At this point grab hold of the assembly with one hand firmly compress the plate and PCB together, while with the other hand insert the M2x8mm screws into the designated holes to secure the PCB to the assembly from the plate side.

Start with the 4 corners screws, then proceed with the remaining screws. Once the 4 corners are secured, you can proceed to add the remaining screws.

![ec-pcb-assembly](/img/ec/ec-pcb-assembly-play.png)

Here is a GIF showing the process of compressing the assembly and inserting the screws.

![ec-pcb-assembly-gif](/img/ec/ec-pcb-assembly.gif)

### 7: Attach the Backplate to the Assembly of 6

Flip the assembly of step 6 upside down, and align the backplate with the assembly, then secure the backplate to the assembly using M2x5mm screws in the specular locations of the spacers you attached in step 1.

![ec-backplate-assembly](/img/ec/ec-backplate-assembly.png)

### 8: Attach rubber feets

Affix the rubber feet to the designated corners on the Backplate.

![ec-rubber-feets](/img/ec/ec-rubber-feets.png)

### 9: Attach keycaps

Place the keycaps onto the switches, ensuring they are firmly seated.

</details>

## Optional Modifications

<details>
<summary style="font-size:1.1em; font-weight:600;">Optional #1: 3x5 key layout</summary>

If you want to use a 3x5 key layout, you can modify the switch plate and PCB accordingly. You can choose to do this modification on either or both sides of the keyboard.

The outermost column of the switch plate needs to be snapped off.

**NOTE**: This modification is irreversible, so please proceed with caution.

![3x5-layout-plate-snap](/img/3x5-layout-plate-snap.png)

Before snapping the PCB, make sure to cut the traces connecting to the switches in that column using a knife or a cutter. This is to prevent any electrical issues after the modification.

![3x5-layout-pcb-cut](/img/3x5-layout-pcb-cut.png)

After cutting the traces, you can snap off the outermost column of the PCB.

</details>

<details>
<summary style="font-size:1.1em; font-weight:600;">Optional #2: Solder rotary encoders instead of switches</summary>

If a rotary encoder is used, it can be attached instead of a switch _either or both_ of the following locations. In that case, soldering from the back side is required.

![rotary-encoder-location-pcb-top](/img/rotary-encoder-location-pcb-top.png)

![rotary-encoder-location-pcb-bottom](/img/rotary-encoder-location-pcb-bottom.png)

</details>

<details>
<summary style="font-size:1.1em; font-weight:600;">Optional #3: Solder OLED instead of switches</summary>

If an OLED is used, it can be attached instead of switches in this location. In that case, soldering from the back side is required.

![oled-location-pcb](/img/oled-location-pcb.png)

You will also have to snap off part of the plate to make space for the OLED.

![plate-snap-oled](/img/plate-snap-oled.png)

We suggest you to utilize a female pin header (1x4) for easy replacement of the OLED in the future.

![oled-header-top](/img/oled-header-top.png)

![oled-header-bottom](/img/oled-header-bottom.png)

![oled](/img/oled.png)

Furthermore, while this will require a custom case and more DIY work, you can use the switches/encoders AND the OLED together by bringing the 4 pins of the OLED out to the side of the case through flying wires.

</details>

## Firmware

### Layout and Switch Type Selection

<details>
  <summary style="font-size:1.1em; font-weight:400;">Layout Selection</summary>

Once you completed the assembly, you **MUST** select the layout and switch type you used. By default the board is configured to EC mode.

Using [VIA](https://www.usevia.app/) you can easily configure the layout and key assignments.

</details>

<details>
  <summary style="font-size:1.1em; font-weight:400;">Switch Type Selection</summary>

In order to select the switch type you will select the appropriate option, `MX` or `EC`, from the `Switch Type` dropdown menu under `Hybrid Tools` -> `Actuation` tab.

![via-switch-type](/img/via-switch-type.png)

</details>

### EC Calibration

In case you are using the EC build, you will need to calibrate the board after the assembly.

This process is required to ensure the proper functioning of the board (even if the keys appear to work it is not guaranteed that all the keys will work properly).

Please refer to the following guide for the calibration process: [EC PCB Calibration](https://cipulot.squarespace.com/guides#:~:text=Notion%20Webpage-,EC%20PCB%20Calibration,-Brief%20video%20guide)

## Important Note

**<u>DO NOT CONNECT OR DISCONNECT THE TRRS CABLE WHILE THE USB CABLE IS CONNECTED!</u>**

If the TRRS cable is plugged or unplugged while the USB cable is connected, the keyboard's microcontroller may be damaged.
Before plugging or unplugging the TRRS cable, always ensure that the USB cable is disconnected.

## Get in Touch

If you have any questions or need assistance, feel free to reach out to us through my [Discord server](https://discord.gg/YKZSqHG8bJ) or professional website [Cipulot PCB Design](https://www.lusvsolutions.com/contact).