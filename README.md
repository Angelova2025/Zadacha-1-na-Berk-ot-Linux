vboxuser@ubuntu26:~/Documents/Linux_task$ mkdir task1
vboxuser@ubuntu26:~/Documents/Linux_task$ cd task1
vboxuser@ubuntu26:~/Documents/Linux_task/task1$ mkdir lessons exercises temp
vboxuser@ubuntu26:~/Documents/Linux_task/task1$ cd lessons
vboxuser@ubuntu26:~/Documents/Linux_task/task1/lessons$ touch lesson1.txt lesson2.txt
vboxuser@ubuntu26:~/Documents/Linux_task/task1/lessons$ ls
lesson1.txt  lesson2.txt
vboxuser@ubuntu26:~/Documents/Linux_task/task1/lessons$ cd task1
bash: cd: task1: No such file or directory
vboxuser@ubuntu26:~/Documents/Linux_task/task1/lessons$ cd exercises
bash: cd: exercises: No such file or directory
vboxuser@ubuntu26:~/Documents/Linux_task/task1/lessons$ cd ..
vboxuser@ubuntu26:~/Documents/Linux_task/task1$ cd exercises
vboxuser@ubuntu26:~/Documents/Linux_task/task1/exercises$ touch exercise1.txt exercise2.txt draft.txt
vboxuser@ubuntu26:~/Documents/Linux_task/task1/exercises$ ls
draft.txt  exercise1.txt  exercise2.txt
vboxuser@ubuntu26:~/Documents/Linux_task/task1/exercises$ rm draft.txt
vboxuser@ubuntu26:~/Documents/Linux_task/task1/exercises$ cd..
cd..: command not found
vboxuser@ubuntu26:~/Documents/Linux_task/task1/exercises$ cd ..
vboxuser@ubuntu26:~/Documents/Linux_task/task1$ rmdir temp
vboxuser@ubuntu26:~/Documents/Linux_task/task1$ ls -R
.:
exercises  lessons

./exercises:
exercise1.txt  exercise2.txt

./lessons:
lesson1.txt  lesson2.txt
vboxuser@ubuntu26:~/Documents/Linux_task/task1$ cd ..
