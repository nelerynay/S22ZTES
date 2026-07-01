# About CHK_COMM
CHK_COMM is one of protocol used in Inverter air conditioner to allow communication between Indoor and Outdoor to maintain speed, temperature and modes, CHK_COMM is still under development.
If CHK_COMM cable is not present, the unit will not start.

## Inside CHK_COMM
CHK_COMM is located inside indoor PCB, the same location and address as RECEIV. it works really simple
> if COM.present == false then
> U4.enabled == true
> end
> 
U4 is the responsible error code for "communication error/abnormality", U4 is also located inside indoor PCB.

## CHK_COMM Development

#### REVISION 1 
- Added CHK_COMM cable
- Added error code
- Added script
