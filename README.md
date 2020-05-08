# stm32-cube-modbus  
This repo holds the code for the ST CubeMX/IDE pack allowing the integration of Modbus communication within projects.
So far, only the RTU media has been implemented, but we hope to release the TCP/IP version (leveraging lwip) within 2020.

## Installation
### Pre-built pack
  1. Open the ST CubeMX/IDE software
  2. Access the additional software package management
  3. Install the I-CUBE-MOBUS package
### Self-built pack
  1. Clone this repo
  2. Add 7z to your PATH environment variable  
  3. **Windows** : Launch gen_pack.bat | **Linux** : Launch gen_pack.sh  
  4. Open the ST CubeMX/IDE software
  5. Access the additional software package management
  6. Install through the "From Local" option  
## Usage
After you have configured all necessary parameters within the ST CubeMX/DE interface, you only need to edit the file called *mb_callbacks.c*.
The rest has already been setup for you.  
Enjoy!
