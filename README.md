# audio.js

## Usage

  audioJS.events.ready(function() {
    var as = audioJS.create_all();
  });

## Compiling Flash from the command line

Using the Flex SDK, which is free to download, Flash movies can be compiled
directly from the command line. It makes things slightly less painful.

### Installing

1. Download the current milestone release 'Open Source Flex SDK' from:
   <http://opensource.adobe.com/wiki/display/flexsdk/Download+Flex+4>

2. Copy to `bin` folder to `/usr/local/bin/flex/bin/`

3. Add `/usr/local/bin/flex/bin/` to your `PATH`

### Compiling

Run the following command from within the audiojs folder.

  mxmlc mp3player.as