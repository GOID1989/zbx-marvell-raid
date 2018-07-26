# zbx-marvell-raid
Zabbix template and PowerShell script for monitoring Marvell RAID Controller

The script may generate LLD data for Marvell RAID Controllers, Virtual Drives (other word Logical).
Physical Drives not processed because not suitable info provided from MSU.

Also it can takes some components health status. It's using Marvel Storage Utility to
connect to controller, so you must install it first:
https://support.hpe.com/hpsc/swd/public/detail?swItemId=MTX_17d87af242a144cbb3a954352c&swEnvO