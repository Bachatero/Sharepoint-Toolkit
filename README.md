# Sharepoint-Toolkit
Sharepoint file uploader/downloader using Office365-REST-Python-Clienti lib


When sharepoint library cannot be mapped as regular network drive using "service" account and only APP can access it due to sharepoint security settings


Usage:

_$  ./python.exe sharepointToolkit.py  --help

usage: sharepointToolkit.py [-h] -s SITE 
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; (-d DOWNLOAD [DOWNLOAD ...] | -u UPLOAD [UPLOAD ...] | -l | -all DOWNLOADALL [DOWNLOADALL ... ])  
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; [-dest DESTINATION] [-dir DIRECTORY] [-del] 

Sharepoint File Tools - download/upload file from/to sharepoint site and list
library contents

optional arguments:  
 &nbsp; &nbsp; &nbsp; &nbsp;  -h, --help            show this help message and exit  
 &nbsp; &nbsp; &nbsp; &nbsp;  -s SITE, --site SITE  Enter sharepoint site name  
 &nbsp; &nbsp; &nbsp; &nbsp;  -d DOWNLOAD [DOWNLOAD ...], --download DOWNLOAD [DOWNLOAD ...]  
 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;                        Enter file name(s) to download  
 &nbsp; &nbsp; &nbsp; &nbsp;  -u UPLOAD [UPLOAD ...], --upload UPLOAD [UPLOAD ...]  
 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;                        Enter file name(s) to upload/optionally use * wildcard (e.g., "D:\tmpDir\test\\\*.txt", or, to recursively dive into subfolders use "D:\tmpDir\test\\**\\\*" )  
 &nbsp; &nbsp; &nbsp; &nbsp;  -l, --list            List library contents  
 &nbsp; &nbsp; &nbsp; &nbsp;  -all DOWNLOADALL [DOWNLOADALL ...], --downloadall DOWNLOADALL [DOWNLOADALL ...] 
 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;                        Enter Sharepoint folder name to get all contents of   
 &nbsp; &nbsp; &nbsp; &nbsp;  -dest DESTINATION, --destination DESTINATION  
 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;                        Enter destination library/folder when uploading to  
 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;                        Sharepoint  
 &nbsp; &nbsp; &nbsp; &nbsp;  -dir DIRECTORY, --directory DIRECTORY  
 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;                        Enter local subdirectory within D:\_tmpShareDrive,  
 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;                        e.g. -dir "GL_Extracts\APR19"  
 &nbsp; &nbsp; &nbsp; &nbsp;  -del, --delete   
 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;                        Deletes file(s) from Sharepoint if option specified when downloading_ 



Credits:

	Vadim Gremyachev https://github.com/vgrem/Office365-REST-Python-Client



