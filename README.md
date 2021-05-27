# IPFinder

## Overview

This is a tool for finding devices on your network and it scans and retrieves information using multiple techniques to gather as much data as possible while maintaining speed.

### Usage

Simply starting the app will scan all available UDP ports and conduct an ARP scan and retrive a list back.

#### Arguments
Starting with arguments will allow you to customise scanning procedures
```markdown
-h                Argument Help
-m <int>          Min UDP port, default 1
-x <int>          Max UDP port, default 65535
-a <true|false>   ARP enabled (You can't get mac addresses or device manufacturer without this), default true
-r <true|false>   Hostname resolve enabled (Use DNS to resolve hostname), default true
-i <true|false>   IP iteration enabled (May take a while, but will return most devices), default false
-l <string>       Log all data to specified file, default null
```

### Changelog


### To do

- Add IP iteration
