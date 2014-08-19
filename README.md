# FreeBox #

## What is FreeBox? ##
FreeBox is a device to crack WIFI. The hardware is mainly a Cubieboard2(with linux) and the software is based on the code from Reaver.

## How is it going? ##
This project is divided into two stages. Now we are at the first phase.
### Stage 1: ###
In this stage, our aim is to setup the building environment and to comfirm the viability. We do nothing but make existing projects functional. We would like to install Linux on cubieboard, update the kernel for the sake of experiment. Then we download, compile and install the aircrack-ng package and reaver package, and give those tools a try on Cubieboard.

If you want to follow up with me, please check [the diaries](#Diaries). Later, when I complete the task successfully, the approaches will be documented.

### Stage 2: ###
If Stage1 is a success, it means that we can crack wifi with the board. But that's not FreeBox! We don't want to carry a screem and keyboard when we doing crack outdoors. The solution is to reconstruct the reaver tool package and some other tools related to be suitble for cubieboard. To achieve the target, we alse need to build drivers for 1602A and a portable input device.

## Notice ##
It is **illegal** to crack other users' WIFI without permission!

