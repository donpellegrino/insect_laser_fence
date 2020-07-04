# Insect Laser Fence

## Abstract

The purpose of this repository is to organize resources for implementation of a laser fence that targets insects, including the mosquito and spotted lanternfly. A research question is to determine if work done on laser fences that target mosquitos in Africa could be adapted to spotted lanterfly in Pennsylvania. Note that the original mosquito use case was popularized in 2010 and described as a failure in 2016 (Schiller, 2016).

## Mosqiuto Characterization

Average Flying Altitude: 2 meters (Kare 2010)  
Supply: ∞ (Kare 2010)  
Size: < 2 centimeters (Kare 2010)  
Speed: < 1 meter per second (Kare 2010)  

## Spotted Lanterfly Characterization

"As early as July, adults can be seen, and they mate and lay eggs from late September through the onset of winter." (Wikipedia 2020) Therefore, a system that target adults should be placed into service from July through the onset of winter.

Average Flying Altitude: TODO  
Supply: "killem killem all" (https://youtu.be/1g82I7w3ENU)  
Size: TODO - Translate to requirements for identification  
Speed: TODO - Translate to requirements for response time  

## Candidate Design - Optical Recognition Laser Turret

A candidate design could be a single laser turret. Optical image recognition might be used for target identification. A mounted laser would then be aimed and fired. A candidate use case would be deployment of the turret in a area with moderate to high density of spotted lanterfly. The turret would be manned and operated in a semi-autonomous mode. Semi-autonomous deployment would mitigate safety and weather challenges.

### Bill of Materials

- [NVIDIA Jetson Nano](https://www.nvidia.com/en-us/autonomous-machines/embedded-systems/jetson-nano/): Master control system and image processing for target identification. [$99.00 at Micro Center](https://www.microcenter.com/product/620641/nvidia-jetson-nano-developer-kit---rev-2)
- [Erector by Meccano - Super Construction Set](http://www.meccano.com/product/778988618080/meccano---super-construction-set): Turret assembly and component positioning. [$199.00 (v1) at Amazon](https://www.amazon.com/Meccano-Construction-Motorized-Building-Education/dp/B07C4ZWC1F/ref=sr_1_2?dchild=1&keywords=meccano&qid=1593880029&sr=8-2&th=1)
- Laser: TODO
- Camera: TODO - update with the SparkFun camera for Jetbot product information
- Motors: TODO
- Power: TODO

### Software System

- [NVIDIA JetPack SDK](https://developer.nvidia.com/embedded/jetpack)
- [Python](https://www.python.org/)
- [OpenCV](https://opencv.org/)

## References

Anonymous. (2020, July 4). "How Does Mosquito Laser Work? Here's How To Build/Buy A DIY Killer." *PointerClicker*. Retrieved July 4, 2020, from https://pointerclicker.com/how-mosquito-laser-defense-works/

Kare, J. (2010, Apr 30). "Backyard Star Wars." *IEEE Spectrum*. Retrieved July 4, 2020, from https://spectrum.ieee.org/consumer-electronics/gadgets/backyard-star-wars

Myhrvold, N. (Feb 2010). "Could this laster zap malaria?" *TED Talks*. Retrieved July 4, 2020, from https://www.ted.com/talks/nathan_myhrvold_could_this_laser_zap_malaria

Schiller, B. (2016, May 3). "What Happened To The Mosquito-Zapping Laser That Was Going To Stop Malaria?" *Fast Company*. Retrieved July 4, 2020, from https://www.fastcompany.com/3059127/what-happened-to-the-mosquito-zapping-laser-that-was-going-to-stop-malaria

Wikipedia contributors. (2020, May 16). Mosquito laser. In *Wikipedia, The Free Encyclopedia*. Retrieved 14:31, July 4, 2020, from https://en.wikipedia.org/w/index.php?title=Mosquito_laser&oldid=956918485

Wikipedia contributors. (2020, June 22). Spotted lanternfly. In *Wikipedia, The Free Encyclopedia*. Retrieved 14:43, July 4, 2020, from https://en.wikipedia.org/w/index.php?title=Spotted_lanternfly&oldid=963918748
