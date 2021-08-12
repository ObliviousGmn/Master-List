# Boardsource Master Guide List
Collection of Guides & Part Lists!!

# Guides

- [Soldering Guide](https://mightyohm.com/files/soldercomic/FullSolderComic_EN.pdf)
- [Desoldering Video Guide](https://www.youtube.com/watch?v=ixskRR26Nmst)
- [Reviung41 Medwa Build Guide](https://medwa.pl/docs/reviung41-build-guide/)
- [Corne V3](https://imgur.com/a/P5g8rKu)
- [Corne V2](https://github.com/foostan/crkbd/blob/master/corne-classic/doc/buildguide_en.md)
- [Reviung41/39](https://reviung.com/build-guide/391/)
- [Mircodox](https://github.com/ItsWaffIe/waffle_microdox/wiki/Microdox-Build-Guide)
- [TG4X](https://github.com/MythosMann/tg4x/blob/master/buildguide.md)
- [Ergo Travel](https://github.com/jpconstantineau/ErgoTravel/blob/master/BuildInstructions.md)
- [Rhymestone](https://github.com/marksard/Keyboards/blob/master/rhymestone/documents/rhymestone_buildguide.md)
- [3x4 Macropad](https://boardsource.xyz/help/5ee88cf909fed07af0b23c1d)
- [Boardsource Ortho Boards](https://boardsource.xyz/help/5f02722b97e16c21d7822fa2)
- [Lily58](https://github.com/kata0510/Lily58/blob/master/Pro/Doc/buildguide_en.md)

# Soldering 101
![Soldering Basics](https://cdn.discordapp.com/attachments/705657159639105626/793930004130955304/unknown.png)

# "My Keys aren't working" Checklist (Waffle)
Check in this order: 

- Verify the key isn't a layer change key since they won't show up in key testers

- Check for a bent switch pins

- Short the hotswap socket pads with some tweezers or a paper clip to simulate a key press 

- Verify the diode for the key is oriented properly.

- Reflow solder on the hotswap socket 

- Reflow solder on the key's diode 

- Check for shorts on your micro controller. Most commonly between the two rows of pins on keyboards like the V2 Corne and Lily58

# SMD LED soldering tips by (Waffle)

- FLUX WILL HELP YOU IMMENSELY 
- Assuming you're using something similar to 60/40 0.032in/0.8mm solder, I recommend soldering at 280-300°c. 
- Pre tin a pad and reflow the solder while placing the LED down on the pad with some tweezers. 
- Orientation is very important. It won't only mess up your LEDs, but incorrect orientation will also prevent your keys from working. 
- Work on one LED at a time. Solder a pad on one and move onto the next to let the previous one cool. 
- Although it may be a pain to work on these LEDs with your controllers in place, I strongly suggest test the LEDs as you go (completely solder 3 at a time) and plug it in to test   that those 3 work. This will save you so much more troubleshooting down the road. 
- Regarding testing, keep in mind LEDs do follow a data chain (1, 2, 3, 4...) so you must follow that for them to work.

# Socketing Parts Lists (Waffle)

This is for socketing Pro Micros, Elite-C's, Nice!Nanos & OLED displays.
- [Female to Male Mill-Max Sockets](https://www.digikey.com/product-detail/en/mill-max-manufacturing-corp/315-43-164-41-003000/ED4764-64-ND/1212143)

You need a **quantity of 1** for a split keyboard with OLED displays
They come in rows of 64 and 48 will be used for your micro controllers and another 8 for you OLED displays.
- [Mill-Max Socket Pins](https://www.digikey.com/product-detail/en/mill-max-manufacturing-corp/3320-0-00-15-00-00-03-0/ED1134-ND/4147392)
These are can be replaced by diode legs but these are all around the best option.
These are sold individually, therefore you will need to purchase 48 (24 for each controller)

- [Male-Male sockets for OLED displays](https://www.digikey.com/product-detail/en/mill-max-manufacturing-corp/350-10-164-00-006000/ED6864-64-ND/357045)
These are used for socketing your OLED displays.
These are also sold in rows of 64 so a quantity of 1 will be more than enough (you only need 8)

- **Nice!Nano sockets** for putting 110mAh  under the controller 
[Nano Recommended Sockets](https://www.amazon.com/Single-Headers-Machine-Female-2-54mm/dp/B0187LTEX2)
these will work with diode legs or the Millmax pins linked above.

