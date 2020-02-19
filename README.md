# DD-WRT Automatic Updater

### Requirements

- A Linux box with network access to the DD-WRT device(s).

### Installation

- Clone the repository. Suggested location: `$HOME/opt/`.
- Follow configuration instructions in `ddwrt-update.TEMPLATE`.

### Sample Execution


```
Getting info of latest DD-WRT releases...
Chosen release (1 prior to latest): r42366 (2020-02-14)

Device: netgear-ac1450
Backing up device configuration...
Backing up mtd0 partition (boot)...
Backing up mtd1 partition (nvram)...
Backing up mtd4 partition (board_data)...

Downloading firmware...
######################################################################## 100.0%

Updating firmware...
######################################################################## 100.0%

Waiting 30 seconds...

Pinging device...
.....OK
```
