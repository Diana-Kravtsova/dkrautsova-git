## Task 6 Rebase, take it easy.

** You should perform operations using Command Line processor / Git Bash only! **

#### Follow the next steps to achieve the task completion:

Preparation Steps:

1.  Create a new feature branch *Section6* on basis of branch *development* and switch to it;
2.  On local create branch *Section6r* on basis of branch *Section6* and go to it.
3.  On branch *development* create a new file *Section6/rebase_msample.txt* and set several lines of text there;
4.  Commit your changes with message "Rebase source" and merge updates to branch *Section6r*;
5.  On branch *development* put some more updates to the same lines and commit changes with message "DEV Rebase 2".
6.  On branch *development* put some more updates to the same lines and commit changes with message "DEV Rebase 3".
7.  On branch *Section6r* add a new file *Section6/rebase_fsample.txt* and set several lines of text there;
8.  Put some more updates to the same lines and commit changes with message "Feature Rebase 2".
9.  Put some more updates to the same lines and commit changes with message "Feature Rebase 3".

Tasks:

10. Rebase changes from branch *development* to branch *Section6r* - no conflicts should appear.
11. On branch *Section6r* put some more updates to the *Section6/rebase_msample.txt* file and commit changes with message "Feature Rebase 4 conflicts".
12. Get on branch *development* and put some more updates to *Section6/rebase_msample.txt* file - text should differ on the same lines between branches *development* and *Section6r*.
13. Commit your changes with message "DEV Rebase 4 conflicts";
14. Rebase changes from branch *development* to branch *Section6r* - abort conflicts and then rebase again to resolve conflicts(using rebase, not merge!).
15. Merge changes from branch *Section6r* to branch *Section6*;
16. Get this file (Topic6/Task6.md from branch *Tasks*) to branch *Section6* to directory *Section6*;
17. In directory *Section6* run command *history >> history6.txt* and stage changes;
18. Include these changes into new commit with description "Task#6 Details" (Check README.md file for instructions);
19. Push changes to corresponding server branch for a review;
20. Create a merge request to apply required changes to *development* branch;

Final Steps - no need to merge to *master* branch:

21. Once reviewed by Tutor, task is completed.

#### Once all the steps are done, you can follow up on next Topic/Task assignment.