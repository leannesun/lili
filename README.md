### Installation Instructions
1.  Download the tarball qogremap.tar.gz to your local hard drive (say, in ~/Downloads)
2.  In the terminal, change directory to the location of the tarball and uncompress it
   
    > cd ~/Downloads
    > tar -xvzf qogremap.tar.gz
    
3.  Navigate into the newly created qogremap directory and run the setup script
   
    > cd qogremap
    > sh setup.sh
    
   Follow any instructions that appear and wait for the installation to complete. You may need to enter your
   account password atleast once. The script installs qogremap in the folder ~/nuCore.
4.  If the NVIDIA driver was installed during setup, you may need to restart the computer before running qogremap.    Keep an eye out for a message that asks you to reboot.
5.  The above installation will modify your ~/.bashrc file. To make sure that the changes are reflected in your terminal
   (assuming you haven't already rebooted your computer or opened a new terminal window/tab), source the file:
   
 
    > source ~/.bashrc
    
6.  Run qogremap by invoking it in the terminal:
   
 
    > qogremap
    
10:49
Just warning you that whatever is in your ~/nuCore folder will be deleted
10:50
Try this and let me know if you run into any issues.
