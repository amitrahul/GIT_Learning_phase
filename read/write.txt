user.name=Rahul Raj
user.email=raj.rahul686@gmail.com

git init -> created a .git folder, and gives power to managed by GIT.

there are three stage area of files in git.
1. working area
2. staging area
3. repository area

different git commands are there :
1.git add filename
2.git commit
3.git status
4.git log
5.git rm --cached filename
6.git restore file.
7.git restore --staged filename :- bring the file from staging area to working area.
This only works if changes done in staging area.
8. git rm --cached filename : -> bring the file in untrack area.

==> difference b/w git rm and git restore :-
rm bring the files in untarck area. 
restore bring the file in working area from staged area or remove 
the content from working area.

9. git commit -m "message of commit" -> used to pass the message without opening the
editor in terminal.

10.git remote :-> list down all the remote connection;
11. git remote add origin link_of_remote :-
it here origin is name of remote connection. through this we add a new link to the remote repository
and give a name of it.
12. git remote rm <name of remote> :-
helps to delete a remote connection.
13. git remote rename <old_name> <new_name> :-
renames the remote connection.

imp Note:
the name of remote connection is always used to establish the communication b/w the repositorys.