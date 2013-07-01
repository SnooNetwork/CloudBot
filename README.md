# CloudBot/DEV

## About

CloudBot is a Python IRC bot based on [Skybot](http://git.io/skybot) by [rmmh](http://git.io/rmmh).

## Getting and using CloudBot

### Download

Get CloudBot at [https://github.com/ClouDev/CloudBot/zipball/develop](https://github.com/ClouDev/CloudBot/zipball/develop "Get CloudBot from Github!").

Unzip the resulting file, and continue to read this document.

### Install
    
Before you can run the bot, you need to install a few Python dependencies.
You are *required* to install `lxml`, and `Enchant` and `PyDNS` are required for some plugins to function.


These can be installed with `pip` (The Python package manager):

    [sudo] pip install -r requirements.txt

#### How to install `pip`

    curl -O http://python-distribute.org/distribute_setup.py # or download with your browser on windows
    python distribute_setup.py
    easy_install pip
    
If you are unable to use pip, there are Windows installers for LXML available for [64 bit](https://pypi.python.org/packages/2.7/l/lxml/lxml-2.3.win-amd64-py2.7.exe) and [32 bit](https://pypi.python.org/packages/2.7/l/lxml/lxml-2.3.win32-py2.7.exe) versions of Python.

### Run

Once you have installed the required dependencies, you can run the bot! Make sure you are in the correct folder and run the following command:

`python bot.py`

The first time you run the bot it will generate the config file. The next time you run it, it will start normally.

On Windows you can usually just double-click `bot.py` to start the bot, as long as you have Python installed correctly.

## Getting help with CloudBot

### Documentation

To configure your CloudBot, visit the [Config Wiki Page](http://git.io/cloudbotircconfig).

To write your own plugins, visit the [Plugin Wiki Page](http://git.io/cloudbotircplugins).

More at the [Wiki Main Page](http://git.io/cloudbotircwiki).

### Support

The developers reside in [#CloudBot](irc://irc.esper.net/cloudbot) on [EsperNet](http://esper.net) and would be glad to help you.

If you think you have found a bug/have a idea/suggestion, please **open a issue** here on Github.

### Requirements

CloudBot runs on **Python** *2.7.x*. It is developed on **Ubuntu** *12.04* with **Python** *2.7.3*.

It **requires the Python module** lXML.
The module `Enchant` is needed for the spellcheck plugin.
The module `PyDNS` is needed for SRV record lookup in the mctools plugin.

**Windows** users: Windows compatibility some plugins is **broken** (such as ping), but we do intend to add it. Eventually.

## Example CloudBots

You can find a number of example bots in [#CloudBot](irc://irc.esper.net/cloudbot "Connect via IRC to #CloudBot on irc.esper.net").

## License

CloudBot is **licensed** under the **GPL v3** license. The terms are as follows.

    CloudBot/DEV

    Copyright © 2011-2013 Luke Rogers / ClouDev - <[cloudev.github.com](http://cloudev.github.com)>

    CloudBot is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    CloudBot is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with CloudBot.  If not, see <http://www.gnu.org/licenses/>.
