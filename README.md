# [Mac Configuration](https://github.com/zane/mac-configuration)

Instructions for configuring new macs to conform to Zane Shelby's personal preferences.

### Install Inconsolata

    curl -C - -O http://www.levien.com/type/myfonts/Inconsolata.otf && open Inconsolata.otf

### Disable the dashboard

    defaults write com.apple.dashboard mcx-disabled -boolean YES
    killall Dock
    
### Have the dock show only running application
    
    defaults write com.apple.dock static-only -bool TRUE

### Add service for starting the screen saver

    ln -s /Users/zane/Projects/mac-configuration.github.zane/Library/Services/Start\ Screen\ Saver.workflow /Users/zane/Library/Services
