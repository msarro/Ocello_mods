# Matty's O-Cello Modification Collection
These are a collection of [O-Cello](https://o-cello.com/) mods that I created to help build an O-Cello electric cello for my wife as a birthday gift. These were required for assembly given some design choices that I made. 

Where possible source files are provided for you to tweak. When this project began I was much less familiar with freecad so tools like Shapr3d and TinkerCad were used.

## Models:
 - `chestrest_4thpos_aio` - This combines the chest rest base, chest rest, and fourth position from ostep's [O-Cello Custom Build/Remix](https://www.thingiverse.com/thing:4942336) into a single printable part. Needless to say, this requires a large bed 3d printer. This is mostly to produce a slightly tidier end result than I was getting when I was using epoxy to join the pieces after printing them separately. It also lets you avoid supports when printing the main chest rest.
    - Recommended print settings:
        - Material: Use what you want here - I used black PLA but PETG, ABS, or ASA could all be appropriate choices. It mostly just rest's against your chest.
        - 20% infill 

- `./coverplate/` - This is simply a blank coverplate to install in the O-Cello. This can be used with your slicer's emboss function to add a custom logo in part 5. You may need to tweak the size, but it is a very quick print. The freecad `FCStd` file, `step` and `stl` files are provided.
    - Recommended print settings:
        - 100% infill 
        - Whatever material you view is appropriate, it won't be facing any stress. Preferably something that doesn't have shrinkage issues since it requires a compression fit.

- `./hanger/` - This is a custom hanger for the O-Cello, when using the custom chest rest and 4th position from ostep's [O-Cello Custom Build/Remix](https://www.thingiverse.com/thing:4942336). Given the O-Cello is a home built instrument, there are no hangers available. This is my attempt at a wall mounted hanger. 
    - Recommended print settings:
        - At least 20% cubic infill
        - .2mm layers
        - 3 walls, + alternate extra wall (if supported by slicer)
        - Print with PETG
    - You will need 2x #4 or #6 x7/8" pan head screws. The holes are 3mm wide with 7mm for a pan head.
    - I CAN NOT guarantee that this is not going to break and drop/damage your treasured O-Cello. Use at your own risk. We are using it successfully in our studio but your mileage can certainly vary. I used a carbon fiber tube and carbon fiber rod for our build, so the weight is much less than if you built yours using a steel tube and rod.

- `./leg-rests/` - The [O-Cello Fishman 301 Mod](https://www.thingiverse.com/thing:5975456) assumes you are using [The Original O-Cello](https://o-cello.com/) parts. But it routes the pickup's output jack in such a way that the normal aluminum L bar orientation would not work. There are two models provided to work around this:
    - `knee_rest_crossbar.stl` - This is a custom crossbar that can be used in place of aluminum L-bar if you cannot find one locally. It requires at least 310mm build volume along X axis, Y axis, or diagonal. It would match a 3mm x 20mm aluminum L bar. It has a small notch to fit against the output jack when using [O-Cello Fishman 301 Mod](https://www.thingiverse.com/thing:5975456).
        - Recommended print settings:
            - Material: PETG (I used PLA but PETG has a little more flex)
            - 100% infill
    - `knee_rest_left_custom.stl` - This is a custom knee rest matching the crossbar. Sadly I built it using shapr3d and on the trial version they only allow you to export a low-poly version. So, it picked up some artifacts, which gave it a little charm. Only the left side is provided, simply mirror it in your slicer to get the right side.
         - Recommended print settings:
            - Material: TPU
            - 15% gyroid infill

- `./oval_bottom_bridge` - This is a 3d printed bridge for the O-Cello based on the original solid bridge from [ConorKane](https://www.thingiverse.com/conorokane/designs). When using the Fishman Presys 301 braided piezoelectric pickup (or any other braided piezoelectric pickup), the bridge needs to have a small indentation to allow the pickup to sit snugly under it, while still letting the bridge sit properly. The excellent [O-Cello Fishman 301 Mod](https://www.thingiverse.com/thing:5975456) has the braided cable coming out at an angle in the bottom of the bridge groove on part 5. Additionally I found that the pickup bridge on [O-Cello Custom Build/Remix](https://www.thingiverse.com/thing:4942336), having a flat area on each side, would crimp the braided cable. So I simply carved a small arc out of the bottom of the solid bridge so it can sit flat, allow the cable to enter the groove safely, and maintain good contact between the piezo and the bridge. 
 - Recommended print settings:
    - Play around! I printed this with 100% infill black PLA.


## References and Attributions
I could not have built my o-cello without the help of the community of builders who brought us the o-cello and various mods. These are the projects whose models I used to build our cello.

- [The Original O-Cello](https://o-cello.com/) by [ConorKane](https://www.thingiverse.com/conorokane/designs)
    - [Thingiverse](https://www.thingiverse.com/thing:1703629)
- [O-Cello Fishman 301 Mod](https://www.thingiverse.com/thing:5975456) by [Bbenje2000](https://www.thingiverse.com/benje2000/designs) on Thingiverse
- [O-Cello Custom Build/Remix](https://www.thingiverse.com/thing:4942336) by [ostep](https://www.thingiverse.com/otsep/designs) on Thingiverse

Enjoy!

These files are made available under a Attribution-NonCommercial 4.0 International License. For full details please check the `LICENSE` file. A TLDR version can be found [here.](https://creativecommons.org/licenses/by-nc/4.0/)