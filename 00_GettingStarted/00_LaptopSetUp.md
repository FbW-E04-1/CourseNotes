# Setting up your laptop for web development

## Nautilus

[Guided Tour](https://www.ubuntubuzz.com/2017/10/newbies-guide-to-ubuntu-1710-part-2.html)

## Open a Terminal window

* Ctrl-Alt-T
* Right click in desktop window; choose Open In Terminal
* Tap the **Super** key (Windows | ⌘) to open Dash; type Terminal

```
$ whoami
<username>
$ sudo whoami
root
```


## Install Google Chrome

[Instructions](https://linuxhint.com/ubuntu_20-04_google_chrome_installation_guide/)

### Method 1: using the command line
#### What the instructions do:
1. Update the information about all packages that are installed on your computer
2. Download an installer file
3. Install the Chrome package
4. Run `google-chrome`

#### Details
* [`apt-get update`](https://askubuntu.com/questions/222348/what-does-sudo-apt-get-update-do)</br>(The question is about `apt-get`, but it also applies to the more recent [`apt` command](https://itsfoss.com/apt-vs-apt-get-difference/))
* [`wget`](https://phoenixnap.com/kb/wget-command-with-examples)
* [What is a `.deb` file?](https://fileinfo.com/extension/deb)
* [`dpkg`](https://askubuntu.com/questions/173465/what-is-dpkg-for)

### Method 2: download through Firefox
1. Visit the [download page](https://www.google.com/chrome/)
2. Click Download
3. Ensure ` 64 bit .deb (For Debian/Ubuntu)` is selected
4. Click Accept and Install
5. The Software app will open; click Install
6. Tap the **Super** key and type "chrome"

## Install Zoom

1. Visit the [download page](https://zoom.us/download)
2. Choose Ubuntu as the Linux Type
3. Check that the default values for OS Architecture and Version look good
4. Click Download
5. Locate the downloaded `zoom_amd64.deb` file; double-click on it
6. Click Install

## Install Slack

[Instructions](https://linuxize.com/post/how-to-install-slack-on-ubuntu-20-04/)

[About the `snap` package manager](https://www.tecmint.com/install-snap-in-linux/)

## Join the class's Slack Workspace

_Ask me for an invitation link_

## Install Node Version Manager (NVM)

[Instructions](https://tecadmin.net/how-to-install-nvm-on-ubuntu-20-04/)
```
sudo apt install curl
curl https://raw.githubusercontent.com/creationix/nvm/master/install.sh | bash
```

## Install latest version of Node.js and the Node Package Manager (NPM)
Open a new Terminal window

```
nvm install node
node --version
npm --version
```

## Install VS Code and Live Share

[Instructions for VS Code](https://linuxize.com/post/how-to-install-visual-studio-code-on-ubuntu-20-04/)

[Instructions for Live Share](https://code.visualstudio.com/learn/collaboration/live-share)

1. Launch VS Code
2. Launch VS Quick Open (Ctrl+P)
3. Paste this:  ```ext install MS-vsliveshare.vsliveshare-pack```
4. Press Enter

## Create a GitHub account

1. Visit the [registration page](https://github.com/join)
2. Follow the steps to create an account
3. Send me your GitHub username
4. Wait for me to add you to the organization
5. Visit the class's [Organization page](https://github.com/FbW-E04-1)
