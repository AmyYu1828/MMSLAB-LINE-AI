# LINE bot

An example LINE bot with following funcs
1. upload image to Imgur.
2. search nearby place

## How to use

### Install deps

``` shell
$ npm install
```

### Configuration

``` shell
$ export CHANNEL_SECRET=YOUR_CHANNEL_SECRET
$ export CHANNEL_ACCESS_TOKEN=YOUR_CHANNEL_ACCESS_TOKEN
$ export IMGUR_CLIENT_ID=YOUR_IMGUR_CLIENT_ID
$ export GOOGLE_MAP_API_KEY=YOUR_GOOGLE_MAP_API_KEY
$ export PORT=1234
```

### Run

``` shell
$ node .
```

## Webhook URL

```
https://your.base.url/callback
```
