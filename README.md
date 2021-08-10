## Work with repository workflow steps

##### 1. Clone repository (if haven't cloned yet):

```
git clone git@okd-gitlab.gomel.iba.by:git-education/<username>-<course_name>.git
```
Ex.
```
git clone git@okd-gitlab.gomel.iba.by:git-education/vpupkin-git.git
```

**Notes:**
- The provided command is about using SSH connection. If you are using https protocol please use instruction provided at Redmine course instructions.

##### 2. When you're ready to start working on new task, create a new remote branch via GitLab based on *development* branch (if needed, if no other souce branch is mentioned in the task details):

```
In the sidebar menu, use Repository > Branches, New Branch.
```


Creating a new branch is the specific step to simulate team working on real project - new branch becomes your local DEVELOPMENT environment with feature branch(es), *development* branch - is your team DEVELOPMENT environment, *master* branch - is your PRODUCTION where only reviewed whole feature changes are allowed to be pushed.

##### 3. Update your local repository from remote and now you're able to switch to the new local branch right away:

```
git fetch
git checkout <new-branch-name>
```

... Work on your task in this branch ...

##### 4. Add and commit your changes:

```
git add
git commit
```

Just to have it well-formatted, please use following format template for commit messages:

```
courseName - taskNumber - itemNumber - detailedComments
```

**Notes:**
- Remember to pull updates from remote development branch regularly.
- Try using fast-forward merging where possible (unless the opposite is requred per task details) in order to have your log tree strict and clean.
- To add file to previous commit use --amend option.
- As you're the only person updating this repo - there shouldn't be any changes. But still, you should make this habbit appear, as your tutor can interfere and put some changes into development branch on his own, so make sure such cases are handled :)

```
git checkout development
git pull origin development
git checkout <branch-name>
git merge development
```

##### 5. Push your changes into corresponding remote branch for review:

```
git push origin <branch-name>
```
Ex.
```
git push origin feature-branch
```

... Then create a *Merge Request* via GitLab UI and wait for your Tutor to complete Verify and Code Review steps:


- In the sidebar menu, use Merge Requests / New Merge Request,  use your feature branch as Source branch and *development* as Target branch. 
- Click *Compare and Continue*.
- Set Title and Description with task info, put your Tutor as Assignee.
- Make sure options to delete source branch after merge and squash commits are not checked.
- Submit merge request. 


If there were any local changes applied to *development* branch to prepare the conditions for a specifc case to resolve - please push such changes to server branch DIRECTLY.
 
 **Notes:**
- Do not merge on your own - until tutor checks and approves it.
- --no-ff flag forces creating merge commit even if fast-forward merge is available.
- If there are any merge conficts defined between your feature branch and target branch - you'll need to resolve them locally, then push new merge commit to the same feature branch.
- Once *development* branch is updated with some solutions, make sure your active feature branch is in sync with it before using it further.

##### 6. Merge all your latest changes to *master* branch

Performed when all tasks of learning section are completed and reviewed - after the latest one is merged to *development* branch. 


- In the sidebar menu, use Merge Requests / New Merge Request, use *development* as Source branch and *master* as Target branch.
- Click *Compare and Continue*.
- Set Title and Description with the provided changes info, put your Tutor as Assignee.
- Make sure options to delete source branch after merge and squash commits are not checked.
- Submit merge request.

**Notes:**
- Do not merge on your own - until tutor checks and approves it.
- Once *master* branch is updated with some solutions, make sure your *development* branch is in sync with it before using it further.

**Once done and reviewed, current task is completed. Congratulations! You can work on the next one.**

