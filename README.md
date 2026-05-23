# Amethyst
Amethyst is an 84-key keyboard with a small form factor. It comes with the RP2040 and i have used purple akko v3 switches to give it purple colour. This keyboard runs qmk firmware and can be found under firmware. The complete design file is amethyst.step. I am getting a new laptop this year and did not want to let go of the keymap of the old keyboard, thus i created amethyst. 


![render=top](/media/render-top.png)
![render-side](/media/render-side.png)
![pcb-render](/media/pcb-render.png)
![pcb-mcu](/media/pcb-mcu.png)
![pcb](/media/pcb.png)
![matrix](/media/pcb-matrix.png)

# Soldering and setup
1. Order the PCB from the gerbers present in hardware/production. 
2. order the parts from the given links in bom.csv file
3. first solder the smd components on the back side and then proceed to the through hole keys. 
4. press the heated inserts in the case with the help of a soldering iron. 
5. screw in the case. 
6. fit the keycaps on the top. 
7. short the BOOT and GND pads with a screwdriver and plug in the usb cable.
8. go to the firmware folder and download the .uf2 file. 
9. drag and drop the .uf2 file to the "RPI-RP2" drive that just popped up.
10. Your keyboard is now ready!!

# BOM
