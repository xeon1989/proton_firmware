# Proton IHU APK's Sideload

This repo doesn't show method on how to install APKs to your IHU. But only serve as a place to track status of it.

Some car like EXORA doesn't have direct link between car system and IHU and it should be safe to meddle with it. However, for other such as X70 you must exercise caution and I don't recommend to sideload it.

## EXORA / PERSONA / IRIZ - GKUI
|Model|Firmware|Method|Comment|
|-----|--------|------|-------|
|EXORA | GKUI (all version) V3.1.3E V3.1.5E V3.2.6E | Loophole | Use exec on Factory Settings
|PERSONA/IRIZ | GKUI (all version) V3.1.5E | Loophole | Use exec on Factory Settings

## PERSONA MC2 / IRIZ MC3 - ATLAS
|Model|Firmware|Method|Comment|
|-----|--------|------|-------|
|IRIZ | ATLAS | Loophole | Hole from one of the app
|PERSONA MC2 | ATLAS SWPERSO1213H1803 | Loophole | Hole from one of the app 

## X70
|Model|Firmware|Method|Comment|
|-----|--------|------|-------|
|X70 | GKUI (CBU/Older unknown version) | Engineer Mode | Enter engineer mode via dialer code and select install APK
|X70 | GKUI V4.0.3(IC4) and below | Exploit | Crafting special file
|X70 | ATLAS SWNL3RB0814H1091 | Simple Flags | |
|X70 | ATLAS SWNL3R... | Simple Flags | |

## X50 (H = Premium/Flagship, L = Executive/Standard)
|HW|OS|Firmware|Method|Comment|
|--|--|--------|------|-------|
|H090 | GKUI19 | SW0SXRA0911H5063.00374 | | 
|H090 | GKUI19 | SW0SXRA1201H5064.00379 | Init Script | USB\b832bc61472727635baffcf25dd28e9f239273e2\...sh
|H200 | GKUI19 | SW0SXRA0121H5167.00411 | Init Script | USB\b832bc61472727635baffcf25dd28e9f239273e2\...sh
|H200 | GKUI19 | SW0SXRA0121L5167.00412 | Init Script | USB\b832bc61472727635baffcf25dd28e9f239273e2\...sh
|H090/H200 | ATLAS | SW0SXRA0616H5170.00581 | | 
|H090/H200 | ATLAS | SW0SXRA0616L5170.00582 | | 
| | ATLAS | SW0SXRA0929H5170.00598 | | 
|H090/H200 | ATLAS | SW0SXRA1124H5170.00617 SW0SXRA1124L5170.00618 (v1) | Init Script | Able to install APKs with simple file copy, but cannot invoke through installer due to APK must be signed and coming from AStore
|H090/H200 | ATLAS | SW0SXRA1124H5170.00617 SW0SXRA1124L5170.00618 (v2) | Downgrade | Same version number, but ACOTech silently push the updates with removal of init script backdoor