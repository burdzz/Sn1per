## CHANGELOG:
* v2.0b - Added help option --help
* v2.0a - Fixed issue with ssh-audit
* v2.0a - Fixed issue with 'discover' mode
* v2.0 - Updated sub-domain takeover list
* v2.0 - Improved scan performance for stealth, airstrike and discover modes
* v2.0 - Removed jexboss due to clear screen issue with output
* v2.0 - Auto loot directory sorting for all tools
* v2.0 - Updated install.sh package list
* v1.9c - Enabled BruteX automated brute force attacks
* v1.9b - Fixed MSSQL port 1433/tcp port scan check (@hacktrack)
* v1.9a - Removed testssl script from stealth mode scans
* v1.9 - Added Ubuntu docker image for Sn1per (@menzow)
* v1.9 - Added automatic loot directory sorting for all modes
* v1.9 - Added MSSQL port 1433/tcp checks
* v1.9 - Added SNMP port 162/tcp checks (@hexageek)
* v1.9 - Added nslookup to install.sh
* v1.9 - Fixed install.sh dependency duplicates
* v1.8c - Added -A option to all NMap port scans
* v1.8c - Fixed install.sh permission issue
* v1.8c - Fixed install.sh cleanup options
* v1.8c - Added ssh-audit
* v1.8c - Added install directory (/usr/share/sniper/) to install script for universal access
* v1.8c - Fixed issue with Metasploit SSH scans
* v1.8c - Added auto-update to install.sh to automatically pull latest github release
* v1.8b - Fixed bug with NMap UDP scan options
* v1.8b - Fixed install.sh dependencies 
* v1.8b - Fixed jexboss options
* v1.8a - Updated sub-domain hijack list of domains (CC: th3gundy)
* v1.8 - Added sub-domain hijack scans for all sub-domains
* v1.8 - Added auto explort of all sub-domains to /domains directory
* v1.8 - Added additional stealth and airstrike checks for port 80 and 443
* v1.8 - Fixed issue with theHarvester not working with google
* v1.7g - Added email security/spoofing checks
* v1.7f - Added Zenmap XML auto-imports 
* v1.7f - Added ClamAV RCE Nmap script
* v1.7e - Fixed minor issue with airstrike and nuke mode
* v1.7e - Fixed minor issues with discover mode
* v1.7e - Added minor cosmetic improvements to reports
* v1.7e - Disabled automatic brute forcing by default
* v1.7e - Added automatic brute force setting in script vars
* v1.7d - Added sslyze
* v1.7d - Added 'discover' mode for full subnet scans
* v1.7d - Added verbosity to scan tasks to separate sub-tasks better
* v1.7c - Added plain text reporting 
* v1.7c - Improved loot directory structure and sorting
* v1.7b - Fixed issue with airstrike mode not scanning correctly
* v1.7b - Improved passive recon performance
* v1.7a - Improved NMap http scan performance
* v1.7a - Removed joomscan due to verbosity issues
* v1.7 - Added uniscan web vulnerability scanner
* v1.7 - Added joomscan Joomla scanner
* v1.7 - Improved web scan performance
* v1.7 - Fixed issue with inurlbr output
* v1.7 - Added remote desktop viewing for RDP connections
* v1.7 - Added experimental Metasploit exploit for Apache Struts RCE (CVE-2016-3081)
* v1.6e - Added reporting option for nobrute mode (CC. @mero01)
* v1.6e - Improved SMB scan performance/optimization added
* v1.6d - Improved NMap scan performance options
* v1.6d - Added xprobe2 OS finger printing tool
* v1.6d - Added jexbos JBoss autopwn
* v1.6d - Merged fix for theharvester package (CC. @RubenRocha)
* v1.6d - Merged fix for SuperMicroScanner (CC. @mero01)
* v1.6c - Add report mode for web scans
* v1.6c - Fixed issues with Sublist3r and theharvester
* v1.6c - Added Shocker Shellshock exploitation scanner
* v1.6b - Added Sublist3r sub-domain brute tool
* v1.6b - Added cutycapt web screenshot util
* v1.6a - Added improvements to recon phase
* v1.6a - Fixed small issue with 3rd party extension
* v1.6a - Various improvements to overall optimization of scans
* v1.6a - Added new "web" mode for full web application scans 
* v1.6 - Added 4 new modes including: stealth, port, airstrike and nuke
* v1.6 - Added Java de-serialization scanner
* v1.6 - Added reporting option to output to console and text file for all scans
* v1.6 - Added option to set Sn1per full path for universal command line access
* v1.6 - Added in DirBuster for web file brute forcing
* v1.6 - Fixed issue with sderr errors in TheHarvester
* v1.5e - Removed shodan command line tool due to issues
* v1.5e - Fixed wafwoof installation in kali 2.0
* v1.5d - Fixed minor issues with port 513/tmp and 514/tcp checks
* v1.5c - Fixed issue which broke link to sniper directory
* v1.5b - Added Squid Proxy checks port 3128/tcp
* v1.5b - Fixed shodan setup options in install.sh
* v1.5b - Fixed syntax error with theHarvester in install.sh
* v1.5a - Fixed syntax error with port 8081 checks
* v1.5a - Added Arachni integration
* v1.5a - Added vsftpd, proftpd, mysql, unrealircd auto exploits
* v1.5 - Added Metasploit scan and auto-exploit modules
* v1.5 - Added additional port checks
* v1.5 - Added full TCP/UDP NMap XML output
* v1.5 - Auto tune scan for either IP or hostname/domain
* v1.4h - Added auto IP/domain name scan configurations
* v1.4g - Added finger enumeration scripts
* v1.4g - Fixed nmap -p 445 target issue
* v1.4g - Fixed smtp-enum target issue
* v1.4f - Fixed BruteX directory bug
* v1.4e - Fixed reported errors install.sh
* v1.4e - Added auto-upgrade option to install.sh for existing Sn1per installs
* v1.4d - Fixed missing rake gem install dependency
* v1.4c - Reordered 3rd party extensions
* v1.4b - Fixed install.sh executable references
* v1.4b - Fixed Yasou dependencies in install.sh
* v1.4b - Fixed minor issues with BruteX loot directory
* v1.4 - Added Yasou for automatic web form brute forcing
* v1.4 - Added MassBleed for SSL vulnerability detection
* v1.4 - Added Breach-Miner for detection of breached accounts
* v1.4 - Fixed minor errors with nmap
* v1.4 - Removed debug output from goohak from displaying on console

## FUTURE:
* Add scan config options to enabled/disable certain scan tasks (ie. brute force, osint, web scans, etc.)