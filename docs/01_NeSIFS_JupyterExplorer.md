# NeSI File system 


The part of the operating system responsible for managing files and directories is called the **file system**. It organizes our data into files, which hold information, and directories (also called ‘folders’), which hold files or other directories.

Directories are like places — at any time while we are using the shell, we are in exactly one place called our current working directory. Commands mostly read and write files in the current working directory, i.e. ‘here’, so knowing where you are before running a command is important.

!!! database "NeSI Filesystem (For Researchers)"

    All HPC platforms have custom File Systems for the purpose of **general use** and **admin**. NeSI Filesystem looks like above 
    
    <center>
    ![image](./images/nesi_filesystem.png){width="450"}
    </center>

    This may look a bit obscure but thing of them as different labels for some familiar names such as Desktop, Downloads, Documents

    * **`/home/username`** is for user-specific files such as configuration files, environment setup, source code, etc. This will be the default landing file system during a login
    * **`/nesi/project/projectcode`** is for persistent project-related data, project-related software, etc
    * **`/nesi/nobackup/projectode`** is a 'scratch space', for data you don't need to keep long term. Old data is periodically deleted from nobackup

    **`projectode`** for this event is `uoa03265`. If you are to open a NeSI project for your own research, it will have a unique project code with a prefix to represent your affiliated institute and a five digit number (randomly generated). 

    >Therefore, full path to persistent and nobackup/scratch file systems will be in the format of 

    * **`/nesi/project/uoa03265`**
    * **`/nesi/nobackup/uoa03265`**



## Jupyter File explorer

!!! folder-open  "Guide  File Explorer to correct working directory"

    Jupyter terminal and file explorer (on left) operate independently of each other. Therefore, changing the directory via terminal to your individual directory will not change the default working directory in explorer. Changing it to your individual directories can be done will couple of click 

    <center>![image](./images/jupyter_explorer.png)</center>