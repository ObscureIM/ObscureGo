# TurtleCoin Nest

The universal desktop GUI wallet for TurtleCoin

![Logo](/turtlecoinnestlogo.png)

## Installation

[Windows](#windows) - [Mac](#mac) - [Linux](#linux)

### Windows

1. Go [here](https://github.com/turtlecoin/turtle-wallet-go/releases) and download the latest release called **TurtleCoin-Nest-x.xx-Windows.zip**
2. Unzip the folder and launch **TurtleCoin-Nest.exe**. (Make sure you leave everything as is in the folder)

Important notes:

* Make sure *turtle-service.exe* is not running before you start *TurtleCoin-Nest*

### Mac

1. Go [here](https://github.com/turtlecoin/turtle-wallet-go/releases) and download the latest release called **TurtleCoin-Nest-x.xx-Mac.zip**.
2. Unzip it and move the folder wherever you want or drag the application **TurtleCoin-Nest** into /Applications or any other folder.
3. Launch the application. (If your mac complains that the app comes from an unindentified developer and does not want to open it, just right-click (or ctrl-click) on the app, and choose open > open)

Important notes:

* The wallets you create or generate will be saved to your home folder. You can keep them there or move them wherever you want.
* Make sure *turtle-service* is not running before you start *TurtleCoin-Nest*.
* If you encounter crashes, open the activity monitor (in your app > utilities), and force quit *turtle-service* (if it is running) before opening a wallet.
* The log files will be saved in ~/Library/Application Support/TurtleCoin-Nest/.

### Linux

1. Go [here](https://github.com/turtlecoin/turtle-wallet-go/releases) and download the latest release called **TurtleCoin-Nest-x.xx-Linux.tar.gz**
2. extract it
`$ tar xvzf TurtleCoin-Nest-x.xx-Linux.tar.gz`
3. run **TurtleCoin-Nest.sh**. (Make sure you leave everything as is in the folder)

Important notes:

* Make sure *turtle-service* is not running before you start *TurtleCoin-Nest*
* If you want the *copy address to clipboard* button to work, install *xclip* or *xsel* (on Debian/Ubuntu: `$ sudo apt install xclip`).
* If you encounter crashes, open an activity monitor (e.g. `$ htop`), and quit *turtle-service* (if it is running) before opening a wallet. (this bug is being worked on)

## Upgrade

Just download the new release and follow the same steps as [Installation](#installation).
If you are on Windows or Linux, move your wallets (.wallet) and settings.db files from the old Nest folder to the new. Then you can delete the old folder. (on Mac, you do not need to move the settings.db file as it stays in ~/Library/Application Support/TurtleCoin-Nest/).

## Screenshots

![Main Screen](/Screenshots/MainScreen.png)

![Open Wallet](/Screenshots/OpenWallet.png)

## Donations

XSDFq1aCuu4TMzgUkVN7chFHKyAmNLYJhEg3DxKdtL67C9z3CS4sYLRHWqoCNmoLNuiq5xKb2F3Fr7GkbcCtWz8J3eG7Pxi44n
