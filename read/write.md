user.name=Rahul Raj
user.email=raj.rahul686@gmail.com

git init -> created a .git folder, and gives power to managed by GIT.

there are three stage area of files in git.

1. working area : in this area new file or modified files are there.
2. staging area : In this area GIT knows what cjanges will be done b/w the latest version and last version.
3. repository area : git already managed the file and knows the version history.

different git commands are there :
1.git add filename
2.git commit
3.git status
4.git log
5.git rm --cached filename
6.git restore file.
7.git restore --staged filename :- bring the file from staging area to working area.
This only works if changes done in staging area. 8. git rm --cached filename : -> bring the file in untrack area.

==> difference b/w git rm and git restore :-
rm bring the files in untarck area.
restore bring the file in working area from staged area or remove
the content from working area.

9. git commit -m "message of commit" -> used to pass the message without opening the
   editor in terminal.

   10.git remote :-> list down all the remote connection;

10. git remote add origin link_of_remote :-
    it here origin is name of remote connection. through this we add a new link to the remote repository
    and give a name of it.
11. git remote rm <name of remote> :-
    helps to delete a remote connection.
12. git remote rename <old_name> <new_name> :-
    renames the remote connection.

imp Note:
the name of remote connection is always used to establish the communication b/w the repositorys.

14. `git add <file1> <file2> <file3>` : add the multiple file in staged area.
15. `git add .`:- add all file in staged area from working area.

16. git pull <remote_name> <branch_name> : download the latest changes from the branch of mentioned remote in your local repo.
