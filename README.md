# lab1
$ cd ~/lab1
$ git status
$ git config --global user.name "Student"
$ git config --global user.email "student@example.com"
$ git remote add origin https://github.com/student-lab/lab1.git
$ git remote -v
origin  https://github.com/student-lab/lab1.git (fetch)
origin  https://github.com/student-lab/lab1.git (push)
$ git branch -M main
$ git add .
$ git commit -m "Первый коммит: добавлены файлы лабораторной работы"
$ git push -u origin main
