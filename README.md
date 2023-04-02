# ctf-time
Simple tool to automate the first few tasks of a TryHackMe CTF challenge.

Almost every TryHackMe CTF I do begins with a few basic steps:
  -creating a new directory to organize my notes/scans/files related to the CTF
  -scanning the target IP with Nmap
  -using SearchSploit to look up the software/version running on the open ports
  -performing directory fuzzing on any http servers found using FFUF
  
This is a simple tool to automate that process
In orer to run this tool you will need Nmap, SearchSploit, and FFUF installed.
  -If you are using a Kali machine then these tools will come pre-installed.
  
Have fun and happy hunting :)
