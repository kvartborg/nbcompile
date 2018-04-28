# nbcompile
[![Build Status](https://travis-ci.org/kvartborg/nbcompile.svg?branch=master)](https://travis-ci.org/kvartborg/nbcompile)

Compile NetBeans projects directly from your terminal.

### Install
Use npm to install the script globally.
```sh
npm install -g nbcompile
```
Or clone this repo and place the `nbcompile.sh` in `/usr/local/bin`.
```sh
git clone https://github.com/kvartborg/nbcompile
cp -a nbcompile/bin/nbcompile.sh /usr/local/bin/nbcompile
```

### Usage
Navigate to a NetBeans project in your terminal and run the `nbcompile` command.
This will compile and run your java code like the NetBeans IDE.
```sh
cd my/netbeans/project
nbcompile
```
