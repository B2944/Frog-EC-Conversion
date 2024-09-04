## Geonworks Frog TKL EC Conversion using the SwedeEC8X
Documentation of the Geonworks Frog TKL EC Conversion and EC8X PCB. This PCB can be found in stock on [ThoccExchange](https://thoccexchange.com) or purchased directly from me via Discord.


![file (1)](https://github.com/user-attachments/assets/ea1c6eea-79ba-4aea-842e-181f70268325)


### Build Specs: 
 
- Burgundy F13 WKL Frog TKL
- SwedeEC8X PCB
- Topre converted Alu 5202 1.2mm plate
- YMDK Housings
- KLC Playground MX Sliders
- YMDK 2U Assemblies and 7U Assembly (Lubed with Krytox 206g2)
- 0.3mm Silencing Rings
- HHKB Hybrid 45g Domes
- HHKB Conical Springs
- DCX WoB



## Build Guide (Pictures coming soon once I get my prototype 300px*) 
1. Place the tadpole mounts into the plate (preferably 90A too increase firmness, to prevent the PCB bottoming out)
2. Click the 1U and 2U Housings into the plate. Next up is this spacebar assembly, this will need to be flipped as shown in the picture to maximise clearance, you will also have to cut the housing above with flush cutters to make room for the flipped spacebar housings and wire if using a plate with a topre stabiliser cutout. If you opted for the MX plate then you can simply clip in your plate mount stabiliser housings and wire. 
3. Push the sliders into the 1U Housings. 
4. Place the domes into the housings. 
5. Place the conical springs in the domes (make sure non are stacked as this causes issues). (You can gently drop the springs that are stacked onto your desk to get them separate easier)
6. Place the pcb onto the back of the plate.
7. Place the provided Waferhead M2.5 8mm Screws into the pcb and tighten into the threaded holes found on the plate. 


## Parts required for the conversion
- Domes, EC Springs, Sliders (Topre Stem or MX), Housings, EC8X PCB, Supported Plate, M2.5 8mm Waferhead Screws. 

  - Domes, EC Springs, MX Sliders and housings can be sourced aftermarket from online vendors such as [Deskeys](https://deskeys.io), [KLC Playground](https://klc-playground.com/products/instock-ec-kits-and-packs?_pos=1&_sid=c27f2fce2&_ss=r&variant=42124616171726) and 
  [ThoccExchange](thoccexchange.com)

  - Topre stem sliders currently have no aftermarket option so will need to be harvested from a board or bought from someone who has already harvested them, these can be found in trade channels found on enthusiast discords. If you fail to find them you can simply buy a 
  realforce to harvest yourself (preferably broken as to not ruin perfectly good boards). This is also a bonus as it will give you the domes, housing, EC springs and keycaps often at a lower price than the aftermarket options.


> [!NOTE]
> You may upset a few people when harvesting perfectly good boards, so please do try and look for a Junkforce. :smile_cat:


## Getting your own plates manufactured

> [!NOTE]
> Ordering your own plates can be rather expensive per unit when doing a small order, so I will be hosting a group order soon after these PCBs launch.

![Screenshot 2024-09-02 095154](https://github.com/user-attachments/assets/a6189bc2-dcaf-4bd1-b67b-103ec98cda5d)


- However, if you are sure you want to get your own made then simply download the plate file for your desired layout from the [plate files](https://github.com/B2944/Frog-EC-Conversion/tree/main/Plate%20Files) folder along with the drawing diagram (beware that there are two options, one which uses standard topre stabilisers and one that uses MX stabilisers for the spacebar to avoid the clearance issues found when using the topre stabiliser). When going down this route you have a few options:


1. Get a plate laser cut to reduce costs and tap the threads yourself - this can be quite difficult and be prepared to snap a few taps. You will also have to adjust the plate file to get the correct size holes ready for tapping. 

2. Get a plate manufactured with threaded holes, this will increase the cost but will ensure that the plate is properly threaded to avoid hiccups in the build process.

3. Get a plate laser cut then epoxy some M2.5 brass standoffs into the holes - this may mean that you have to adjust the plate files to meet the sizing for your standoffs. This will also result in you requiring shorter screws.

4. You can make use of threaded spaces as shown in the example pic from the plato plate guide.

   ![spacer](https://github.com/user-attachments/assets/d952f776-e6ce-4dbc-87da-03020e05d7bc)

This method makes use of a threaded standoff to secure the plate and pcb together using 2 screws, one from above the plate and one below the pcb, the benefit of this is that you can use softer plates like POM or PC which can not be easily threaded. A standoff 4mm standoff is required in order to fit them in between the switch housing without clearance issues. This method makes use of more hardware, but also reduces plate manu costs as you now only require a simple laser cut plate. (Change info to M1.6 screws and standoffs once I test. **This will require plate holes to be adjusted for smaller screws as M2.5 screws have clearance issues inbetween the housings. 
 - For this method you will need:

   - Threaded Standoff spacers
   - Waferhead Screws 3mm and 4mm (3mm through plate, 4mm through pcb)

5. Get a plate laser cut then place 10mm M2.5 Waferhead screws through the top of the plate through to the PCB, then tighten some low profile M2.5 nuts on the back of the PCB.
  - This method is ideal as aluminium threads can be weak so it avoids the risk of stripping the expensive plate. 
  - This method is also much cheaper than a threaded plate and easier than any of the standoff options. 




#### <ins>Screw Types</ins>

When choosing a screw for an EC conversion, you must take into account the amount of clearance underneath the PCB in the case. For this conversion of the Frog, there is not much room so we must opt for the waferhead/flad head style of screw to maximise clearance to avoid the pcb touching the base of the case. 

![image_2024-08-12_222904910](https://github.com/user-attachments/assets/00f30322-ed59-48dd-8afa-aff914f440a9)




## Layout Support

![Layout Support for PCB](https://github.com/user-attachments/assets/720704da-e847-48de-8624-b7edb1ab3a7e)


## VIA

- Whilst waiting for the Firmware to be pushed to the main branch of VIA so the PCB is automatically recognised, you can use this [VIA](https://app-6w4.pages.dev) link.
- If you find yourself having issues with the firmware, please message me on Discord or open an issue on here.

## Tasks left to complete 
- [X] Supporting plates for all Frog TKL Layouts (F12 and F13) 
- [ ] Implement o-ring cutouts for next batch to allow support of all H87/H88 TKLs.
- [ ] Integrated o-ring Plates
- [ ] Frog TKL Integrated Plates
- [ ] Increase PCB support for more boards by converting plates to Topre.
- [ ] Host groupbuy for Frog TKL Plates. DM me on Discord if you would be interested (swede.)

# PCB Design and Compatibility

- I was heavily inspired after discovering Decoys reddit post on their F12 Frog TKL conversion, however once I contacted them to gain a better understanding of the conversion I realised that there was no readily available EC PCB that supported F13 layouts. This lead to the commissioning of the EC8X and the adjusting of the MX Plate file to convert it to accomodate topre housings by using CIPs plate generator to calculate the spacings. 
  
Each round of PCBs will be inspired by a different vehicle

1. <code>Porsche 944</code>
   - Limited to 16 units. 15 USB C and 1 JST Variant. This round features a '944' lettering silkscreen above the nav cluster and a complimentary silkscreen on the back of the PCB of the NA 2.5L inline 4 found in the Porsche 944 and 944 S throughout production during 
   1982-1989. The plates were also designed with this in mind, leaving a cutout above the arrow cluster to view the '944' silkscreen. 

- The PCB is 1.6mm and fully configurable in VIA.
- Screw hole diameter: 2.8mm

### <ins>Compatibility</ins>

- This PCB should work with most TKLs, which do not require O-ring cutouts on the PCB for mounting and also use top mount USB C on the PCB, however I hope to put out a more thorough compatibility list soon. Compatibility for o-ring mount TKLs is in development in the form of an integrated o-ring plate. In addition, I will also be releasing a non o-ring integrated plate for the Frog TKL to maintain that HHKB Plate feeling. 


> [!CAUTION]
> **This PCB will not work with TKLs which require o-ring cutouts**

## Sound Test
   
![soundtest]("Place MP3 File here")
