UNVS 
=============

<b>PLEASE NOTE THIS IS STILL A HIGHLY EXPERIMENTAL PROJECT. 
----------------
WE ARE STILL IN DEVELOPMENT STAGES. USE AT YOUR OWN RISK. WE ACCEPT NO LIABILITY IN ANY INSTANCE & NO GUARANTEE NOR WARRANTY IS PROVIDED. DEVELOPED FOR ENTERTAINMENT - USE IT FOR FUN !</b>

https://UNVS.com


unvs.conf File (In Wallet Folder) Example Settings
----------------

Below is a list of most commonly used **unvs.conf** file settings to help configure your wallet's abilities.

Not all have been tested and some may be depreciated, these have been compiled from past bitcoin core/litecoin wallet client instructions.

```
 # Run on the test network instead of the main network.
 testnet=1
 
 # Disable test network and run on the main network.
 testnet=0
 
 # Use as many addnode= settings as you like to connect to specific peers in addition to ports.
 addnode=000.00.00 add
 addnode=000.00.00:9333 add

 # Maximum number of inbound+outbound connections.
 maxconnections=
 # Example 100 Connections accepted.
 maxconnections=100
 
 # =1 tells Wallet installation to accept JSON-RPC commands.
 server=1
 
 # =0 removes server behavior.
 server=0
 
 # You must set rpcuser and rpcpassword to secure the JSON-RPC api.
 rpcuser=username
 rpcpassword=SetAPasswordHere
 
 # Set gen=1 to auto activate mining on wallet start.
 gen=1
 
 # Sets auto mining to off on wallet start.
 gen=0
 
 # Start Wallet client minimized.
 min=1
 
 # Minimize to the system tray.
 minimizetotray=1 
```

Default configuration file locations
-----------------------------------

Operating System	Data Directory	Example Path

Windows	%APPDATA%\unvs\	

Linux	$HOME/.unvs/



Development process
-------------------

We are continually developing in-house with our own team, but we also receive assistance from freelance developers and community driven support.

We are still in the early stages. Bug fixes, patches and such like will be rolled out in stages. 

Use our services for FUN & Entertainment only !
