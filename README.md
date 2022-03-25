# How to Upload file to Google Drive from Linux Command Line

## [Step 1: Download gdrive (Google Drive CLI Client)](https://github.com/prasmussen/gdrive)

> wget https://github.com/prasmussen/gdrive/releases/download/2.1.1/gdrive_2.1.1_linux_386.tar.gz

## Step 2: Unzip the Archive

> tar -xvf gdrive_2.1.1_linux_386.tar.gz

## Step 3: Perform Authentication

> ./gdrive about

## Step 4: Clone the repository

> git clone https://github.com/caiolombello/upload-to-drive.git 

## Step 5: Move script to /usr/bin

> sudo mv upload-to-drive/drive /usr/bin

## Step 6: Use the command to upload files

To upload an file
> $ drive 
> $ \<file>

To upload an entire directory
> $ drive 
> $ \<dir> --recursive
