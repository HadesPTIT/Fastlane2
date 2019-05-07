fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

Install _fastlane_ using
```
[sudo] gem install fastlane -NV
```
or alternatively using `brew cask install fastlane`

# Available Actions
## Android
### android develop
```
fastlane android develop
```
Beta Develop Distribution
Example:  fastlane android beta remote:framgia pullNumber:123 branch:571_create_register_logic  |
Or: fastlane android beta branch:571_create_register_logic   |
You can skip passing value for list parameter above
### android debug
```
fastlane android debug
```
Beta Staging Distribution
Example:  fastlane android beta_stg remote:framgia pullNumber:123 branch:571_create_register_logic  |
Or: fastlane android beta_stg branch:571_create_register_logic   |
You can skip passing value for list parameter above
### android production
```
fastlane android production
```
Production  Distribution
Example:  fastlane android prod remote:framgia pullNumber:123 branch:571_create_register_logic  |
Or: fastlane android prod branch:571_create_register_logic   |
You can skip passing value for list parameter above
### android notify_CW
```
fastlane android notify_CW
```
notification on chatwork 
### android fabric
```
fastlane android fabric
```
Upload to Fabric.

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
