# termux-login-pin
### Created by [MrAlpha786](https://github.com/MrAlpha786)
***Request:*** Please use or modify this with proper credit. Add link to my github in your README.md.

_Add Login Password in Termux._

***Note: It's not an app lock. It's only for Termux.
      If you don't know what Termux is, You don't need this.***

## Prerequisites
1. Termux
2. Internet Connection

## Installation

Just enter following commands in respective order:

1.
```bash
apt-get update && apt-get upgrade -y
```
2.
```bash
apt-get install wget curl -y
```
3.
```bash
wget https://raw.githubusercontent.com/MrAlpha786/termux-login-password/master/setup
```
or
```bash
curl https://raw.githubusercontent.com/MrAlpha786/termux-login-password/master/setup > setup
```
4.  
```bash
chmod u+x setup
```
5.
```bash
bash setup
```
or
```bash
./setup
```
