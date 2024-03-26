C:\Users\lydia>git init
Reinitialized existing Git repository in C:/Users/lydia/.git/

C:\Users\lydia>git add README.md

C:\Users\lydia>git commit -m "first commit"
[master (root-commit) 9c8a178] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

C:\Users\lydia>git branch -M main

C:\Users\lydia>git remote add origin https://github.com/lypow/lypow.git

C:\Users\lydia>git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 227 bytes | 25.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/lypow/lypow.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
