# Langauge Server
<elab about language servers>

## Project Setup
Create `vscode` directory in root directory.
``` sh
cd ./vscode
```

## Installing Node and NPM
```sh
# If curl isn't already installed
sudo apt-get install curl

# Replace the number in "setup_16" with whichever version of node you want to install
curl -sL https://deb.nodesource.com/setup_16.x | sudo -E bash -

# Finally, install node and npm
sudo apt-get install nodejs

# Confirm the installation
node -v && npm -v
```

### Clone The Sample Repo