# Bash web monitor
***
A script that utilizes `curl`, `md5sum` and other utilities to monitor and notify for changes in websites.

## Features
 - Desktop notifications
 - Discord notifications through webhooks

## Usage
```
Usage: ./bash-web-monitor [options] url

Options:
  -i interval      set the interval of checks(defaults to 30s)
  -d webhook-url   post to the following discord webhook url
  -n               send Desktop notifications
  -h               Show this help message
```

## TODO
~~- [ ] use cron for scheduling~~
 - [x] Desktop notifications
 - [ ] make it work with IFTTT and discord webhooks
 - [ ] Handle HTTP error/status codes
