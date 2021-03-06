# Folder customization (Advanced)
Input to the python script would be the directory name. The script will search for appropriate images 
(size = 256*256) for the folder at https://images.google.com/ considering the folder name as the search 
string.

It will download 'n' images (n <= 100) and select one at random to convert into an .ico file. <br>
Value of 'n' is parameterized. <br>
(Note: Higher 'n' will result in more time for execution and icons may or may not be appropriate for its folder,
which is pretty much the same phenomenon observed when manually searching images on google.)

The selected image is converted to .ico format and saved in the appropriate subdirectory and applied
as its icon.

### Before:
![alt text](https://github.com/CAVIND46016/Folder_Customization-Icons/blob/master/data/friends_before.png)
### After:
![alt text](https://github.com/CAVIND46016/Folder_Customization-Icons/blob/master/data/friends_after.png)

# Folder customization (Basic)
Here, the icons need to be created manually and saved into its appropriate directory/subdirectory.
The python script then applies the respective icons to its folders.

### Before:
![alt text](https://github.com/CAVIND46016/Bulk-Icon-Apply/blob/master/data/before.png)
### After:
![alt text](https://github.com/CAVIND46016/Bulk-Icon-Apply/blob/master/data/after.png)

You can easily make a Windows Application (.exe) file using the  steps as shown on the website: <br>
https://mborgerson.com/creating-an-executable-from-a-python-script/

`pyinstaller.exe --onefile --windowed app.py` <br>
`pyinstaller.exe --onefile --windowed --icon=app.ico app.py`

<br>
`--onefile` is used to package everything into a single executable. If you do not specify this option, the libraries, etc. will be distributed as separate files alongside the main executable. <br>
`--windowed` prevents a console window from being displayed when the application is run. If you're releasing a non-graphical application (i.e. a console application), you do not need to use this option. <br>
`app.py` the main source file of the application. The basename of this script will be used to name of the executable, however you may specify an alternative executable name using the --name option.
<br>

##### Also, on [LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:6372596933311156224).

