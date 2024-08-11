# Geonworks Frog TKL EC Conversion using the SwedeEC8X
Documentation of the Geonworks Frog TKL EC Conversion. This kit can be found in stock on [ThoccExchange](https://thoccexchange.com).

![IMG_2808](https://github.com/user-attachments/assets/9e066c7a-82b2-49ed-8bcd-200b5d8ff9b1)


 Build Specs: 
 
- Burgundy F13 WKL Frog TKL
- SwedeEC8X PCB
- Topre converted Alu 5202 1.2mm plate
- YMDK Housings
- KLC Playground MX Sliders
- YMDK 2U Assemblies and 7U Assembly 
- 3mm Silencing Rings
- Realforce R1 45g Domes
- Realforce Conical Springs
- DCX WoB



## Build Guide (Pictures coming soon once I get my prototype 300px*) 
1. Place the tadpole mounts into the plate. 
2. Click the EC Housings and slider assemblies into the plate. 
3. Place the domes into the housings. 
4. Place the conical springs in the domes (make sure non are stacked as this causes issues). 
6. Place the pcb onto the back of the plate.
7. Place the provided Waferhead M2.5 8mm Screws into the pcb and tighten into the threaded holes found on the plate. 


## Parts required for the conversion
- Domes, EC Springs, Sliders (Topre Stem or MX), Housings, EC8X PCB, Supported Plate, M2.5 8mm Waferhead Screws. 

  - Domes, EC Springs, MX Sliders and housings can be sourced aftermarket from online vendors such as [Deskeys](https://deskeys.io), [KLC Playground](https://klc-playground.com/products/instock-ec-kits-and-packs?_pos=1&_sid=c27f2fce2&_ss=r&variant=42124616171726) and 
  [ThoccExchange](thoccexchange.com)

  - Topre stem sliders currently have no aftermarket option so will need to be harvested from a board or bought from someone who has already harvested them, these can be found in trade channels found on enthusiast discords. If you fail to find them you can simply buy a 
  realforce to harvest yourself (preferably broken as to not ruin perfectly good boards). This is also a bonus as it will give you the domes, housing, EC springs and keycaps often at a lower price than the aftermarket options.


  - Another optional part would be silencing rings, which result in a much quieter upstroke as the ring dampens the slider when returning to the top of the housing. 


> [!NOTE]
> You may upset many from harvesting perfectly good boards, so please do try and look for a Junkforce. :smile_cat:


## Getting your own plates manufactured

> [!NOTE]
> Ordering your own plates can be rather expensive per unit when doing a small order, so I will be hosting a group order soon after these PCBs launch.

- However, if you are sure you want to get your own made then simnply download the plate file for your desired layout from the [plate files](https://github.com/B2944/Frog-EC-Conversion/tree/main/Plate%20Files) folder along with the drawing diagram.


## Layout Support

![Layout Support for PCB](https://github.com/user-attachments/assets/720704da-e847-48de-8624-b7edb1ab3a7e)


## VIA

- Whilst waiting for the Firmware to be pushed to the main branch of VIA so the PCB is automatically recognised, you can use this [VIA](https://app-6w4.pages.dev) link.
- If you find yourself having issues with the firmware, please message me on Discord or open an issue on here.

## Tasks left to complete 
- [X] [Support all Frog TKL Layout](https://github.com/B2944/Frog-EC-Conversion/issues/1)
- [ ] Implement o-ring cutouts for next batch to allow support of all H87/H88 TKLs.
- [ ] Increase PCB support for more boards by converting plates to Topre.
- [ ] Host groupbuy for Frog TKL Plates. DM me on Discord if you would be interested (swede.)

# PCB Design 

- I was heavily inspired after discovering Decoys reddit post on their F12 Frog TKL conversion, however once I contacted them to gain a better understanding of the conversion I realised that there was no readily available EC PCB that supported F13 layouts. This lead to the commissioning of the EC8X and the adjusting of the MX Plate file to convert it to Topre by using CIPs plate generator to calculate the spacings. 
  
Each round of PCBs will be inspired by a different vehicle

1. <code>Porsche 944</code>
   - Limited to 16 units. 15 USB C and 1 JST Variant. This round features a '944' lettering silkscreen above the nav cluster and a complimentary silkscreen on the back of the PCB of the 2.5L inline 4 found in the Porsche 944. The plates were also designed with this in        mind, leaving a cutout above the arrow cluster to view the '944' silkscreen. 

- The PCB is 1.6mm and full configurable in VIA.



## Sound Test

![soundtest]("Place MP4 File here")
