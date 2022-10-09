# logitech-brio4k-telescope-adapter
This is a simple hardware adapter for the Logitech Brio 4k webcam to the C or CS mount thread. It is available in 1.25" and 2" mounts for common telescope eyepiece lengths. 

Focusing on some telescopes may require adapters or modifications due to prime focus being difficult to achieve for some setups. 

## Printing Instructions
I printed this file on an Elegoo Mars 3 using ABS-Like resin. The threads are fairly tight in tolerance, and require some tuning to ensure the print will function. 

Alternatively, you can print the file in PLA or PETG, the filament is likely soft enough that the threads may be cut through and function using a metal eyepiece. 

## Assembly Instructions
The rework instructions from [Kurokesu](https://www.kurokesu.com/main/2017/09/18/logitech-brio-4k-webcam-rework-instructions/) can be followed for the teardown portion. Some light desoldering is required. I found the use of a hot air rework tool useful for removing the LED though it may be desoldered by hand. 

If those instructions are unavailable for some reason, the front panel of the Brio 4k is simply a glued plastic piece, it can be removed by prying up a corner and carefully pulling it away from the body. There are then two phillips head screws that retain the front face of the case. After the front face is removed, you will note that there is a hotshoe adapter that blocks the mainboard from removal, this is glued in place to the bottom of the case. You can remove this by using a pry tool while taking care to not damage the PCB. Once the hotshoe mount is removed, the rest is fairly simple, a few screws, and desolder the lens/LED. Take care not to damage the sensor. 

The body is a new front face that uses the original two screws to attach to the existing metal back (used as a heatsink). I recommend putting the hotshoe mount back in the body so that there is fewer holes/gaps in the setup.

As the IR filter is removed with the lens assembly, I use a cheap UV IR cut filter from [SVBony](https://www.amazon.ca/gp/product/B07RP5844G) to provide both structure and light filtration. 

## License
![license](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)

This work is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-nc-sa/4.0/). You may review the license in its entirety at [LICENSE.txt](LICENSE.txt)
