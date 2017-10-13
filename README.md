# Spaceman

Welcome to Spaceman. We run the space process helping you space out.

# To run

Since all you need to run the command is this:
`osascript /PATH/TO/YOUR/script.scpt`

1. Move this spacelist.plist file to your `~Library/LaunchAgents/`.
2. Run `pwd` to find the path to your script when you're inside this folder.
3. Update `/WORKING/DIRECTORY/` to the location of this folder.
4. launchctl load -w ~/Library/LaunchAgents/spacelist.plist
5. launchctl start spaceman.job (it should be under the <key></key>)

You should be running!

If you every need to turn off the script:
`launchctl unload -w ~/Library/LaunchAgents/spacelist.plist`
 

