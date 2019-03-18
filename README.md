# hp c7000 blade
zabbix template tested on zabbix v3.4
translate most mib oid to numberic using script so do not need extra mib file in zabbix server.
here are the value maps(already set in xml file):

Value Map:

Host - Status
0 ⇒ Not available
1 ⇒ Available
2 ⇒ Unknown

HP - Accelerator Board Status
1 ⇒ Other
2 ⇒ Invalid
3 ⇒ Enabled
4 ⇒ Temporarily Disabled
5 ⇒ Permanently Disabled

HP - Battery Status
1 ⇒ Other
2 ⇒ Ok
3 ⇒ Charging
4 ⇒ Failed
5 ⇒ Degraded
6 ⇒ Not Present

HP - Condition
1 ⇒ Other
2 ⇒ Ok
3 ⇒ Degraded
4 ⇒ Failed
-----------------
HP - Controller Board Status
1 ⇒ Other
2 ⇒ Ok
3 ⇒ General Failure
4 ⇒ Cable Problem
5 ⇒ Powered Off

HP - Controller Redundancy Type
1 ⇒ Other
2 ⇒ Not Redundant
3 ⇒ driverDuplexing
4 ⇒ fwActiveStandby
5 ⇒ fwPrimarySecondary

HP - Controller Role
1 ⇒ Other
2 ⇒ Not Duplexed
3 ⇒ Active
4 ⇒ Backup
-----------------------------
HP - Enclosure Manager Roles
1 ⇒ StandBy
2 ⇒ Active

HP - ifAdminStatus
1 ⇒ Up
2 ⇒ Down
3 ⇒ Testing

HP - ifOperStatus
1 ⇒ Up
2 ⇒ Down
3 ⇒ Testing

HP - Logical Drive Status
2 ⇒ Ok
3 ⇒ Failed
4 ⇒ Unconfigured
5 ⇒ Recovering
6 ⇒ Ready Rebuild
7 ⇒ Rebuilding
8 ⇒ Wrong Drive
9 ⇒ Bad Connect
10 ⇒ Overheating
11 ⇒ Shutdown
12 ⇒ Expanding
13 ⇒ Not Available
14 ⇒ Queued For Expansion

HP - Network Connector Device Type
1 ⇒ No Connect
2 ⇒ Network
3 ⇒ Fibre Channel
4 ⇒ SAS
5 ⇒ Inifiband
6 ⇒ pciexpress
----------------------------
HP - Physical Drive Location
1 ⇒ Other
2 ⇒ Internal
3 ⇒ External
4 ⇒ proLiant

HP - Power Supply Input Power Status
1 ⇒ No Error
2 ⇒ Line Over Voltage
3 ⇒ Line Under Voltage
4 ⇒ Line Hit
5 ⇒ Brown Out
6 ⇒ Line Power Loss

HP - Power Supply Status
1 ⇒ No Error
2 ⇒ General Failure
3 ⇒ Bist Failure
4 ⇒ Fan Failure
5 ⇒ Temp Failure
6 ⇒ Interclock Open
7 ⇒ EPROM Failed
8 ⇒ Vref Failed
9 ⇒ DAC Failed
10 ⇒ RAM Test Failed
11 ⇒ Voltage Channel Failed
12 ⇒ Orring Diode Failed
13 ⇒ Brown Out
14 ⇒ Giveup On Startup
15 ⇒ Nvram Failed
16 ⇒ Calibration Table Invalid

HP - Present Device
1 ⇒ Other
2 ⇒ Absent
3 ⇒ Present

HP - S.M.A.R.T Drive Status
1 ⇒ Other
2 ⇒ Ok
3 ⇒ Replace Drive

HP - Server Blade Power
1 ⇒ Other
2 ⇒ On
3 ⇒ Off
4 ⇒ Power staged Off
5 ⇒ Reboot

