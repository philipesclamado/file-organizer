# file-organizer

This is the software that handles file management.

## Running the app

1. `make`

## [PM2 Process Management Quick Start](https://pm2.keymetrics.io/docs/usage/quick-start/)

Managing application state:
```
$ pm2 restart app_name
$ pm2 reload app_name
$ pm2 stop app_name
$ pm2 delete app_name
```

List the status of all application managed by PM2:
```
$ pm2 [list|ls|status]
```

Display logs in realtime:
```
$ pm2 logs
```

Dig in older logs:
```
$ pm2 logs --lines 200
```
