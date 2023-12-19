# Welcome to the Linux Command Challenge! 🐧

## Explore and test your skills with these basic Linux commands. Try completing the tasks listed below:

### Change Directory

#### Change directory to the provided path

cd path_to_directory

#### Change directory to the home directory

cd ~

#### Go to the last working directory

cd -

#### Change directory to one step back

cd ..

#### Change directory to 2 levels back

cd ../..

### List Files and Directories

#### List files and directories in the current directory

ls

#### List all files having a .sh extension

ls \*.sh

#### List files and directories with index numbers (inodes)

ls -i

#### List only directories in the current directory

ls -d \*/

### Copy and Move Files

#### Copy a file or directory to a destination

cp source destination

#### Move or rename a file or directory

mv source destination

##### Remove Files and Directories

#### Remove a file

rm file

#### Remove a directory and its contents

rm -r directory

#### Forcefully remove a file without prompting

rm -f file

### Archive and Compression (tar)

#### Create a tar archive

tar -cvf archive.tar file1 file2 directory

#### Create a compressed tar archive (gzip)

tar -czvf archive.tar.gz directory

#### Extract files from a tar archive

tar -xvf archive.tar

#### Extract files from a compressed tar archive (gzip)

tar -xzvf archive.tar.gz

#### List the contents of a tar archive

tar -tvf archive.tar

### Change File Permissions (chmod)

#### Make a file executable

chmod +x numbers.py

#### Give root permissions (read, write, execute) to a file

chmod 755 numbers.py

#### Make a file executable with root permissions

sudo chmod +x numbers.py
