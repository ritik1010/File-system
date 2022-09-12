We have simulated a file system with block size 4Bytes. Each file is divided in the block of 4Bytes and one text file is created for each block. The block number of each block is stored inside INODE file. So, INODE file contains all the blocks of that file. The name of the INODE (text) file is the inode number of that file. Here, INODE file as well as all blocks are stored in a text file. Note that this is a file system stimulation.

Input and output format:

mf file1 this is file content
This command will create a file with name file1.txt and the content “this is file content” in it.

df file1
This command will delete the file with name file1.txt

rf file1 file2
This command will rename the file with name file1.txt with file name file2.txt

pf file2
This command will print the content of file2.txt

ls
This command will list all the files created with their inode number