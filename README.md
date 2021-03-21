# Windows64Bit
XcelR Core Wallet v0.17.2 For Windows 64 Bit

=======================================================

OPEN XCELR CORE WALLET TO GENERATE THE APPLICATION DIRECTORY IN APP DATA THEN CLOSE THE CORE WALLET TO ADD xcelr.conf TO %APPDATA%\XcelR

(WARNING: Do not add the xcelr.conf file to the %appdata% dir while the core wallet is open. This will cause problems. Never edit your xcelr.conf file while your xcelr wallet is open.)

Please add the XcelR conf file to .xcelr/XcelR folder in %APPDATA% if on Windows. 

[If the zip file you downloaded does not contain a .conf file you can find a updated version on our Github/Gitlab]

=========================================================================================================================

Your xcelr.conf file should look like this. 

addnode=164.90.130.14:2048
addnode=164.90.139.226:2048
addresstype=legacy
server=1
rpcuser=xcelr
rpcpassword=changeme
rpctimeout=30
rpcallowip=127.0.0.1
fallbackfee=0.0002
gen=1
4way=1
fallbackfee=0.0002
paytxfee=0.001


(WARNING: If creating a new xcelr.conf file, make sure that you have all files selected and save as xcelr.conf, configuration file will not resgister if saved as xcelr.conf.txt)


How To Solo CPU Mine XcelR
====================================================================

Inside the zip file there is a batch file named mine. 

Step 1.)

After you have added the xcelr.conf file to your %APPDATA% Folder. Open the XcelR Core Wallet. 

Step 2.)

Allow the XcelR Core Wallet to download the blockchain data.

Step 3.) 

Once your XcelR Core Wallet is uptodate with the blockchain data. Double Click on the mine.bat file and your CPU Mining.

===================================================================


To view transactions on the XcelR Blockchain - https://explorer.xcelr.org


