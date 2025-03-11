# ESXi-HP-Smart-Array-SSD-Wear

Zabbix template to measure non-HP branded SSDs connected to HP Smart Array controller on servers running ESXi.

Check SSD datasheet for TBW, import template, change trigger values and intervals.

For best performance without random errors in Latest Data it will be better to set interval for Data Retrieval different from Physical Drives Discovery and Item prototypes.



Tested on:
- HPE ProLiant G8, 9 and 10 series servers with HP branded RAID controllers (200 series not included).
- ESXi 7 and 8. Sure it will work on older versions of ESXi.
- Intel D3-S4510 Series, Samsung 870 EVO, Crucial MX500 series SATA SSDs.
