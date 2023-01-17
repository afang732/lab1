# Exercise 2: add image to git

This exercise asks you to add a folder to your repo, and thereafter
image to that folder.  And finally commit everything to github!

1. make a new folder (e.g. _images_) to this repo.  Hint: `mkdir`

annafang@Annas-MacBook-Pro-10 lab1 % mkdir images

2. ensure that the folder is there.  Hint: `ls`

annafang@Annas-MacBook-Pro-10 lab1 % ls
command-line.md	images		readme.md
git-image.md	license		solution

3. download an image you like and save it into the image dir you made
   above.
   
4. on command line navigate to the image folder.  Hint: `cd`

annafang@Annas-MacBook-Pro-10 lab1 % cd images

5. ensure that the image is there.  Hint: `ls`

annafang@Annas-MacBook-Pro-10 images % ls
IMG_2958.jpg

6. add the image to your git repo.  Hint: `git add image.jpg`

annafang@Annas-MacBook-Pro-10 images % git add IMG_2958.jpg

7. commit and push the changes.  Hint: `git commit -am ".. your
   message here.. ".
   
   annafang@Annas-MacBook-Pro-10 images % git commit -am "image"
[main a76b5d5] image
 1 file changed, 8 insertions(+)
 
annafang@Annas-MacBook-Pro-10 images % git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 456 bytes | 456.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/afang732/lab1.git
   9b464a4..a76b5d5  main -> main

8. go and check on github that the image is there.

9. as before, edit this file and write here the commands you used.
   Hint: you have to do the edits and commit again, in a similar
   fashion as above.

Did the edits show up on github?

yes
