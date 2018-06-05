# hubot-reload

Reload your hubot scripts without restarting hubot.

Written in JS not CoffeeScript and works with Hubot3


## Installation

In your hubot project repo, run:

``` bash
npm install hubot-reload --save
```

Then add **hubot-reload** to your `external-scripts.json`:

``` json
[
  "hubot-reload"
]
```

## Usage

```
user>> hubot reload
hubot>> Reloaded all scripts
```
