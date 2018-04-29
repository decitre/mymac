## Install Basic Software

### Install from App Store

- [Amphetamine](https://itunes.apple.com/us/app/amphetamine/id937984704?mt=12)
- [Pages](https://itunes.apple.com/us/app/pages/id409201541?mt=12)

### Homebrew
##### Install [Git](https://git-scm.com/download/mac)

```
git config --global --edit
git config --global user.name "Your Name"
git config --global user.email you@example.com
```
##### Run Xcode and accept the license

Homebrew can not install properly until this occurs.

```
xcode-select --install
sudo xcodebuild -license accept
```

##### Install Homebrew

```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew doctor
```

##### Install Homebrew packages

```
git clone https://github.com/decitre/mymac.git
cd mymac
brew bundle
```

### Licenses

- Intellij: Search "jetbrains" mail
- Sublime Text: Search "Sublime" mail


