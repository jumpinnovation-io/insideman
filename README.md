# Insideman v2

Temp website: https://insideman.sitesgpt.com/

InsideMan is a tool enabling different type of  uptime-kuma monitoring behind firewalls, offering capabilities within otherwise restricted network environments

InsideMan is a versatile and advanced software tool designed to facilitate various types of uptime-kuma monitoring behind firewalls, providing comprehensive capabilities within networks that are otherwise restricted or inaccessible. 
This innovative solution serves as a crucial asset for organizations seeking to maintain operational integrity, security, and performance in their network infrastructures.

At its core, InsideMan leverages rest API to penetrate firewall barriers, it enables seamless and undetectable access to critical network resources, allowing for real-time observation and analysis of system uptime and performance metrics.

One of the key features of InsideMan is its ability to adapt to diverse monitoring requirements. Whether it's tracking the availability and responsiveness of web servers, monitoring the uptime of mission-critical applications, 
or ensuring the reliability of network infrastructure components, InsideMan provides a comprehensive tool and functionalities to address a wide range of monitoring needs.

InsideMAN Ver 1.2.90
How to config JSON File

Config VAULES:
"BASEURL": "http://uptimekuma.com/v1/",
    "APIKEY": "7C67AD9F2D6D69EC485625845",
    "ServiceWaitSec": "15",
Don’t Change ANY of the values above.
1)	"Check1": {
2)	        "Enable": "True",
There are 5 Check you can use via the INSIDEMAN 
    Enable The CHECK you want to run
"UPTIMETOKEN": "m787607448-d63da760299cd6625a79324068a45bc5efc849c1",
Get this token from Uptime-kuma dashboard
"TYPE": "6"
There are 6 TYPES
1)	Ping
2)	TCP PORT CHECK
(Must have HOST VAULE & PORT VAULE)
3)	Website Check
4)	SSL CHECK
5)	Checks if an EXE is Running
6)	Check if a Service is Running

"HOST": "https://uptimekuma.com"
The HOST Value is needed for Ping / TCP Check / Website / SSL Check 
"PORT": "3389"
This Value is needed for TCP CHECK (Checks if a port is open)
"CHECKSEC": "30"
This Value is for when to start the check in sec’s ( Check will run every 30 sec)
"EXEAPP" : "C:\test\test.exe"
This is used for (Checks if an EXE is Running) & Check if a Service is Running

BETA Installer here https://github.com/jumpinnovation-io/insideman/releases/download/BETA/InstallService_Install_Store_InsideMAN_v2.exe
