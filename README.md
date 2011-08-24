# [Mac Configuration](https://github.com/zane/mac-configuration)

Instructions for configuring new macs to conform to Zane Shelby's personal preferences.

### Disable the dashboard

    defaults write com.apple.dashboard mcx-disabled -boolean NO
    killall Dock
    
### Have the dock show only running application
    
    defaults write com.apple.dock static-only -bool TRUE
