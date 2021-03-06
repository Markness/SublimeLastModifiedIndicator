# Sublime Text - Last Modified Indicator

This plugin displays an indicator next to the last edited line so you'll immediately see where you've worked before.

By default, the indicator stretches over seven lines around the last edited one to provide enough visual feedback.
This can be reduced to only the last edited line by modifying the `last_modified_indicator_multiline` configuration entry.

![example](https://dl.dropboxusercontent.com/u/50095156/lasteditedindicator_example.png)


## Installation

### Package Control
Download and install [Package Control](http://wbond.net/sublime_packages/package_control), restart Sublime Text and open the Package Control menu by pressing <kbd>Ctrl</kbd><kbd>Shift</kbd><kbd>P</kbd> (Windows/Linux) or <kbd>⌘</kbd><kbd>Shift</kbd><kbd>P</kbd> (OSX), then type `pci` and search for `LastModifiedIndicator`.

### Manual
Clone the repository to your Packages folder (Preferences -> Browse Packages...): `git clone git@github.com:wag/SublimeLastModifiedIndicator.git`

Or download the [zip](https://github.com/wag/SublimeLastModifiedIndicator/archive/master.zip) file directly and unpack it to the Packages folder.


## Settings

The plugin can be configured by editing the file: `LastModifiedIndicator/LastModifiedIndicator.sublime-settings`

      // enable (true) or disable (false) the plugin
      "last_modified_indicator": true,

      // show the indicator over multiple (seven) lines,
      // alternatively only on the last modified line
      "last_modified_indicator_multiline": true
