# Exercise 1: Navigation

This exercise is an introduction to terminal command.
An example solution is in the _solution_ folder.

Try to achieve the following tasks.  When done, write the command you
used in this file underneath the particular question.

1. Open your terminal (command prompt), either gitbash on windows or
   terminal on mac.
   
2. Which directory are you in?  Find it out!  Hint: `pwd`

annafang@Annas-MacBook-Pro-10 ~ % pwd
/Users/annafang

3. Navigate to your "Documents" directory (or wherever else you keep
   your stuff).  Hint: `cd`
   
   annafang@Annas-MacBook-Pro-10 ~ % cd desktop/info201
   
4. Print out the working directory--are you in the correct place?

  annafang@Annas-MacBook-Pro-10 ~ % cd desktop/info201/lab1

5. List the files there.  Do you see the same files and in the file
   explorer?  Hint: `ls`
   
annafang@Annas-MacBook-Pro-10 lab1 % ls
command-line.md	git-image.md	license		readme.md	solution
annafang@Annas-MacBook-Pro-10 lab1 % 

6. Navigate back to the home folder.  Use the dedicated shortcut for
   home folder.  Hint `~`.
   
annafang@Annas-MacBook-Pro-10 lab1 % cd ~
annafang@Annas-MacBook-Pro-10 ~ % 

7. Commit and push your changes.
annafang@Annas-MacBook-Pro-10 lab1 % git commit -am "commandline"
[main 3401e52] commandline
 1 file changed, 14 insertions(+)
 
 annafang@Annas-MacBook-Pro-10 lab1 % git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 460 bytes | 460.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/afang732/lab1.git
   bd4590f..3401e52  main -> main

8. Check the file on github--do you see your edits there?

Congrats!  You are done!
