SuperUS by Chainfire

XDA Profile
http://forum.xda-developers.com/member.php?u=631273

XDA Thread
http://forum.xda-developers.com/showthread.php?t=1538053

Update Links

TWRP / FlashFire installable ZIP:

Stable: http://download.chainfire.eu/supersu-stable

Beta: http://download.chainfire.eu/supersu-beta

Latest: http://download.chainfire.eu/supersu


Must delete folder system/extras/su


Must add this to init.(DEVICE).rc in device/(MANUFACTURER)/(DEVICE):

service initd /system/bin/initd.sh
    class main
    oneshot