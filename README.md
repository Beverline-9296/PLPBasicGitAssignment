
janeb@DESKTOP-6JC84FV MINGW64 ~/Desktop/PLPBasicGitAssignment (main)
$ git init
Initialized empty Git repository in C:/Users/janeb/Desktop/PLPBasicGitAssignment/.git/

janeb@DESKTOP-6JC84FV MINGW64 ~/Desktop/PLPBasicGitAssignment (master)
$ git remote add origin https://github.com/Beverline-9296/PLPBasicGitAssignment.git

janeb@DESKTOP-6JC84FV MINGW64 ~/Desktop/PLPBasicGitAssignment (master)
$ git atatus
git: 'atatus' is not a git command. See 'git --help'.

The most similar command is
        status

janeb@DESKTOP-6JC84FV MINGW64 ~/Desktop/PLPBasicGitAssignment (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        hello.TXT

nothing added to commit but untracked files present (use "git add" to track)

janeb@DESKTOP-6JC84FV MINGW64 ~/Desktop/PLPBasicGitAssignment (master)
$ git add hello.TXT

janeb@DESKTOP-6JC84FV MINGW64 ~/Desktop/PLPBasicGitAssignment (master)
$ git commit -m "Add hello.txt with a greeting"
[master (root-commit) c74d8a1] Add hello.txt with a greeting
 1 file changed, 1 insertion(+)
 create mode 100644 hello.TXT
 
janeb@DESKTOP-6JC84FV MINGW64 ~/Desktop/PLPBasicGitAssignment (master)
$ git push origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 311 bytes | 77.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/Beverline-9296/PLPBasicGitAssignment/pull/new/master
remote:
To https://github.com/Beverline-9296/PLPBasicGitAssignment.git
 * [new branch]      master -> master

janeb@DESKTOP-6JC84FV MINGW64 ~/Desktop/PLPBasicGitAssignment (master)
$
