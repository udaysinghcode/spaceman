# Spaceman [![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.png?v=103)](https://github.com/ellerbrock/open-source-badges/)

Welcome to Spaceman, named in the honor of Dr. Leo Spaceman (_pronounced spä-ʧ-mən_) from 30 Rock, a man who didn't pay enough attention at work. We run the space process helping you space out.

![Dr. Spaceman](https://images.duckduckgo.com/iu/?u=http%3A%2F%2F38.media.tumblr.com%2F3be4b0c28f4d6e4e581a9a76e2eafb4d%2Ftumblr_mof6m5CeWW1qh1g19o1_500.gif&f=1 "Dr. Spaceman") 

## Introduction

Idle tasks got you down? Trying to space out when you're stuck at work. Spaceman helps you space out while not appearing idle keeping you at work at all times.

## To run

Since all you need to run the command is this:
`osascript /PATH/TO/YOUR/script.scpt`

1. Move this spacelist.plist file to your `~Library/LaunchAgents/`.
2. Run `pwd` to find the path to your script when you're inside this folder.
3. Update `/WORKING/DIRECTORY/` to the location of this folder.
4. `launchctl load -w ~/Library/LaunchAgents/spacelist.plist`
5. `launchctl start spaceman.job` (it should be under the `<key></key>`)

You should be running!

If you every need to turn off the script: `launchctl unload -w ~/Library/LaunchAgents/spacelist.plist`
 

### Inspiration

Made in New York for a friend at work
