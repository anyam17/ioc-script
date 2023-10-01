The active response Python script is to parse the content of critical alerts and store their IoCs to predefined files on the Wazuh server. The script analyzes security alerts and extracts file hashes, IP addresses, and URLs. 
These IoCs are uniquely stored in the mal-ip-list, mal-url-list, and mal-md5-list files at the /var/ossec/etc/lists/ directory of the Wazuh server.

- The mal-url-list file stores the detected URLs.
- The mal-ip-list file stores the detected IP addresses.
- The mal-md5-list file stores the detected MD5 file hashes.
