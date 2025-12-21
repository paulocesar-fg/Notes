#computation #linux 

A difference between Linux and windows is that Linux does not use *drive letters* in *pathnames*. In the windows world, the physical drives installed on the computer determine the *pathname* of the file. Windows assign a letter to each physical *disk drive* , and each drive contains its own directory structure for acesing files stored on it.

This isn't the method used by Linux. Linux stores files within a single directory structure called a virtual directory. The virtual directory contains file path from all the storage devices installed on the computer, merged into a single directory structure.

The Linux virtual directory structure contains a single base directory called the *root*.

Windows
```C:\Users\Paulo\Documents\test.doc```

Linux
```/home/Paulo/Documents/test.doc```


### Common Linux Directory Name

| Directory | Usage                                                                                       |
| --------- | ------------------------------------------------------------------------------------------- |
| /         | Root of the virtual directory, where normally no files are placed.                          |
| /bin      | Binary directory, where many GNU user-level utilities are stored                            |
| /boot     | Boot directory, where boot files are stores.                                                |
| /dev      | Device directory, where Linux creates device nodes.                                         |
| /etc      | System configuration files directory                                                        |
| /home     | Where Linux creates user directories                                                        |
| /lib      | Where system and applications library files are stored                                      |
| /media    | A common place for mount points used for removable media                                    |
| /mnt      | Mount directory another common for mount points used for removable media                    |
| /opt      | Optional directory, often used to store third-party software packages and data files.       |
| /proc     | Process directory, where current hardware and process information are stored.               |
| /root     | Root home directory                                                                         |
| /sbin     | System binary directory, where many GNU admin-level utilities are stored.                   |
| /run      | Run directory, where runtime data is held during system operation.                          |
| /srv      | Service directory, where local services store their files.                                  |
| /sys      | Where system hardware information files are stored.                                         |
| /tmp      | Temporally directory, where temporally work files can be created and destroyed.             |
| /usr      | User binary directory, where the bulk of GNU user-level utilities and data file are stored. |
| /var      | Variable directory, for files that change frequently, such as log files.                    |
