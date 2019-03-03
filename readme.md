Step-by-step install instructions:

1. Register on the VPS hosting like this 
2. Create "Droplet" Ubuntu 16 x64 / 2+GB / 2-4vCPU / 50+ GB SSD
3. Log in to Droplet over SSH
4

```
sudo apt-get update
sudo apt-get install build-essential libssl-dev curl -y
curl -sL https://raw.githubusercontent.com/creationix/nvm/v0.31.0/install.sh -o install_nvm.sh
bash install_nvm.sh
sudo reboot

nvm install 8.0.0

https://github.com/ExchangeTime/opentrade.git
cd opentrade

sudo npm install 
```

```
cd  ~/opentrade/server
sudo node main.js
```

In your browser address bar, type https://127.0.0.1:40443
The first registered user will be exchange administrator. 

Graphical updates at gokrypto.se
