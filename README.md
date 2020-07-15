# internet_filter
This repo held an python site grabber to filter sites with pi-hole

# Reason fot the script
The script will read the input_sites.txt file, all the sites listed in this text file will be grabbed, searched and all linked other sites will be added to the blocklist in pihole. Reason for this is that the current pihole files and 'secure' dns servers are not blocking all sites needed to add safe internet browsing to my home.

for example, tumblr have good sites but also sites that better can be blocked. This script will recognize tublr input sites, than check that sites and search for following or likes on the sites and go so on. Alle founds with links or likes will be added to the blocklist.

Also othe sites who are searching and collecting some kind of other sites can be added so the list

# white_list.txt
urls in white list will be skipped to the blocklist

# future
In future want to ad AI to filter out sites, but it is very difficult (now) to filter and check direclty.

# requirements
Python >3.5
Python module:
- Beautiful Soup 
