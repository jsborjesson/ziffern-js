# Ziffern JS

A decade ago I lived in Germany and wrote [this](https://github.com/jsborjesson/ziffern) in Ruby, I also wrote a [Rails app](https://github.com/jsborjesson/ziffern_site) to host a UI for it. Rails 4 is EOL since almost a decade as well, but for nostalgic reasons I wanted to bring this library to life again, without dealing with the old Rails app or hosting a server.

Instead I made a new simple static site and compiled the Ruby lib using Opal.

## Development

```bash
gem install opal
opal -c ziffern/ziffern.rb > ziffern.js
```
