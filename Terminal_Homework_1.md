## Terminal (GitBash) Commands

### What directory am I in?
```bash
pwd
```
### Create directory
```bash
mkdir new_directory
```
### Change directory
```bash
cd your_directory
```
### Create multiple (3) directories
```bash
mkdir directory_1 directory_2 directory_3
```
### Navigate to any of directories above
```bash
cd directory_1
```
### Create 5 files (3 txt, 2 json)
```bash
touch file1.txt file2.txt file3.txt file4.json file5.json
```
### Create 3 directories
```bash
mkdir dir_1 dir_2 dir_3
```
### List all files in the current directory (including hidden files)
```bash
ls -la
```
### Open any of txt files, edit it, save the changes and close the file
1. Open the file using the vi command:
```bash  
vi file1.txt
```
1. Press the "i" key to enter insert mode and make your desired changes.
1. Press the escape "ESC" key to exit insert mode.
1. Type ":wq" and press the enter key to save your changes and close the file.

OR
```bash
cat >> file1.txt
Type your text here...
```
### Navigate up one directory
```bash
cd ..
```
### Move any two of created files to any of created directories
```bash
mv directory_1/file1.txt directory_1/file2.txt directory_2
```

### Copy any two created files to any created directory
```bash
cp directory_1/file3.txt directory_1/file4.json directory_3
```

### Find a file by name
```bash
find . -name "file1.txt"
```
### View file contents in real time/monitor the growth of a file that is being written by a process (grep command)
```bash
tail -f directory_3/file3.txt
```
### Print the first lines of the specified file
```bash
head -3 directory_2/file2.txt
```

### Print the contents of a large text file one page(one screen) at a time
```bash
less directory_2/file1.txt
```
Stop the process by pressing **Ctrl + C**.
Press **q** to quit less.

### Display the system date and time
```bash
date

(output)
Wed Mar  1 13:39:46     2023
```

### Task*
1. Send HTTP request to http://162.55.220.72:5005/terminal-hw-request
```bash
curl http://162.55.220.72:5005/terminal-hw-request
```
1. Write a script that will do the steps 3, 4, 5, 6, 7, 8, 11

   - Create a new file "newscript"
```bash
touch newscript
```
   - Edit this file and add the commands from the steps
```bash
#!/bin/bash
cd your_directory
mkdir directory_1 directory_2 directory_3
cd directory_1
touch file1.txt file2.txt file3.txt file4.json file5.json
mkdir dir_1 dir_2 dir_3
ls -la
mv directory_1/file1.txt directory_1/file2.txt directory_2
```
1. Run the script
```bash
./newscript
```
