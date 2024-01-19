# clypdown

Download sound files from clyp.it, even when the uploader didn't enable downloads. Created by 0x27. Now Python3™ compatible!

# Original description

## TL;DR  
I was trying to download a tune from [clyp](https://clyp.it/) and the download button was not enabled. No fear, [the API](https://clyp.it/api) comes to the rescue and we can ignore this.

## How it was made...
The process of how I created clypdown is documented fully [in this Steemit post](https://steemit.com/programming/@synapse/clypdown-tool-for-grabbing-music-from-clyp-it).

## Demo  
Youtube vidya to come later or whatever, maybe once I add list mode.

```
$ python ~/clyp.py https://clyp.it/hrvttfzp
{i} Uploader has disabled downloading. Who fucking cares.
{*} Got song title: Sabrepulse feat. Ten Thousand Free Men & Their Families - Chiptune Night
{*} Got mp3 url: http://a.clyp.it/hrvttfzp.mp3
{*} Saving file to Sabrepulse feat. Ten Thousand Free Men & Their Families - Chiptune Night.mp3
[################################] 3362/3362 - 00:00:10
{*} Done!
$
```

## Install
You will need the [clint](https://github.com/kennethreitz/clint) and [requests](https://github.com/kennethreitz/requests) modules for this.
```
pip install -r requirements.txt
```

## Licence
[Licenced under the WTFPL](http://wtfpl.net)

## Thanks  
Thanks to [Sabrepulse](https://twitter.com/sabrepulse) for having tunes what were uploaded on there with the download button disabled ;)

I do strongly suggest you actually support artists and stuff, but if you are on a box where the web-player refuses to work, nothing wrong with 'solving' the problem creatively.

## Beer?
If you found this useful, donations to the beer/rum supply are always appreciated at the cryptocurrency bin of   ```13wUj3ZMut6uJAZKgZ4jCGz6tfqRvUzRgj```, or via [My Coinbase](https://www.coinbase.com/infodox/)
