![image](https://github.com/user-attachments/assets/dcd2d6a7-570b-4cf4-8eb1-8142410dab21)
##Assignement description : Create a directory called ""my_folder"", navigate into it, and create a file named ""my_file.txt"" with some text. Then, create another file named ""another_file.txt"" with some text. Concatenate the content of ""another_file.txt"" to ""my_file.txt"" and display the updated content. Finally, list all files and directories in the current directory.
ubuntu@ip-172-31-41-118:~$ pwd
/home/ubuntu
ubuntu@ip-172-31-41-118:~$ mkdir my_folder
ubuntu@ip-172-31-41-118:~$ cd my_folder
ubuntu@ip-172-31-41-118:~/my_folder$ echo "This is the content of my_file.txt" > my_file.txt
ubuntu@ip-172-31-41-118:~/my_folder$ cat my_file.txt
This is the content of my_file.txt
ubuntu@ip-172-31-41-118:~/my_folder$ cat my_file.txt
This is the content of my_file.txt
ubuntu@ip-172-31-41-118:~/my_folder$ echo "This is the content of another_file.txt" > another_file.txt
ubuntu@ip-172-31-41-118:~/my_folder$ cat another_file.txt
This is the content of another_file.txt
ubuntu@ip-172-31-41-118:~/my_folder$ cat another_file.txt >> my_file.txt
ubuntu@ip-172-31-41-118:~/my_folder$ cat my_file.txt
This is the content of my_file.txt
This is the content of another_file.txt
ubuntu@ip-172-31-41-118:~/my_folder$

## Assignement description :Create 20 files with .txt extensions and rename the first 5 files to .yml extension and Print the latest created top 5 files among the total no of files".

![image](https://github.com/user-attachments/assets/e2369fb5-f6cb-48f1-84b3-e3f6fd75ae6f)

ubuntu@ip-172-31-41-118:~/Arun$ for i in {1..20}; do touch "file$i.txt"; done
ubuntu@ip-172-31-41-118:~/Arun$ mv file1.txt file1.yml
mv file2.txt file2.yml
mv file3.txt file3.yml
mv file4.txt file4.yml
mv file5.txt file5.yml
ubuntu@ip-172-31-41-118:~/Arun$ ls -ltr
total 0
-rw-rw-r-- 1 ubuntu ubuntu 0 Nov 10 05:20 file1.yml
-rw-rw-r-- 1 ubuntu ubuntu 0 Nov 10 05:20 file2.yml
-rw-rw-r-- 1 ubuntu ubuntu 0 Nov 10 05:20 file3.yml
-rw-rw-r-- 1 ubuntu ubuntu 0 Nov 10 05:20 file4.yml
-rw-rw-r-- 1 ubuntu ubuntu 0 Nov 10 05:20 file5.yml
-rw-rw-r-- 1 ubuntu ubuntu 0 Nov 10 05:20 file6.txt
-rw-rw-r-- 1 ubuntu ubuntu 0 Nov 10 05:20 file7.txt
-rw-rw-r-- 1 ubuntu ubuntu 0 Nov 10 05:20 file8.txt
-rw-rw-r-- 1 ubuntu ubuntu 0 Nov 10 05:20 file9.txt
-rw-rw-r-- 1 ubuntu ubuntu 0 Nov 10 05:20 file10.txt
-rw-rw-r-- 1 ubuntu ubuntu 0 Nov 10 05:20 file11.txt
-rw-rw-r-- 1 ubuntu ubuntu 0 Nov 10 05:20 file12.txt
-rw-rw-r-- 1 ubuntu ubuntu 0 Nov 10 05:20 file13.txt
-rw-rw-r-- 1 ubuntu ubuntu 0 Nov 10 05:20 file14.txt
-rw-rw-r-- 1 ubuntu ubuntu 0 Nov 10 05:20 file15.txt
-rw-rw-r-- 1 ubuntu ubuntu 0 Nov 10 05:20 file16.txt
-rw-rw-r-- 1 ubuntu ubuntu 0 Nov 10 05:20 file17.txt
-rw-rw-r-- 1 ubuntu ubuntu 0 Nov 10 05:20 file18.txt
-rw-rw-r-- 1 ubuntu ubuntu 0 Nov 10 05:20 file19.txt
-rw-rw-r-- 1 ubuntu ubuntu 0 Nov 10 05:20 file20.txt
ubuntu@ip-172-31-41-118:~/Arun$





