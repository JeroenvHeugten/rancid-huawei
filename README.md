rancid-huawei
=============

Small script to let rancid collect configuration from Huawei networking devices

Quick fix for Huawei devices, in this case Secospace AntiDDoS series, ugly
script, feel free to improve it. Plenty of things that could have done better.

Installation:

- Update /usr/lib/rancid/bin/rancid-fe,  add "'huawei' => 'huarancid',"
- Update /networkdc2/router.db,  add "DEVICENAME:huawei:up"
- Place the huarancid script in /usr/lib/rancid/bin/
- Add device to .cloginrc

