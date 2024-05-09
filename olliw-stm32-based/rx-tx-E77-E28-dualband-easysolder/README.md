# mLRS Hardware: Easy-To-Solder Board E77 E22 dual band #

For the through-hole parts, Mouser parts numbers are listed in the electric scheme. A list of parts is also available here https://www.mouser.de/ProjectManager/ProjectDetail.aspx?AccessID=b60c19cf3a.

These are of course only suggestions, these and equally suitable parts can be sourced from many places.

The EByte E77-900M22S module is relatively new. It can be ordered from the "EBYTE Official Store" on AliExpress.

The EByte E28-2G4M27SX module is needed for a dual-band build. It is around for some while and can be ordered on AliExpress from several sources (the "EBYTE Official Store" may not be the cheapest offer).

ATTENTION: EByte has silently changed the hardware of the E77 module around the beginning of 2024. These newer modules use a (better) TCXO, whereas the older modules use a ceramic crystal oscillator. According to the datasheet the newer modules can be identified by a serial number SN ≥ 3202995. The implications of the hardware change are not fully collected. The new and old modules require different firmwares. Also, some reports suggest that one needs to use SWRST for flashing via SWD.

