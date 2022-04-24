## Task 4 Branches and Branches.

** You should perform operations using Command Line processor / Git Bash only! **

#### Follow the next steps to achieve the task completion:

Preparation Steps:

1.  Create a new feature branch *Section5* on basis of branch *development* and switch to it;

Tasks:

2.  Create a new directory *Section5* and create file *newFile.txt* there, adding sample text 'Hello' on the 1st line of the file;
3.  Commit current changes; 
4.  Return to branch *development*. On basis of branch *development* create new branch *s5feature* on local;
5.	Merge branch *Section5* to branch *s5feature* with fast-forwarding option;
6.	Update *Section5/newFile.txt* - put sample text 'World' on the 2nd line of the file;
7.	Commit current changes;
8.	Get back to branch *Section5* and update *Section5/newFile.txt* - put sample text ', World!!!' on the 2nd line of the file;
9.	Commit current changes;
10.	Merge changes from branch *s5feature* without fast-forwarding option - use P4Merge Tool to resolve conflicts;
11.	Update *Section5/newFile.txt* - remove end line symbol on the 1st line of the file, it should now contain only 1 line with sample text 'Hello, World!!!';
12. Сommit these changes to current branch.
13.	In directory *Section5* run command *history >> history4.txt* and stage changes;
14.	Get this file (Topic5/Task4.md from branch *Tasks*) to branch *Section5* to directory *Section5*;
15. Include these changes into new commit with description "Task#4 Details" (Check README.md file for instructions);
16. Push changes to corresponding server branch for a review;
17. Create a merge request to apply required changes to *development* branch;

Final Steps - no need to merge to *master* branch:

18. Once reviewed by Tutor, task is completed.

#### Once all the steps are done, you can follow up on next Topic/Task assignment.