Calendar app
============

Maintainers:
------------
- [Georg Ehrke](https://github.com/georgehrke)
- [Thomas Tanghus](https://github.com/tanghus)
- [Bart Visscher](https://github.com/bartv2)

Developer setup info:
---------------------
### Master branch:
Just clone this repo into your apps directory.

### Rework branch:
The calendar rework depends on the appframework.
Get the latest version of the appframework:
```bash
git clone git://github.com/owncloud/appframework.git
```
Enable the appframework in the app settings of ownCloud.

Get the lastest version of the rework:
```bash
git://github.com/owncloud/calendar.git
cd calendar
git checkout rework
```