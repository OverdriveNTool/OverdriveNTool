# OverdriveNTool

![1](https://overdriventool.eu/wp-content/uploads/2020/12/isz5q33-esy.png)

**OverdriveNTool** is a simple program for adjusting the parameters of AMD GPUs. Although it has not been translated into Russian, its interface will be understandable to anyone who has ever worked with utilities for overclocking video adapters.

With **OverdriveNTool**, you can change the frequency settings of the AMD graphics chip and the used video memory. In addition, the user can control the voltage and program the video card or processor to reduce the voltage consumption when a certain temperature is reached. This will help prevent overheating of the device.

# System requirements:
- **System**: Windows 7 and newer assemblies.
- **GPU**: AMD 290, 290x, 380, 380x, 390, 390x, Fury, Fury X, Nano, 4xx, 5xx series, Vega 56, Vega 64, Radeon VII.
- **Driver**: 17.7.2 and newer.

# Overclocking AMD GPUs in OverdriveNTool
Working with the **OverdriveNTool** utility is simple and accessible to any user. To use it, you can use any folder on the computer media, preferably created only for this program.

The folder with the program will contain the OverdriveNTool.exe utility itself, as well as two files for its management:

1. File for starting the program in automatic mode (in this case, overdrive_BAT.bat).
2. The profile file, in which the overclocking settings will be recorded,
downvolting, fan speeds and temperature conditions for video cards
(the OverdriveNTool.ini file that is automatically generated when
saving any profile).
# Update History

**0.2.9 (14.06.2020)<br>
-fixed: Application recognizes driver as not installed in 20.5.1 (or newer)<br>
-added profiles reordering**

**0.2.8 (16.04.2019)<br>
-support for Fan Curve and Memory timing level introduced in 18.12.2 driver (Removed Fan Min, Fan Max, Fan Target Temp and Power Temp values)<br>
-added -wait command<br>
-added possibility to apply or reset all supported gpus at once by using Ctrl + Apply or Ctrl + Reset<br>
-fixed bug with GPUs and profiles duplication when use -showgui command<br>
-added support for Radeon VII**

**0.2.7 (09.11.2018)<br>
-fixed: console messages may not be displayed on Windows 10<br>
-added possibility to open .reg files with SoftPowerPlayTable editor<br>
-added optional auto reset before apply<br>
-added -t and -showgui commands<br>
-added optional displaying an error when values are not as expected after apply<br>
-for errors with ErrorCode -1 on apply now current driver limits are displayed**

**0.2.6 (16.05.2018)<br>
-added ini file backup feature<br>
-added an option to hide ADL_ERR_NOT_SUPPORTED errors<br>
-fixed: console messages may not be displayed on some systems<br>
-added -getcurrent and -ac command to apply values without using profile**

**0.2.5 (13.02.2018)<br>
-r command now also resets I2C offset and LLC when I2C is enabled and supported<br>
-consoleonly command messages are now coloured<br>
-fixed: ini file may lose it’s content on PC crash**

**0.2.4 (18.01.2018)<br>
-fixed bug in QEMU PCI passthrough with showing only one GPU on multiGPU configs<br>
-updated error messages to give more info**

**0.2.3 (14.12.2017)<br>
-added possibility to use * as gpu_id in commandline**

**0.2.2 (23.11.2017)<br>
-added Friendly name and Registry key to gpu additional info<br>
-SoftPowerPlayTable editor can now automatically restart GPU when click «Save» or «Delete»**

**0.2.1 (19.10.2017)<br>
-added SoftPowerPlayTable editor<br>
-commandline fix to avoid error messages when driver is not installed<br>
-added option to not include unsupported GPUs on the GPU list**

**0.2.0 (02.10.2017)<br>
-added possibility to deactivate Fan section**

**0.1.9 (25.09.2017)<br>
-added -consoleonly command in commandline<br>
-added I2C support for up9505<br>
-added Adapter index to gpu additional info<br>
-GPU displayed on startup changed to first supported rather than first one<br>
-Vega FE support in Pro mode<br>
-fixed ini bug with random values for I2C when new profile is created**

**0.1.8 (08.09.2017)<br>
-fixed dpi bug introduced in 0.1.7<br>
-added I2C support for IR3567B**

**0.1.7 (26.08.2017)<br>
-Now additional info about GPU is optional (system menu->settings)<br>
-changed Pstate disabling/enabling to single click<br>
-commandline support for more than 10 GPUs<br>
-Power Target now allows negative values**

**0.1.6 (19.08.2017)<br>
-changed GPU list sorting to be like in other apps, for easier gpu recognition.**

**0.1.5 (18.08.2017):<br>
-changed tab order for edit controls<br>
-fixed bug with not listing all GPU’s on some configs**

**0.1.4 (17.08.2017):<br>
— added possibility to disable/enable each P state.**

**0.1.3 (12.08.2017):<br>
— added few more commands**

**0.1.2 (08.08.2017):<br>
— added -c command in commandline**

**0.1.1 (07.08.2017):<br>
— prevent using commandline on unsupported cards<br>
— fixed bug with showing only first GPU on multiGPU configs**

**0.1 (06.08.2017):<br>
— initial release**
