# Config

**Config** is a basic checklist I follow to set up a new Mac's development environment.

## Contents

| File | Description |
| --- | --- |
| `.bash_profile` | Customizes the Terminal.app prompt and echoes the currently checked out Git branch. |
| `.gitconfig` | Global Git configuration to specify my name and email, shortcuts, colors, and more. |
| `.gitignore` | A bunch of stuff that, much like short people, have no reason to live. |
| `.editorconfig` | Global editor configuration preferences. |

## Checklist

### 1. Prep OS X

- Download and install latest version of Xcode from the Mac App Store.
- Download and install Xcode Command Line Tools from <https://developer.apple.com/downloads/>.

### 2. Prep Terminal.app

- Load [`.bash_profile`](/.bash_profile)
- Load [`.gitconfig`](/.gitconfig) contents into the global `~/.gitconfig`
- Load up the Ocean theme from <https://github.com/mdo/ocean-terminal>

### 3. Secure Git(Hub) access

- [Generate new SSH key](https://help.github.com/articles/generating-ssh-keys/)
- [Generate an access token](https://help.github.com/articles/creating-an-access-token-for-command-line-use/) for Terminal to auth your GitHub account when 2FA is enabled.

### 4. Prep Text Editors

- Load [`.editorconfig`](/.editorconfig)

### 5. Setup Atom

- Enable `atom` Terminal commands: from Atom.app, open the Atom menu and select *Install Shell Commands*
- Install favorite packages
  - [autoclose-html](https://atom.io/packages/autoclose-html)
  - [css-snippets](https://atom.io/packages/css-snippets)
  - [css-triggers](https://atom.io/packages/css-triggers)
  - [file-icons](https://atom.io/packages/file-icons)
  - [minimap](https://atom.io/packages/minimap)
  - [project-manager](https://atom.io/packages/project-manager)
  - [editorconfig](https://atom.io/packages/editorconfig)

## Use it yourself

Fork this repo, or just copy-paste things you need, and make it your own. **Please be sure to change your `.gitconfig` name and email address though!**

## Works on my machine

Yup, it does. Hopefully it does on yours as well, but please don't hate me if it doesn't.

<3
