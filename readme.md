# pihole-splogs

Low-value copycat spam blog site DNS blocklists.

**All**

```
https://raw.githubusercontent.com/JackCuthbert/pihole-splogs/main/pihole-github-splogs.txt https://raw.githubusercontent.com/JackCuthbert/pihole-splogs/main/pihole-stack-overflow-splogs.txt
```

**GitHub**

```
https://raw.githubusercontent.com/JackCuthbert/pihole-splogs/main/pihole-github-splogs.txt
```

**StackOverflow**

```
https://raw.githubusercontent.com/JackCuthbert/pihole-splogs/main/pihole-stack-overflow-splogs.txt
```

## Usage

### Pi-Hole

1. Login into Pi-hole admin
2. Navigate to "Adlists"
3. Copy the above URLs
4. Paste the URLs in the address box and click on Add

### AdguardHome

For your chosen URL above:

1. Login to AdguardHome admin
2. Navigate to Filters > DNS Blocklists
3. Click "Add blocklist" at the bottom
4. Select "Add a custom list"
5. Enter a name to identify the list
6. Enter the lists url
7. Click "Save"

## Other lists

I sometimes maintain other lists:

- [pihole-twitter](https://github.com/JackCuthbert/pihole-twitter): Block Twitter domains.
- [pihole-reddit](https://github.com/JackCuthbert/pihole-reddit): Block Reddit domains.
- [pihole-ausnews](https://github.com/JackCuthbert/pihole-ausnews): Block non-Murdoch owned Australian news sites and services.
