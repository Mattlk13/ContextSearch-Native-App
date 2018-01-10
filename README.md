# ContextSearch-Native-App
Native App for use with Context Search

This is a simple app written in both C and python that reads a requested file to base64 for webextensions native application processing.

## Windows
Grab the latest release and run the installer

## Other OS
1. Compile or use the python script
2. Edit "path" key in ContextSearch.json to point to the binary or python script

### Linux
For global visibility, copy ContextSearch.json to:

* /usr/lib/mozilla/native-messaging-hosts/ContextSearch.json

or:

* /usr/lib64/mozilla/native-messaging-hosts/ContextSearch.json

For per-user visibility

* ~/.mozilla/native-messaging-hosts/ContextSearch.json

### Mac OS X
For global visibility, copy ContextSearch.json to:

* /Library/Application Support/Mozilla/NativeMessagingHosts/ContextSearch.json

For per-user visibility

* ~/Library/Application Support/Mozilla/NativeMessagingHosts/ContextSearch.json

