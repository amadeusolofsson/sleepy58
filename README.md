# sleepy58

## A low-profile 4x6 orthocolumnar wireless keyboard with a 5-key thumb cluster. 
It uses [ZMK](https://github.com/zmkfirmware/zmk) together with the Seeed Studio XIAO BLE nRF52840.
I created it using [ergogen](https://github.com/ergogen/ergogen). Putting the pcb file into kiCad and routing it.
I used some of [ceoloide's](https://github.com/ceoloide/ergogen-footprints/tree/main) footprints for ergogen.




## Required Parts

| Part name           | Count | Description and sites I bought from (Many swedish ones, just use something equivalent)                                                          |
| :-------------------| :---: | :-----------------------------------------------------------------------------------------------------------------------------------------------|
| PCBs                |   2   | Flippable so only two needed. (I bought from JLCPCB, lead-free, 2 layers)                                                                       |
| XIAO Wireless MCUs  |   3   | 1 each side (+1 if you want to use as dongle) https://www.digikey.se/en/products/detail/seeed-technology-co-ltd/102010448/16652893?so=90838492  |
| Choc Switches v1    |  58   | 58 Low Profile Choc switches (29 for each hand) https://splitkb.com/products/ambients-kailh-low-profile-choc-switches?variant=48116119830875    |
| diodes 1N4148W      |  58   | 58 SOD123 SMD Diodes https://www.digikey.se/en/products/detail/diodes-incorporated/1N4148W-7-F/814371?so=9083849                                |
| Choc Keycaps        |  58   | 58 Choc v1 Compatible Keycaps https://splitkb.com/products/blank-mbk-choc-low-profile-keycaps?variant=31811491987533                            |
| Power Switches      |   2   | For switching battery power https://www.electrokit.com/en/skjutomkopplare-mini-1-pol-on-on-smd                                                  |
| JST Plugs           |   2   | For connecting battery easily https://www.electrokit.com/stiftlist-ph-2-pol-2.0mm-vinklad-1                                                     |
| Lipo batteries      |   2   | Small battery https://www.electrokit.com/batteri-lipo-3.7v-380mah                                                                               |
| Rubber feet         |  8    | Since no case https://www.electrokit.com/3m-bumpon-gummifot-6.4x1.9mm-8-pack                                                                    |
| Dongle casing       |   1   | Optional casing for dongle https://www.printables.com/model/522586-seeed-xiao-ble-case                                                          | 



## Recognitions and thanks
Ben Vallack and Christian Selig for inspiration.
@GEIGEIGEIST & @Pipshag as great examples to compare my own keyboard with for when I got stuck on a specific part.
@VOID for the 3d printed dongle casing files.
And finally massive thanks to the ZMK & Absolem Club discords and it's members who helped me with my stupid questions :)
