### New changes
* Fix picopass plugin (revert OFW PR 1701)
* Updated universal remote assets (by @Amec0e)
### Changes from previous release
* Add SubGhz Bruteforce plugin (by @Ganapati & @xMasterX) (PR #57) - saving functionality and many fixes by @xMasterX
* Fix GUI and add new icon in LF-RFID App (icon by @Svaarich)
* GUI Changes to LFRFID Fuzzer
* New Battery info (from @theeogflip) (PR #60)
* NRFSniff: Adds unique count display (by @Graf3x) (PR #56)
* Updated universal remote assets (by @Amec0e)
* OFW: RFID app port to plain C
* OFW: SubGhz: fix decoder keeloq
* OFW PR: Picopass: detect and show SE / SIO - OFW PR 1701 (by pcunning)
* OFW PR: Fix MFClassic 4k reading - OFW PR 1712 (by Astrrra)
* OFW: SubGhz: handle missing key in cryptostore. Lib: lower default display contrast.
* OFW: Furi: wait for timer wind down in destructor 

**Note: To avoid issues prefer installing using web updater or by self update package, all needed assets will be installed**

Self-update package (update from microSD) - `flipper-z-f7-update-(version).zip` or `.tgz` for iOS mobile app

DFU for update using qFlipper - `flipper-z-f7-full-(version).dfu`

If using DFU update method, download this archive and unpack it to your microSD, replacing all files except files you have edited manually -
`sd-card-(version).zip`

