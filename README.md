# Tutorial Install Node V17

INSTALLATION:
- apt-get update
- apt-get upgrade
- apt-get install curl
- curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -
- sudo apt-get install -y nodejs

NOT WORKING?

- sudo apt-get remove nodejs
- sudo apt-get remove npm
- curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.2/install.sh | bash
- chmod +x ~/.nvm/nvm.sh
- source ~/.bashrc 
- nvm install 17
- node -v
[Yes now you have successfully installed node version 17]
