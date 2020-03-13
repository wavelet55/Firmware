DireenTech DtiObF4R Target Support README
=========================================

Harry Direen, Ph.D., P.E., hdireen@direentech.com
Randal Direen, Ph.D., rdireen@direentech.com
www.DireenTech.com

Academy Center for UAS Research
Department of Electrical and Computer Engineering
HQ USAFA/DFEC
https://www.usafa.edu/research/research-centers/center-unmanned-aircraft-systems/

Started: March 2020

The DireenTech DtiObF4R is a flight control board similar to and
started from the OmnibusF4. The flight control board is being
designed by DireenTech under a research grant for the Air Force Academy.
Contract No: FA7000-19-2-0037
The board and software is expected to diverge from the OmnibusF4 design.

"OmnibusF4" is not a product name per se, but rather a design spec
that many product vendors within the drone flight management unit
(FMU) community adhere to. The spec defines the major components, and
how those components are wired into the STM32F405RGT6 microcontroller.

Reference the readme.txt file in: platforms/nuttx/Nuttx/boards/
arm/stm32/dtiobf4r  directory for board hardware definitions 
and other specific build instructions.

Build Instructions
==================

The boards/arm/stm32/omnibusf4/nsh/defconfig file creates a basic setup, and
includes drivers for all supported onboard chips. The console and
command prompt are sent to USART3.

