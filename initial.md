## First steps on a newly installed Fedora

### Install Vim
`sudo dnf install vim`

### Install Oh-My-Zsh

`sudo dnf install zsh util-linux-user git`

`sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"`

Log out and log in to start using `zsh` as default.

### Install Nodejs and NPM

`sudo dnf install -y nodejs npm`

### Install NVM

`curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.6/install.sh | bash`

### Install stable node via NVM

`nvm install stable`

`nvm use stable`

### Install PostgreSQL

`sudo dnf install postgresql-server postgresql-contrib`

### Setup PostgreSQL to start during boot process

`sudo systemctl enable postgresql`

### Install MongoDB
`dnf install mongodb mongodb-server`

