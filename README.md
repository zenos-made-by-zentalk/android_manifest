-----------------------------------------------------------------------------

<p align="center">
<img src="https://i.imgur.com/ZMZgE4F.png" > 
</p>

-----------------------------------------------------------------------------

Getting Started:
================

To get started with the building process, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/zenos-made-by-zentalk/manifest -b pie

# Sync
repo sync -c -jx --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch zen_$device-userdebug

# Build the code
$ mka bacon -jX
```


