Description
===========

Port scan driver is one of the monitoring drivers in tacker for VNF management.
It uses portscanning method to check the application status in VNF.

Until now, Tacker monitoring drivers can check network(ping) and
application(using HTTP URL).

Therefore, port monitoring driver helps for auto
healing of VNFC level and it is a useful when checking the
VNF inside status too.

It can check a specific port number for about a mgmt_ip.
You can define port  that you want to check in the VNFD.
Default value is 22.

