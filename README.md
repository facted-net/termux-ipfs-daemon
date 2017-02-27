# termux-ipfs-daemon

[![Build Status](https://travis-ci.org/facted-net/termux-ipfs-daemon.svg?branch=master)](https://travis-ci.org/facted-net/termux-ipfs-daemon)

This is a shell script intended for use with [Termux](https://termux.com/) which installs and runs an IPFS daemon for use with other applications.  It watches connection information and restarts the [IPFS](https://ipfs.io) daemon in offline mode when using mobile data and in online mode when using wifi.

## Installation
Requires the [Termux API app](https://termux.com/add-on-api.html).

From the Termux command line:

`curl https://raw.githubusercontent.com/facted-net/termux-ipfs-daemon/master/termux-ipfs -o ~/termux-ipfs; chmod ogu+x termux-ipfs`

## Usage
From the Termux command line:

`./termux-ipfs`
