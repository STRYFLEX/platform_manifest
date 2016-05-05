![StryFlex](http://forum.xda-developers.com/attachment.php?attachmentid=3438056&amp;d=1439487936)

To initialize your local repository using the StryFlex trees, use a command like this:
````bash
repo init -u git://github.com/STRYFLEX/manifest.git -b mm-6.0
```
Then to sync up:
````bash
repo sync -c -f --force-sync
```
Finally to build:
````bash
./build.sh device_codename
```
Example:
````bash
./build.sh taoshan
./build.sh titan
```
