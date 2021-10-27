# PFS_gen2cmd_eng
Gen2 commnads for PFS engineering observation
  - This repository includes only commands written by S. Koshida. 
# Skeleton file list
  - SETUPFIELD.sk       : Slew the telescope to a certain R.A and Dec. No interaction with PFS.
  - SETUPFIELD_AZEL.sk  : Slew the telescope to a certain azimuth and elevation. No interaction with PFS.
  - AGEXP.sk            : Take exposures of AG cameras at an actual position of the telescope.
  - PFS_FOCUSAG.sk      : Start focusing sequence using AG cameras at an actual position of the telescope
  - PFS_STARTAG.sk      : Start AG sequence for a pfsDesign or an actual position of the telescope
  - AGON.sk             : Resume the AG sequence from the last exposure
  - AGOFF.sk            : Stop the AG sequence
  - AGRECONF.sk         : Reconfigure the AG parameters (Currently exposure time and cadence only)
