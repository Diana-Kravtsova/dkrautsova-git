## Task 7 The Golden Rule of Rebasing

** You should perform operations using Command Line processor / Git Bash only! **

#### Follow the next steps to achieve the task completion:

Preparation Steps:

1.  On branch *development* update *Section6/rebase_msample.txt* file on several lines of text there;
2.  Commit your changes with message "DEV of Golden Rule";
3.  Push the latest commit directly to server branch *development*.
4.  On branch *Section6* update *Section6/rebase_msample.txt* file on several lines(same lines as before) of text there;
5.  Commit your changes with message "Feature of Golden Rule";
6.  Push the latest commit directly to server branch *Section6*.

Tasks:

7.  Rebase changes from branch *development* to branch *Section6* (Section6 is prioritized) and resolve conflicts if needed (using rebase, not merge!);
8.  Try pushing directly to corresponding server branch *Section6*;
9.	Since you have received an error message about updates being rejected because the tip of the current branch is behind its remote counterpart -
    - Read about the Golden Rule of Rebasing, (for example, from here: https://habr.com/company/otus/blog/352640/ ), 
    - then undo the rebasing and fix your local branch to include all required updates.
10. Get this file (Topic6/Task7.md from branch *Tasks*) to branch *Section6* to directory *Section6*;
11. In directory *Section6* run command *history >> history7.txt* and stage changes;
12. Include these changes into new commit with description "Task#7 Details" (Check README.md file for instructions);
13. Push changes to corresponding server branch for a review;
14. Create a merge request to apply required changes to *development* branch;

Final Steps - no need to merge to *master* branch:

15. Once reviewed by Tutor, task is completed.

#### Once all the steps are done, you can follow up on next Topic/Task assignment.