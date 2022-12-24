LAB5:
1. Compress a file by compress, gzip, zip commands and decompress it again. State the differences between compress and gzip commands. \
![My Remote Image](https://user-images.githubusercontent.com/110028481/209424232-a40e4193-2a5b-419c-97e4-ddfd86a6d11b.png)
differences between compress and gzip commands are in the compression ratio and compression algorithm.\
2. What is the command used to view the content of a compressed file.
zcat
3. Backup /etc directory using tar utility.\
tar -cvf etc.tar /etc/ \
![My Remote Image](https://user-images.githubusercontent.com/110028481/209424238-6eedc643-c15a-4765-99f4-7f4ae319922e.png)
4. Starting from your home directory, find all files that were modified in the last two day.\
find ~ -mtime -2 -ls
5. Starting from /etc, find files owned by root user.
Find /etc -user root
6. Find all directories in your home directory.
Find ~ -type d 
7. Write a command to search for all files on the system that, its name is “.profile”.
Find / -name .profile
8. Identify the file types of the following: /etc/passwd, /dev/pts/0, /etc, /dev/sda
ll /etc/passwd,
ll dev/pts/0,
ll /etc
ll /devsda
9. List the inode numbers of /, /etc, /etc/hosts.
Ls -i /
Ls -i /etc
Ls -i /etc/hosts
10. Copy /etc/passwd to your home directory, use the commands diff and cmp, and Edit in the
file you copied, and then use these commands again, and check the output. \
![My Remote Image](https://user-images.githubusercontent.com/110028481/209424240-337fd873-3c2c-4a88-bb7c-cbc530bc642d.png)
11. Create a symbolic link of /etc/passwd in /boot.
12. Create a hard link of /etc/passwd in /boot. Could you? Why? \
11 & 12→  create soft link and hard-link and tell me why hard link to another partion fails? → because of hard link do not work in other partions. \
![My Remote Image](https://user-images.githubusercontent.com/110028481/209424389-8d2e95ff-60af-4397-9c38-3dd499e8ceac.png)
