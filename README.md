# chromium_recover_dbs
by Morgan Aldridge <morgant@makkintosshu.com>

## OVERVIEW

A `bash` script to validate & repair Chromium SQLite databases. Tested on OpenBSD.

## BACKSTORY

I've experienced some corruption of Chromium data stored in SQLite databases when `chrome` is running and I get a kernel panic or other hard freeze.

## USAGE

Run `chromium_recover_dbs` under the user for which you want Chromium SQLite databases to be repaired.

## LICENSE

Released under the [MIT license](LICENSE).
