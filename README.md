# Usage

- Create a config file at `~/.config/cloud/config.ini` containing:

```{ini}
[DEFAULT]
home_dir = /Users/ethan

[CloudData]
CloudDataPath = ${home_dir}/Cloud/data
LogFilePath = ${home_dir}/Cloud/sync_log

[Box]
label = box
local_directory = ${home_dir}/Cloud/data/box_sync
remote_directory = box:sync

[GoogleDrive]
label = googledrive
local_directory = ${home_dir}/Cloud/data/google_drive_sync
remote_directory = googledrive:sync
```
