![image](https://github.com/user-attachments/assets/e71b1bdc-421f-4798-a5bb-ec3361808599)

task 1
ubuntu@ip-172-31-39-149:~$ mkdir MY_FOLDER
ubuntu@ip-172-31-39-149:~$ cd MY_FOLDER
ubuntu@ip-172-31-39-149:~/MY_FOLDER$
ubuntu@ip-172-31-39-149:~/MY_FOLDER$ vim my_file.txt
ubuntu@ip-172-31-39-149:~/MY_FOLDER$ cat my_file.txt
This is arun 123456
ubuntu@ip-172-31-39-149:~/MY_FOLDER$ vim anotherfile_txt
ubuntu@ip-172-31-39-149:~/MY_FOLDER$ cat anotherfile.txt
ubuntu@ip-172-31-39-149:~/MY_FOLDER$ cat anotherfile_txt
this is varun 789
ubuntu@ip-172-31-39-149:~/MY_FOLDER$ cat anotherfile_txt >> my_file.txt
ubuntu@ip-172-31-39-149:~/MY_FOLDER$ cat my_file.txt
This is arun 123456
this is varun 789
ubuntu@ip-172-31-39-149:~/MY_FOLDER$ ls -l
total 8
-rw-rw-r-- 1 ubuntu ubuntu 18 Oct 20 06:10 anotherfile_txt
-rw-rw-r-- 1 ubuntu ubuntu 38 Oct 20 06:12 my_file.txt
ubuntu@ip-172-31-39-149:~/MY_FOLDER$
