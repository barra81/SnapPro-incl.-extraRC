SnapPro-incl.-extraRC
=====================
copy the Snap_Pro folder into yourmissionfile.pbo\sys



in your init.sqf 

ADD

call compile preprocessFileLineNumbers "sys\snap_pro\compiles.sqf";


BELOW 

the other Compiles.sqf


______________________________________________________________________________________

in your description.ext

ADD


#include "sys\snap_pro\snappoints.hpp"
