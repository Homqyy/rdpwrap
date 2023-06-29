# RDPWrap

For Chinese, please refer to [README-zh.md](./README-zh.md).

## Overview

- Purpose: To extend Remote Desktop Services to Windows, principally aimed at circumventing limitations within the Home Edition.

## Procedure

1. Installation: Double-click on `install.bat`.
2. Implement Patch File:
    1. Enter in the CMD Terminal: `net stop termservice`.
    2. Replace `rdpwrap.ini` in the `C:\Program Files\RDP Wrapper` directory.
    3. Key in the CMD Terminal: `net start termservice`.
3. Invoke the Configuration Manager: Execute `RDPConf.exe`.
4. Verification: Utilize `RDPCheck.exe`.
