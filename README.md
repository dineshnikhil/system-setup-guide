# Initial set up

### 1. Update your system using the below comands

```
sudo apt update && sudo apt upgrade -y
```

### 2. Install the git in the system using the following command

```
sudo apt install git
```

### 3. Clone the terminal profile from the below command

```
git clone git@github.com:dineshnikhil/terminal-profile.git
```

- then just run following commmand like below respectfuly

```
./install_powerline.sh
```

```
./install_terminal.sh
```

```
./install_profile.sh
```

### 4. Softwares to install as the .deb files

- [VsCode](https://code.visualstudio.com/Download)
- [Insomnia](https://insomnia.rest/download)
- [Microsoft-edge](https://www.microsoft.com/en-us/edge?form=MA13FJ&exp=e00&ch)
- [mongodb-compass](https://www.mongodb.com/try/download/compass)
- [mongodb-mongosh](https://www.mongodb.com/try/download/shell)
- [mongodb-org-server](https://www.mongodb.com/try/download/community)
- [zoom](https://www.zoom.us/download)

### 5. Install the cascadia code font

- install the cascadia code font form [here](https://github.com/microsoft/cascadia-code/releases/tag/v2111.01)
- install only the required .tt files
- set the font in vs code
- set the font in the terminal also

### 6. Setting up the browser and passwords

- install the brave browser
- from the bitwarden password manager export the data as csv file
- import that in the brave brave browser
- login into the edge
- import book marks and all from edge in the brave settings.

### extras

- install gnome-tweaks

```
sudo apt install gnome-tweaks
```

- install gnome-shell-extension-manager

```
sudo apt install gnome-shell-extension-manager
```

- extensions too install

  - blur my shell
  - caffeine
  - user themes

- To enable the minimize feature of dock run the following command.

```
gsettings set org.gnome.shell.extensions.dash-to-dock click-action 'minimize'
```

- To hide the show application option from the dock

```
gsettings set org.gnome.shell.extensions.dash-to-dock show-show-apps-button false
```
