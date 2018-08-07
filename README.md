# tcping
Copyright (c) 2002-2008 Marc Kirchner <mail(at)marc(dash)kirchner(dot)de>
Modified by MushrooM93
tcping support ipv4/ipv6 dual-stack in linux, 
the operation is similar to ping but it does not use the ICMP protocol.

Usage:
$gcc tcping.c -o tcping
$cp tcping /usr/bin/
$tcping -v6 ipv6.google.com 80



[-q] [-t timeout_sec] [-u timeout_usec] [-v4|6] <host> <port>
