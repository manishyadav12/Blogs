# Getting Started with Git

# What is Git

Git is a version control system that allows users to track changes to files over time and collaborate with others on projects. 

This allows developers to work concurrently on the same code base without causing conflicts. Git allows users to store different versions of their code, called "commits", and easily switch between them or revert to previous versions as needed.

This facilitates team collaboration and allows individual users to experiment with code without worrying about losing their work.

# Git vs GitHub

Git is a version control system used to track changes to computer files and coordinate work on those files among multiple users. It's a tool that developers use to manage their code base and collaborate with others on software projects.

GitHub is a platform that provides hosting for Git repositories. It is a cloud-based service that allows developers to store code, track changes, and collaborate with others on software projects.

In addition to hosting Git repositories, GitHub also offers many features for developers such as Tools for bug tracking, project management, and team collaboration. 
So Git is a code management tool and GitHub is a code storage and sharing platform. They are often used together but are not the same.

# Git Branch

In Git, branches are separate lines of development. a new branch creates a point-in-time copy of your code that you can use to make changes without affecting the main code base.

This allows you to try and work on new features without affecting your main code base. You can also easily commit your changes to the main code base when you're ready.


![GIT-Branchand-its-Operations.webp](https://cdn.hashnode.com/res/hashnode/image/upload/v1670739707236/sTIcr0qux.webp align="left")

# Most used Git command

- Set username and email

$ git config --global user.name
Ex: Manish

$ git config --global user.email
abcdefg@gmail.com

-To check username and email
$ git config --global user.name
$ git config --globaluser.email

-To open IDE
$ code .

-To initialize empty git repository
$ git init

-To show all folders (including hidden)
$ ls -lart

-To check status
$ git status

*First commit
$ git commit

then directs to page then type
ie Initial commit
to exit
esc then :wq

-To make new blank file
$ touch file_name.extension
Ex-  $ touch index.html

-To add all files to staging area
$ git add -A

-To commit
$ git commit -m "comment"

-To go to previous commit
$ git checkout file_name.extension

for all files
$ git checkout -f

-To see previous commits
$ git log

to see previous n commits
$ git log -p -n
Ex- $ git log -p -5 // to see previous 5 commits

-To compare staging area with modifies area
$ git diff

-To skip staging area and to directly commit
$ git -a -m "comment"

-To delete file and remove from staging area
$ git rm file_name.extension

-To only remove from staging area
$ git rm --cached file_name.extension

-To short status
$ git status -s

-To ignore files
~make file .gitignore by giving command $ touch .gitignore

write file name inside .gitignore file

-To ignore file only inside .gitignore file use /filename

-To ignore file with particular extension use  *.extension
Ex- *.cpp // to ignore .cpp files

-To make branch
$ git branch branch_name

-To go to branch
$ git checkout branch_name

-To merge branch
$ git merge branch_name

-To make new and switch to that branch
$ git checkout -b branch_name

That's all Hope You enjoyed reading this 
Follow me for more Such blogs!
✌️✌️


