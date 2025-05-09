### KIT_PSC3M5_2GO BSP
PSOC™ Control C3M5 Compact Kit - This board has the PSOC™ Control C3M5 device with debugger, IPM and BLDC motor.     Equipped with an Arm® Cortex®-M33 based PSOC™ Control microcontroller from Infineon Technologies AG,     the PSOC™ Control C3M5 Compact Kit is designed to demonstrate the capabilities of Infineon's PSOC™ Control C3M5     Microcontroller for motor control applications in a standalone plug and play form factor.     
**Note:**
Programming this kit requires installing 
[SEGGER J-Link software](https://www.segger.com/downloads/jlink/#J-LinkSoftwareAndDocumentationPack)

NOTE: BSPs are versioned by family. This means that version 1.2.0 of any BSP in a family (eg: PSoC™ 6) will have the same software maturity level. However, not all updates are necessarily applicable for each BSP in the family so not all version numbers will exist for each board. Additionally, new BSPs may not start at version 1.0.0. In the event of adding a common feature across all BSPs, the libraries are assigned the same version number. For example if BSP_A is at v1.3.0 and BSP_B is at v1.2.0, the event will trigger a version update to v1.4.0 for both BSP_A and BSP_B. This allows the common feature to be tracked in a consistent way.

### What's Included?
The KIT_PSC3M5_2GO library includes the following:
* BSP specific makefile to configure the build process for the board
* cybsp.c/h files to initialize the board and any system peripherals
* cybsp_types.h file describing basic board setup
* Linker script & startup code for GCC, IAR, and ARM toolchains
* Configurator design files (and generated code) to setup board specific peripherals
* .lib file references for all dependent libraries
* API documentation

### What Changed?
#### v1.0.4
* MPN CYW89829B01MKSBG to CYW89829B0232 update release for CYW89829
#### v1.0.3
* Initial production release for CYW89829
#### v1.0.2
* Initial production release for CYW20829
#### v1.0.1
* MTB 3.0 and pre-production release 
#### v0.5.0
* Initial pre-production release

### Supported Software and Tools
This version of the KIT_PSC3M5_2GO BSP was validated for compatibility with the following Software and Tools:

| Software and Tools                        | Version |
| :---                                      | :----:  |
| ModusToolbox™ Software Environment        | 3.1.0   |
| GCC Compiler                              | 11.3.1  |
| IAR Compiler                              | 9.40.2  |
| ARM Compiler                              | 6.16    |

Minimum required ModusToolbox™ Software Environment: v3.0.0

### More information
* [KIT_PSC3M5_2GO BSP API Reference Manual][api]
* [KIT_PSC3M5_2GO Documentation](http://www.infineon.com/KIT_PSC3M5_2GO)
* [Cypress Semiconductor, an Infineon Technologies Company](http://www.cypress.com)
* [Infineon GitHub](https://github.com/infineon)
* [ModusToolbox™](https://www.cypress.com/products/modustoolbox-software-environment)

[api]: https://infineon.github.io/TARGET_KIT_PSC3M5_2GO/html/modules.html

---
© Cypress Semiconductor Corporation (an Infineon company) or an affiliate of Cypress Semiconductor Corporation, 2019-2022.