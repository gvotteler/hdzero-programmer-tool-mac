HDzero Programmer Tool - For MAC
Developed by - Gunther_FPV (Gunther Votteler)
Github - https://github.com/gvotteler
Version 1.0

#############################################
This tool provide a usefull way to update or flash your Hdzero VTX's.

#############################################
Pre-requieriments.

Before tu use this tool YOU need follow the next steps.

1. Open your terminal app (CLI)

2. Install brew in your MAC, if ypu not have installed
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

3. Install flasroom
brew install flashrom

4. Run this commands in the same folder that you have the HDZeroProgrammerTool.app
xattr -dr com.apple.quarantine "HDZeroProgrammerTool.app"
codesign --deep --force --sign - "HDZeroProgrammerTool.app"

5. If you want, move the app to Applications folder or desire folder.

6. Download the Hdzero firmware that ypu want flash in your VTX (https://www.hd-zero.com/document) section VTX Firmware

7. Extract the zip file, locate the zip file of your vtx and extract too.

8. Open HDZeroProgrammerTool.app, borew the folder and choose the .bin file extracted.

9. Flash.

10. Optional (If you want, create a backup of the current firwamre befor to flash)


##########################################################################################
##########################################################################################




