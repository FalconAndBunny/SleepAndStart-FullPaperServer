# SleepAndStart-FullPaperServer
## Uses [_mcsleepingserverstarter_](https://github.com/vincss/mcsleepingserverstarter) and [papermc](https://papermc.io/) and [NodeJS](https://nodejs.org/en/download/)

### Extra Credits to [EmptyServerStopper](https://github.com/vincss/mcEmptyServerStopper) and [ViaVersion](viaversion.com)

Supported Versions: 1.19.* (All 1.19 versions)

# How to download on a (linux) ubuntu server

### First download [NodeJS](https://github.com/nodesource/distributions#debinstall)

### Then run this code into the terminal
``` bash
# Download Java
java -version
# Download any Jdk from Jdk 17 - Jdk 20

```
``` bash
# Download git (Check for git with "which git")
sudo apt-get install git
```
``` bash
# In the directory of your home/any folder which will contain the server 
git clone https://github.com/FalconAndBunny/SleepAndStart-FullPaperServer.git

mv SleepAndStart-FullPaperServer/* ./
rm SleepAndStart-FullPaperServer
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


## Create a quick start command!

``` bash
touch start-server.sh
chmod +x start-server.sh
nano start-server.sh
```

### In the nano write:
```bash
# Replace the/path/to/your/server with the directory
cd the/path/to/your/server/Paper
exec npm start
```

### ^C to exit and y to save. Then:
``` bash
echo $PATH
# This will give all the "Paths" that allow for quick access to a command
# Replace a/path/name/ with one of the $PATH constants
sudo mv start-server.sh a/path/name/

```
