# Basic Linux Commands

## Change Directory

```bash
cd path_to_directory     # Change directory to the provided path
cd ~                     # Change directory to the home directory
cd -                     # Go to the last working directory
cd ..                    # Change directory to one step back
cd ../..                 # Change directory to 2 levels back
```

## List Files and Directories

```
ls           # List files and directories in the current directory
ls *.sh      # List all files having a .sh extension
ls -i        # List files and directories with index numbers (inodes)
ls -d */     # List only directories in the current directory
```

## Copy and Move Files

```
cp source destination      # Copy a file or directory to a destination
mv source destination      # Move or rename a file or directory
```

## Remove Files and Directories

```
rm file                 # Remove a file
rm -r directory         # Remove a directory and its contents
rm -f file              # Forcefully remove a file without prompting
```

## Archive and Compression (tar)

```
tar -cvf archive.tar file1 file2 directory  # Create a tar archive
tar -czvf archive.tar.gz directory           # Create a compressed tar archive (gzip)
tar -xvf archive.tar                        # Extract files from a tar archive
tar -xzvf archive.tar.gz                    # Extract files from a compressed tar archive (gzip)
tar -tvf archive.tar                        # List the contents of a tar archive
```

## Change File Permissions (chmod)

```
chmod +x numbers.py     # Make a file executable
chmod 755 numbers.py    # Give root permissions (read, write, execute) to a file
sudo chmod +x numbers.py  # Make a file executable with root permissions
```
