# HostsY
Just a simplified and multi-threaded revamp of [HostsX](http://github.com/Laicure/HostsX) for Windows.

######Auto Parameters:
Required:
* -auto
  * Initializes Auto Generate State
  * Directly replaces the hosts file in **C:\Windows\System32\drivers\etc**
  * Requires Data folder beside the app
   * Must have the **sources.txt** that contains the _host sources_
   * Optional: **black.txt** for domain _blacklist_
   * Optional: **white.txt** for domain _whitelist_

Optional:
* -sort
  * Sorts the Domains (ascending)
* -tab
  * Uses tab instead of spaces between Target IP and Domain Name
* -logs
 * Generate generation logs; auto-generates a logs.txt file

######[Weekly Updated](https://forum.xda-developers.com/showpost.php?p=68978460&postcount=2) host file:
```
https://bitbucket.org/Laicure/publicview/downloads/hosts
```

######You can use [StevenBlack/hosts' data](https://github.com/StevenBlack/hosts/tree/master/data) sources:
```
https://raw.githubusercontent.com/mitchellkrogza/Badd-Boyz-Hosts/master/hosts
https://raw.githubusercontent.com/azet12/KADhosts/master/KADhosts.txt
https://raw.githubusercontent.com/FadeMind/hosts.extras/master/SpotifyAds/hosts
https://raw.githubusercontent.com/StevenBlack/hosts/master/data/StevenBlack/hosts
https://raw.githubusercontent.com/FadeMind/hosts.extras/master/UncheckyAds/hosts
https://raw.githubusercontent.com/AdAway/adaway.github.io/master/hosts.txt
https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.2o7Net/hosts
https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Dead/hosts
https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Risk/hosts
https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Spam/hosts
https://www.malwaredomainlist.com/hostslist/hosts.txt
http://winhelp2002.mvps.org/hosts.txt
http://someonewhocares.org/hosts/zero/hosts
https://raw.githubusercontent.com/tyzbit/hosts/master/data/tyzbit/hosts
https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&mimetype=plaintext&useip=0.0.0.0
```
######Other Sources:
```
https://hosts-file.net/ad_servers.txt
https://hosts-file.net/emd.txt
https://hosts-file.net/exp.txt
https://hosts-file.net/fsa.txt
https://hosts-file.net/grm.txt
https://hosts-file.net/hfs.txt
https://hosts-file.net/hjk.txt
https://hosts-file.net/mmt.txt
https://hosts-file.net/pha.txt
https://hosts-file.net/psh.txt
https://hosts-file.net/pup.txt
https://hosts-file.net/wrz.txt
---
https://gitlab.com/gwillem/public-snippets/snippets/28813/raw
---
https://github.com/Free-Software-for-Android/AdAway/wiki/HostsSources
```
