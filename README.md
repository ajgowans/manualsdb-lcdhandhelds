# The MiSTer Manuals DB - Tomy Pyuuta Jr.

This is a database for the MiSTer project that downloads the English manuals in .pdf form for LCD Handhelds to the docs folder, which can be loaded from the OSD within th core by selecting "Help".

Currently supported:
Epoch Galaxy II
Tomy Scramble

To use it simply copy and paste the below to the bottom of your downloader.ini file (found at: /media/fat/downloader.ini )

```ini
[ajgowans/manualsdb-lcdhandhelds]
db_url = https://raw.githubusercontent.com/ajgowans/manualsdb-lcdhandhelds/db/db.json.zip
```
