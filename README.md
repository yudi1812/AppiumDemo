**Steps:**

Install Java: Java JDK 17 - Get it here: https://www.oracle.com/java/technologies/downloads/#jdk17-mac

**Appium setup**
1. Install homebred (package manager for macOS and is used to install software packages)
2. Terminal: /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
Install node and mom (Appium dependencies)
3. Command to install node:  brew install node (this will install node as well)
4. Install Appium server using npm: npm install -g appium@2.0.1
5. Install UiAutomator2 Driver: appium driver install uiautomator2
6. Install xcuitest driver: appium driver install xcuitest

**Android setup**
Get Android studio here (https://developer.android.com/studio) and install it (including Android SDK via GUI installation)

**Emulator setup**
Open Android studio -> Configure -> AVD Manager -> Create Virtual Device -> Select Model (Nexus 6) -> Download Image for Android 11 OS version if not already downloaded -> Start AVD ->
AVD name: Nexus_6_API_30

**Set JAVA_HOME environment variable**
1. Navigate to home directory: cd ~/
2. Open -e .zshrc
3. Add below entries: 

export JAVA_HOME=$(/usr/libexec/java_home)

export ANDROID_HOME=${HOME}/Library/Android/sdk

export PATH="/Users/yudi/apache-maven-3.9.3/bin:${ANDROID_HOME}/platform-tools:${ANDROID_HOME}/cmdline-tools:${JAVA_HOME}/bin:${PATH}"

4. Close it
5. Terminal: source .zshrc (to retain changes)

**How to run the project from local machine**
1. Pull the code into your machine and import in IDE (IntelliJ)
2. Go to src/test/java/AppiumTest.java -> Run this file
