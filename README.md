# sd2psx: PCB

<table>
<tr>
    <td><img src="img/pcb.png"></td>
    <td><img src="img/pcb3d.png"></td>
    <td><img src="img/pcb3dback.png"></td>
</tr>
</table>

## Production notes

The PCB must be produced in 0.8mm thickness. Production files are provided under the "Releases" tab. These do not include the through-hole OLED module.

## OLED module notes

The case requires a slim OLED module. The more common full-sized module will not fit into the case:

![](img/slim.jpg)

Examples of compatible modules:
- https://detail.tmall.com/item.htm?id=534583545403&skuId=3942158349315
- https://www.aliexpress.com/item/32638662748.html (make sure to select the smaller module marked as "New-White")

Spec sheet of a compatible module:

![](img/oled.jpg)

**Make sure that the pinout goes GND/VCC/SCL/SDA**. There are modules that swap GND/VCC around, these won't work.

## Assembly tips

When attaching the module to the PCB, remove protective OLED screen film (to prevent misalignment), then drop the module into the case so that the screen ends up flush against the case wall. Solder it on in that setup, then clip the pins:

![](img/asm1.jpg)
![](img/asm2.jpg)

There may be extra space between the pin header and the PCB, depending on your 3d print tolerances, but when fully assembled it should look nice and flush.
