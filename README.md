# DD-WRT Automatic Updater

### Requirements

- A Linux box with network access to the DD-WRT device(s).

### Installation

- Clone the repository. Suggested location: `$HOME/opt/`.
- Follow configuration instructions in `ddwrt-update.TEMPLATE`.

### Sample Execution


```
Getting latest DD-WRT release info...
Latest release is: r41075 (2019-09-20)

Device: netgear-ac1450
Backing up current device configuration...

Downloading firmware...
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100 26.6M  100 26.6M    0     0  2356k      0  0:00:11  0:00:11 --:--:-- 3137k

Updating firmware...
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100 26.6M    0  3009  100 26.6M    143  1303k  0:00:20  0:00:20 --:--:--     0

Waiting 30 seconds...

Pinging device...
.....OK
```
