# Script to import Cisco config to Netbox.

1. Create Device in Netbox 
2. Get  dev_id
3. Put config near script
4. Define SYNTAX fo the device (supported ios or nxos)
5. Change netbox server

```

usage: parse.py [-h] -s SYNTAX [-did DID] [-p] conf_file

Parse config and import to Netbox

positional arguments:
  conf_file   config to parse

optional arguments:
  -h, --help  show this help message and exit
  -s SYNTAX   syntax CiscoConfParse: nxos,ios etc...
  -did DID    device id in Netbox
  -p          push data to Netbox
```
