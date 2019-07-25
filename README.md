# XLR8 Beta Images

This repository is where we will share Beta FPGA images for the XLR8 family boards.  These images contain new or experimental functionality that may not yet be included in formally released XLR8 FPGA images.

## FPGA Image Upload Tool: *xlr8reconfig*
We have provided a command line tool called xlr8reconfig that allows you to update the FPGA image from the command line.  This is the same tool that runs when you update the FPGA via the "Burn Bootloader" command in the Arduino IDE.

## Instructions:

***Tool Location***

The xlr8reconfig tool is included as part of our Arduino boards package and is located in the following directories, depending on your operating system.

Mac: 

~/Library/Arduino15/packages/alorium/tools/xlr8reconfig/1.3.0/

Windows:

C:/users/YourUserName/AppData(hidden folder)/Local/Packages/Arduino15/packages/alorium/tools/xlr8reconfig/1.3.0/


***Command***

Navigate to the directory for xlr8reconfig and use the following command syntax to start the FPGA loading process:

Mac:

xlr8reconfig –rpd_file <path_and_name_of_rpd_file> --load_image 1

Windows:

xlr8reconfig.exe -v --rpd_file <path_and_name_of_rpd_file> --load_image 1
