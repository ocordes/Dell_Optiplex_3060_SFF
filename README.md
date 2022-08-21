# Dell_Optiplex_3060_SFF


This is a working configuration for a Dell Optioplex 3060 SFF, which supports MacOS Monterey (>=12.5.1) and also MacOS Ventura (beta).

What works:
 * S-ATA disks
 * NVME SSDs (see <https://dortania.github.io/Anti-Hackintosh-Buyers-Guide/Storage.html> for a special guide, since not all SSDs are supported)
 * Realtek network card (with kext)
 * Audio (not checked every port, but the internal speaker is working ...)
 * WLAN/BT with BMC94360cs2 PCIe card 
 * internal intel graphics UHD 630 (HDMI- and DP-port)
 * two monitor modes
 * all USB ports are natively supported (no injection)
 
 
 Notes:
 
  * the 3060 SFF main board has no additional USB header, so you need a cable (USB header -> USB-A) to connect the BT part to an existing USB port!
  * for the two monitor mode, I testest a HDMI-DP-connector and a DVI-HDMI-connector, DVI-DP-connector is not working!
