## Task 11 Cherry Pick on the top of a Cake.

** You should perform operations using Command Line processor / Git Bash only! **

#### Follow the next steps to achieve the task completion:

Preparation steps:

1.  Create a new feature branch *Section9* on basis of branch *development* and switch to it;
2.  On branch *Section9* create a new file *Section9/alpha.txt* with text 'Alpha' in it and commit changes;			(0)
3.  Create and go to local branch *s9feature* on basis of branch *Section9*.
4.  Update file *Section9/alpha.txt* with text 'Non-Alpha' and commit changes.										(1)
5.  Create a new file *Section9/beta.txt* with text 'Beta' in it and commit changes.								(2)
6.  Create a new file *Section9/gamma.txt* with text 'Gamma' in it and commit changes.								(3)

Tasks:

7.  Get back to commit (1) to check the repo, then move to commit (3).
8.  Reset your folder to state of commit (2) so file updates also resetted.
9.  Revert that commit changes to commit (1).
10. Reset your folder to state of commit (0), but leave file changes ustaged - and stash them.
11. Get back to branch *Section9* and list out stashes specifically from *s9feature* branch.
12. Update file *Section9/alpha.txt* with text 'Full-Alpha' and commit changes.
13. Get back to branch *s9feature*, apply stash and commit changes.
14. Cherry-pick latest commit of branch *s9feature* to branch *Section9*. Answer the question:
	*What is the differense in using RESET / REVERT / CHECKOUT in redoing things?*
15.	On branch *Section9* create a new file *Section9/answer.md* with that answer.
16. Get this file (Topic9/Task11.md from branch *Tasks*) to branch *Section9* to directory *Section9*;
17. In directory *Section9* run command *history >> history11.txt* and stage changes;
18.	Include these changes into new commit with description "Task#11 Details" (Check README.md file for instructions);
19. Push changes to corresponding server branch for a review;
20. Create a merge request to apply required changes to *development* branch;

Final Steps - merge all to *master* branch:

21. Once reviewed by Tutor, create a merge request to apply required changes from *development* to *master* branch;
22. Once reviewed by Tutor, task is completed.

#### Once all the steps are done, you can follow up on next Topic/Task assignment.