# FS-AI_2020

This is a 'placeholder' for the release of the 2020 verison of the IMechE FS-AI ADS-DV interface software.

Please look at the 2019 repository https://github.com/FS-AI/FS-AI_2019 for an introduction. Don't forget to check out the issues as there is valuable info there: https://github.com/FS-AI/FS-AI_2019/issues

For 2020 the plan is to release the interface as C source code that compiles on Linux and uses SocketCAN. No binary library will be used. This will improve flexibility but please note that technical support will only be provided for the base interface code, not any derivatives / forks.

The interface will be developed and tested on the InCarPC CQ67G fitted to the ADS-DV. Additional testing is likely to be performed on a Dell Inspiron 5590 laptop, Rasberry Pi 4 4GB and BeagleBone Blue. OS versions TBD but Ubuntu 18.04 64bit will be used where available.

Also, training material is under preparation to provide a test environment that replicates the CAN interface of the ADS-DV. This will use Arduino hardware to represent the real-time nature of the ADS-DV embedded ECU. If you wish to build this test environment the following hardware is recommended for purchase:

Any Arduino Uno compatible board.
An Arduino Uno compatible CAN shield. Either the Seeed Studio V2 or the Sparkfun / SKPang should be suitable.
(Optionally) a display shield.



Don't forget to check the IMechE website regularly for documentation updates:

https://www.imeche.org/events/formula-student/team-information/forms-and-documents
