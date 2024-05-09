Preconditions:
Install Java: Java JDK 17 - Get it here: https://www.oracle.com/java/technologies/downloads/#jdk17-mac

Appium setup
Install homebred (package manager for macOS and is used to install software packages)
Terminal: /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
Install node and mom (Appium dependencies)
Command to install node:  brew install node (this will install node as well)
Install Appium server using npm: npm install -g appium@2.0.1
Install UiAutomator2 Driver: appium driver install uiautomator2
Install xcuitest driver: appium driver install xcuitest

Android setup
Get Android studio here (https://developer.android.com/studio) and install it (including Android SDK via GUI installation)

Emulator setup
Open Android studio -> Configure -> AVD Manager -> Create Virtual Device -> Select Model -> Download Image for Android 10 OS version if not already downloaded -> Start AVD ->
AVD name: Nexus_6_API_30

