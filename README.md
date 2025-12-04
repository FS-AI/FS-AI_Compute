# FS-AI Sense & Compute

## NOTE:

This repository has been updated in preparation for the 2026 FS-AI event. This is still work-in-progress and updates should be expected.


## IMechE Provided 'InCarPC' Compute Platform

Six 'InCarPC' Compute Platforms are available for use with the IMechE ADS-DVs. These are fitted onto 'quick change' plates compatible with the brackets and wiring at the rear of the ADS-DVs.

The specification of the 'InCarPC' is as follows:

Part Number: CQ77G-32-W10P13

* Intel Core i7-8700T up to 4.0GHz
* NVIDIA GeForce GTX 1060 Ti GPU supporting 1280 CUDA cores
* 32GB DDR4 RAM
* Removable 2.5" SATA SSD caddy
* PEAK-System CAN interface (SocketCAN compatible)
* 4x USB 3.0 ports
* 2x GbE LAN ports
* 4x HDMI + 3x DisplayPort
* 2.4 & 5 GHz 802.11ac WLAN & Bluetooth v4.0 module

See also: [LINK](/ADS-DV%20InCarPC%20Specification%20(2025%20V1).pdf)

If you are borrowing an ADS-DV from the IMechE using the Loan Service, you may request that it is fitted with one of the 'InCarPC's.

The 2025 wiring configuration brought 1x USB 3.0 port and 1x Ethernet port to the front of the vehicle for use with the sensor plate and the on-board ZED2 camera. The 2026 wiring configuration is under review and may include additional ports.

The 2025 wiring configuration provided 12V Power and vehicle CAN to the 'InCarPC' using the 'Reference Compute' standard connector. This will stay the same for 2026.

## Onboard ZED2 Camera

If you choose not to fit your own sensors to the ADS-DV, the vehicle will be provided with a StereoLabs ZED2 camera.

Note this is the 'end of life' ZED2, and not the later ZED2i.

For further information on the ZED2 please see the StereoLabs website: [LINK](https://support.stereolabs.com/hc/en-us/articles/24824513333015-Where-can-I-find-a-comparison-table-for-the-ZED-Stereo-Cameras)

## Use of the 'Reference Compute' Installation

As an alternative to the 'InCarPC' teams may make use of the 'Reference Compute' installation to fit their own compute platform to the ADS-DV.

This is recommended if possible, since you will have full-time access to your own computing asset and can work with it at all times before, and during, the FS-AI 2026 event. The 'InCarPC's will be shared among several teams.

The 2025 documentation for the 'Reference Compute' installation can be found here: [LINK](/2025%20-%20ReferenceComputePlatform%20-%20Design%20Specifications.pdf)

Note that this will be revised and finalised for 2026, and may include additional ports. The main 12V Power and vehicle CAN connector will not change.

Please be aware that it is possible to fit your own compute platform to the front of the ADS-DV as part of an additional Sensor Plate installation. The same 12V Power and vehicle CAN connector is available at the front. This has the advantage of both sensors and compute being installed onto the same mounting hardware.



----
Don't forget to check the IMechE website regularly for documentation updates:

https://www.imeche.org/events/formula-student/team-information/forms-and-documents

## For specific questions and bug reports, please raise an Issue and tag it with the 'question' label.
#### Otherwise, please use the Github Discussions feature for general forum-style chat.
