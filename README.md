# Mount-Block-Device-File-in-OSX

hdiutil attach -imagekey diskimage-class=CRawDiskImage -nomount filename

This command will give you something like /dev/disk1. 
You can run hdiutil mount /dev/disk1 to actually see the files inside. 
It will print out the location of the mount point, something like /Volumes/Untitled
