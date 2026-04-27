A script used to download, install and configure the latest BgInfo version (v4.33) on a Windows Server. 
The BgInfo folder will be created on the C: drive if the folder does not already exist. 
Then the latest BgInfo.zip file will be downloaded and extracted in the BgInfo folder. The logon.bgi file which holds the preferred settings will also be downloaded and extracted to the BgInfo folder. 
After extraction .zip files will be deleted. A registry key (regkey) to AutoStart the BgInfo tool in combination with the logon.bgi config file will be created. At the end of the script BgInfo will 
be started for the first time and the PowerShell window will be closed.
