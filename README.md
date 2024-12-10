# Introduction

This is how I setup a new  Macbook.


### Brewfile

Most apps are listed in the `Brewfile`. Install via:

```
brew bundle
```

### Manual installation

Not all apps are available on App Store or Homebrew and some of them must be installed manually:

- [SDKMAN](https://sdkman.io/)
- Oh-zh-sh + Dracula theme
- Zsh plugins: `plugins=(git dotenv autojump macos)`

### Some scripting

- iCloud symlink: `ln -s ~/Library/Mobile\ Documents/com\~apple\~CloudDocs ~/iCloud`