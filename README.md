**This program can be used to update applications that have a single executable**
After the update, the program starts the application with the argument "-firstrun"

Usage: *Updater.exe DownloadLink InfoLink AppPath*
-	***DownloadLink***    link to download file from internet
-	***InfoLink***        link to a text file containing information about the download file
-	***AppPath***         full path to the file to be replaced on the local hard drive
	
Example: *Update.exe https://github.com/AnyUser/Repository/raw/main/AnyApp.exe https://raw.githubusercontent.com/AnyUser/Repository/main/InfoFile.txt X:\Path\To\App\AppName.exe*

Sample file content from InfoLink:

	Version=6.19.5.0
	SHA256=rge3h656667j8kl8lhsr5a452h5h65j76765wrh
	
Options:

	-help	print this help message
	-test	shows all input without executing the program