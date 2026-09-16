# ScreenCloud - NextCloud
[![Sponsor @tmiland](https://img.shields.io/badge/Sponsor-%40tmiland-ea4aaa?logo=githubsponsors&logoColor=white)](https://github.com/sponsors/tmiland)


A NextCloud service plugin for ScreenCloud

## Installation

* Go to: **Preferences** -> **Online Services** -> **More services**
* Select: **Install from URL** and paste the following address:

```
https://github.com/tmiland/screencloud-nextcloud/archive/master.zip
```

* Or go to: **Preferences** -> **Online Services** -> **More Services**
* Select: **Mirror: Other** and paste the following address:

```
https://github.com/tmiland/screencloud-nextcloud/raw/master/plugin-list.xml
```

Tested and working with Nextcloud 20.0.8, ScreenCloud 1.3.0 from Debian 9.0 repo on Ubuntu 20.04.2.

PS: In "Server URL" use "https://nextcloud.domain.com", not the WebDAV url.

To install ScreenCloud from Debian 9.0 repo:

Add the Screencloud repo:

```
sudo sh -c "echo 'deb http://download.opensuse.org/repositories/home:/olav-st/Debian_9.0/ /' >> /etc/apt/sources.list.d/screencloud.list"
```

Update your software sources and install Screencloud’s Debian app:

```
sudo apt-get update && sudo apt-get install screencloud
```

Download the repo key:

```
cd /tmp
```
```
wget http://download.opensuse.org/repositories/home:olav-st/Debian_9.0/Release.key
```

Add the repo key:

```
sudo apt-key add - < Release.key
```

Guide source: https://www.omgubuntu.co.uk/2016/06/force-install-screencloud-ubuntu-16-04

# Screenshots

Plugin installed:

![screenshot installed](https://raw.githubusercontent.com/tmiland/screencloud-nextcloud/master/Screenshot%20at%2017_56_41.png?raw=true "Plugin installed")

Plugin settings:

![screenshot settings](https://raw.githubusercontent.com/tmiland/screencloud-nextcloud/master/Screenshot%20at%2018_06_39.png?raw=true "Plugin settings")

Images uploaded:

![screenshot uploaded](https://raw.githubusercontent.com/tmiland/screencloud-nextcloud/master/Screenshot%20at%2018_14_08.png?raw=true "Images uploaded")

## Info

Forked and customized for NextCloud from https://github.com/Section214/screencloud-owncloud
