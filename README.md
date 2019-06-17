# BrewyaStore

Basic OUYA compatible store server

## Useage
1. Clone this repo
2. open a terminal in the repo's directory
3. Run `python3 BrewyaStore.py`
note: depending on your system, `python3` may be replaced with `python`

## point your OUYA to new store
Change file `/sdcard/ouya_config.properties` on your Ouya's filesystem to add the following line:
`OUYA_SERVER_URL=http://your.server.ip:5000`

Warning: Be sure not to add a trailing `/` to the above URL
