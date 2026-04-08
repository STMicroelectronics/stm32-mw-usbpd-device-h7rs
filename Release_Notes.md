

# Release Notes for
# <mark>STM32 USB-C Power Delivery H7RS Device Driver</mark>
Copyright &copy; 2022 STMicroelectronics\

[![ST logo](_htmresc/st_logo_2020.png)](https://www.st.com)

# Purpose

The USB-PD device driver provides a set of functions to manage the physical layer (i.e. low level of the type C state machine and low level of message transport). This includes :

- Type C state machine: SRC, SNK or DRP

- Physical layer : message handling SOP, SOP', SOP'', HARDRESET, ...

- Timer server to handle GOODCRC, PRL repetition timing

The USB-PD device driver is developed following the Universal Serial Bus Power Delivery Specification Revision 3.2, V1.1 (October, 2024) and Universal Serial Bus type-C Cable
and Connector Specification, Revision 2.0 (August, 2019).

# Update History

<label for="collapse-section6" aria-hidden="true">V1.3.0 / 23-Jan-2026</label>
<div>

## Main Changes

  Headline
  --------
  Add support of Debug Accessory Mode (DAM) in Sink mode

## Known limitations

  Outstanding bugs list : None

  Requirements not met or planned in a forthcoming release : None

## Supported Devices and boards

  All STM32H7RSxx devices embedding USBPD IP

## Backward compatibility

  No compatibility break with previous version

## Dependencies

 This software release is compatible with USB-C Power Delivery Core Stack Library v5.4.0

</div>

<label for="collapse-section5" aria-hidden="true">V1.2.2 / 25-Sep-2025</label>
<div>

## Main Changes

  Headline
  --------
  SLA0044 Legal terms updated to latest revision (Rev 6 / October 2025)

## Known limitations

  Outstanding bugs list : None

  Requirements not met or planned in a forthcoming release : None

## Supported Devices and boards

  All STM32H7RSxx devices embedding USBPD IP

## Backward compatibility

  No compatibility break with previous version

## Dependencies

 This software release is compatible with USB-C Power Delivery Core Stack Library v5.3.1

</div>

<label for="collapse-section4" aria-hidden="true">V1.2.1 / 13-Dec-2023</label>
<div>

## Main Changes

### Initial release

## Contents
**Fixed bugs list**

  Headline
  --------
  Fix fast role swap compilation error in no PD context
  Remove useless defines


## Known limitations

  Outstanding bugs list : None

  Requirements not met or planned in a forthcoming release : None

## Development Toolchains and Compilers

- IAR Embedded Workbench for ARM (EWARM) toolchain V9.20.1
- RealView Microcontroller Development Kit (MDK-ARM) toolchain V5.38a
- STM32CubeIDE V1.15.0 (GCC12)

## Supported Devices and boards

  All STM32H7RSxx devices embedding USBPD IP

## Backward compatibility

  No compatibility break with previous version

## Dependencies

 This software release is compatible with USB-C Power Delivery Core Stack Library v5.0.0

</div>

<label for="collapse-section3" aria-hidden="true">V1.2.0 / 31-May-2023</label>
<div>

## Main Changes

### Initial release

## Contents
**Fixed bugs list**

  Headline
  --------
  Avoid issue when an AMS is interrupted
  Fix definition of FRSTX pins for series that are using only a common pin
  Remove not used CRC init
  Fix missing definitions
  MCUAstyle corrections

## Known limitations

  Outstanding bugs list : None

  Requirements not met or planned in a forthcoming release : None

## Development Toolchains and Compilers

- IAR Embedded Workbench for ARM (EWARM) toolchain V9.20.1
- RealView Microcontroller Development Kit (MDK-ARM) toolchain V5.31
- STM32CubeIDE v1.9.0

## Supported Devices and boards

  All STM32H7RSxx devices embedding USBPD IP

## Backward compatibility

  No compatibility break with previous version

## Dependencies

 This software release is compatible with USB-C Power Delivery Core Stack Library v5.0.0

</div>

<label for="collapse-section2" aria-hidden="true">V1.1.0 / 29-Nov-2022</label>
<div>

## Main Changes

### Initial release

## Contents
**Fixed bugs list**

  Headline
  --------
  Implementation of UCPD software trimming procedure.

## Known limitations

  Outstanding bugs list : None

  Requirements not met or planned in a forthcoming release : None

## Development Toolchains and Compilers

- IAR Embedded Workbench for ARM (EWARM) toolchain V9.20.1
- RealView Microcontroller Development Kit (MDK-ARM) toolchain V5.31
- STM32CubeIDE v1.9.0

## Supported Devices and boards

  All STM32H7RSxx devices embedding USBPD IP

## Backward compatibility

  No compatibility break with previous version

## Dependencies

 This software release is compatible with USB-C Power Delivery Core Stack Library v5.0.0

</div>

<label for="collapse-section1" aria-hidden="true">V1.0.0 / 29-Jun-2022</label>
<div>

## Main Changes

### Initial release

## Contents
**Fixed bugs list**

  Headline
  --------
  First official version for STM32H7RSxx device

## Known limitations

  Outstanding bugs list : None

  Requirements not met or planned in a forthcoming release : None

## Development Toolchains and Compilers

- IAR Embedded Workbench for ARM (EWARM) toolchain V9.20.1
- RealView Microcontroller Development Kit (MDK-ARM) toolchain V5.31
- STM32CubeIDE v1.9.0

## Supported Devices and boards

  All STM32H7RSxx devices embedding USBPD IP

## Backward compatibility

  No compatibility break with previous version

## Dependencies

 This software release is compatible with USB-C Power Delivery Core Stack Library v5.0.0

</div>


For complete documentation on **STM32 32-bit Arm Cortex MCUs**,
visit: [http://www.st.com/STM32](http://www.st.com/STM32)

This release note uses up to date web standards and, for this reason, should not
be opened with Internet Explorer but preferably with popular browsers such as
Google Chrome, Mozilla Firefox, Opera or Microsoft Edge.