# TM4C123-Setup-Files
Updated drivers and fix for Youtube Video "TM4C123 Tutorial: Setting Up The Development Environment" Channel: "All About EE"

2024 Fix:

1. The original link to the Texas Instruments CMSIS Headers is broken. Retrieve the download from the "CMSIS Headers" folder in the repository. (The original download was accessed from the link https://www.ti.com/tool/CMSIS_DEVICE_HEADERS through the Wayback Machine archive in 2017 and before.)

2. I could not locate the device "TI TM4C1233H6PM" as shown on video, however, I used "TI LM4F120H5QR" and it worked perfectly

3. If encountering approximately three error pop-ups when attempting to run the program on the board, follow these steps:
   a. Update drivers by navigating to the "Stellaris Drivers" folder in the repository.
   b. Open the Device Manager and locate any missing drivers.
   c. Manually search for the drivers in the "Stellaris Drivers" folder.

(Original download was obtained from https://www.ti.com/tool/STELLARIS_ICDI_DRIVERS)
