  
Linux File System:
In Linux, all the filesystems are part of a single directory tree. The main file system is referred to as root (/) filesystem. 

Following are the important and basic commands were taught during the training:

1. pwd: This command tells us about the present working directory. This gives the complete path of the current working directory.
        ex: $ pwd  
            /home/user     (Output)
   
2. cd: cd stands for change directory. This command is used to change the current working directory.
        ex: $ cd dir
             /home/user/dir    (This will be new working directory)
             
3. touch: This command creates new empty file in the current working directory.
        ex: $ touch file.txt
          
4. cat: cat is short for concatenate. This command can be used to show and create files. Also some input can be appended at the end of the file using this command.
        ex: $ cat file.txt  (This will show the contents of file.txt file)
            $ cat > file.txt (This will create a new file with name file.txt)
            $ cat >> file.txt
              Hello World!!    (Hello World!! will get appended at the end of the file)
            
5. df : df stands for disk filesystem. It is used to display disk space used in the filesystem.
         ex: $ df    (shows disk space used in the filesystem.)

6. mkdir: This command is used to make a new directory.
         ex: $ mkdir newdir
         
7. rmdir: This command is used to remove a directory. This command can be used when a directory is empty. 
         ex: $ rmdir newdir
         
8. rmdir -r: -r is the option used with rmdir command that recursively removes a directory with all of its contents.
         ex: $ rmdir -r newdir
         
9. rm: This command is used to remove a file.
         ex: $ rm file.txt
             $ rm -r parent (deletes all the files and sub-directories recursively of the parent directory)
         
10. cp: cp stands for copy. This command cpoies the contents of a file to another file.
         ex: $ cp first.txt second.txt    (The contents of file first.txt will get copied to second.txt)
             $ cp -r olddir newdir        (Copies the contents of olddir recursively into newdir)
         
11. man: This command used to display the manual of any command. This providesthe description of the command specified.
         ex: $ man rmdir
         
12. ls : ls stands for list. This commands lists the contents of a directory.
         ex: $ ls
         
13. mv: mv stands for move. This command moves the contents of one directory to another.
         ex: $ mv one two (contents of one will be moved to two)
         
14. head: head command prints top N lines of a file. By default it prints first 10 lines.
         ex: $ head file.txt
         
15. tail: tail command prints last N lines of the file. By default it prints last 10 lines.
         ex: $ tail file.txt
         
16. ping: ping command is a simple utility used to check whether a network is available and if a host is reachable.
         ex: $ ping 8.8.8.8 (8.8.8.8 is address of google server)
         
17. uname: This command prints the system information.
         ex: $ uname
         
18. top: This command is used to display information about CPU and memory utilization.
         ex: top -n 10