# startrek1e
lackeyccg plugin for Startrek:CCG 1st ed.

HOWTO update

branch the repo branch playable

get new card data from [https://www.trekcc.org/lackey2020/](https://www.trekcc.org/lackey/2020.php)

replace the [sets/Virtual.txt](sets/Virtual.txt) and [sets/Physical.txt](sets/Physical.txt) with the new data.
place new images in sets/setimages/general/ as border trimmed 320x462px jpg

update 
[changelog.txt](changelog.txt)

add new expansion to
[formats.txt](formats.txt) and [setlist.txt](setlist.txt)

set new date to yesterday and add replaced images
[uninstall.txt](uninstall.txt)

update the date, version number and add short changes
[version.txt](version.txt)

Set new date at the top of
[updatelist.txt](updatelist.txt)

generate new checksum 
/mkupdate plugins/startrek1e/updatelist.txt

make new PR
