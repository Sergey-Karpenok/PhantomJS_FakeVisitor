# PhantomJS_FakeVisitor

### Install

##### Debian based

```bash
$ sudo apt-get update

Then install required packages:
sudo apt-get install build-essential chrpath libssl-dev libxft-dev
sudo apt-get install libfreetype6 libfreetype6-dev libfontconfig1 libfontconfig1-dev

Now download the latest FantomJS from its official website. After downloading the archive file, just extract this to the desired system location. You don’t need to install this.

$ wget https://bitbucket.org/ariya/phantomjs/downloads/phantomjs-2.1.1-linux-x86_64.tar.bz2
$ tar xvjf phantomjs-2.1.1-linux-x86_64.tar.bz2 -C /usr/local/share/

Now simply create a soft link phantomjs binary file to systems bin dirctory as below:
$ sudo ln -sf /usr/local/share/phantomjs-2.1.1-linux-x86_64/bin/phantomjs /usr/local/bin

After completing installation, let’s verify the installed version of phantomjs:
phantomjs --version

2.1.1

```

##### Arch Linux

```bash
sudo pacman -S phantomjs bc
```

##### OS X

```bash
brew install coreutils phantomjs
```

##### Other

Download in [Official site](http://phantomjs.org/download.html).

### Usage

```bash
./start.sh
```

### Configurations

You can set **Cookies**, **Proxy**, **Resolution** and **User Agent** in _files_ directory.
