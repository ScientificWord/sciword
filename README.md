Scientific Word is now open source. 

The source code is not yet on GitHub, since traces of non-public source are still being removed. However, a copy of the executable for Windows, version 6.1.2, is now posted. The instructions for installing it on Windows are:

1. Install MiKTeX and the MiKTeX console. These require Windows 8 or later.
2. Download the SciWord.zip file [HERE](https://www.mackichan.com/techtalk/v60/SciWord.zip).
3. Unzip the file. The contents are:
	- A directory, SW, which contains the executable code for Scientific Word and the associated files.
	- A directory, texmf-local, which contains various files needed to typeset some documents created by Scientific Word and WorkPlace, versions 5.5 and earlier.
	- These notes.

Instructions for installation.

1. Copy the SW directory to C:\\Program Files (x86).
2. Install MiKTeX if it is already installed.
3. If you expect to edit documents created by versions 5.5 and earlier, then
	- Copy the texmf-local directory to your user directory (C:\\Users\\<your login name>), or some other location you prefer.
	- Start the MiKTeX console and select whether you want to run in Administrator or User mode. User mode should be sufficient unless you put the texmf-local directory in a location that requires administrator permissions.
	- Click on 'Settings' in the sidebar on the left, and on the 'Directories' tab.
	- Click on the '+' button in the toolbar just above the 'Path' window.
	- Browse the file picker to select the 'texmf-local' folder you moved in the first step of this section.
	- Once that is done, click on the Tasks menu bar item, and select "Refresh file name database"

The executable file is sw.exe, which you should find at C:\\Program Files (x86)\SW\\sw.exe.
