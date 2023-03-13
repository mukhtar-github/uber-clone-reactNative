# uber-clone-reactNative

## Setup Development Environment

### Download Android Studio

Unzip the file and use the these commands in your Terminal:
Open the Android folder and go to platform-tools folder, then press (Ctrl+L) - To get the path (/home/mukhtar/Android/Sdk/platform-tools/).
Go to Home folder and press Ctrl+H to open all hidden files, then open (.bashrc) file, and at the bottom end, type (export ANDROID_HOME=$HOME/Android/Sdk
export PATH=$PATH:$ANDROID_HOME/tools:$ANDROID_HOME/platform-tools).

"How to set Android SDK path in Ubuntu?

PATH of any Android tool can be set using export command in ~/.bashrc file.

1. Open ~/.bashrc file
2. Type the following line of command at the end of the ~/.bashrc file :

export ANDROID_HOME=$HOME/Android/Sdk
export PATH=$PATH:$ANDROID_HOME/tools:$ANDROID_HOME/platform-tools

3. Save the file
4. Restart the Terminal"

sudo mv ~/Downloads/android-studio /usr/local/
cd /usr/local/android-studio/bin
./studio.sh
