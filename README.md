# SleepAndStart-FullPaperServer
## Uses [_mcsleepingserverstarter_](https://github.com/vincss/mcsleepingserverstarter) and [papermc](https://papermc.io/) and [NodeJS](https://nodejs.org/en/download/)

### Extra Credits to [EmptyServerStopper](https://github.com/vincss/mcEmptyServerStopper) and [ViaVersion](viaversion.com)

Supported Versions: 1.19.* (All 1.19 versions)

# How to download on a (linux) ubuntu server

### First download [NodeJS](https://github.com/nodesource/distributions#debinstall)

### Then run this code into the terminal

``` bash
# Download git (Check for git with "which git")
sudo apt-get install git
```
``` bash
# In the directory of your home/any folder which will contain the server 
git clone https://github.com/FalconAndBunny/SleepAndStart-FullPaperServer.git

mv SleepAndStart-FullPaperServer/* ./
```
``` bash
# Optional command
rm README.md
```
``` bash
# Next:
cd Paper
npm install
npm update

# Configuration for the basic server is done!
# Run:
npm start

# To start the server!
```

### Extra Configuration

``` bash
# sleepingSettings.yml
nano sleepingSettings.yml

```