# Apps_Script
Script I use in google apps scrips
This scrip sweeps a folder (folderId variable) and 2 levels of subfolder within it for new and modified files since the last time it ran, sends an email with the list for a mailing list, and records the data on the spreadsheet.

For more levels, you will have to add code

To watch more than one folder, create several instances of this script/spreadsheet, one for each "root" folder you want to watch

I use this to have some kin of registry and control over folder I share with suppliers that I expect them to put files on. 

This started with the script I found here: http://baumbach.com/google-script-2/  
But it was not working for added files with modified date prior to the script last run. It also did not worked for subfolder (as stated), so I had to improve it a little.

I also used this as a reference: https://www.labnol.org/code/19854-list-files-in-google-drive-folder.

Cheers.
