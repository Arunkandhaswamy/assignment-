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



