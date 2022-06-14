   71  git status
   72  git stash -u
   73  git stash 
   74  git stash show -u
   75  git stash list
   76  git status
   77  git hist
   78  git status
   79  git stash show -u stash@{0}
   80  git stash show stash@{0}
   81  git checkout stash@{0}^3 -- Section7/stashIt2.md
   82  git status
   83  git stash show -u stash@{0}
   84  git status
   85  git commit -m "Add new Section7/stashIt2.md file"
   86  git stash drop
   87  git stash list
   88  git stash branch featureStash
   89  git add .
   90  git status
   91  git commit -m "Add new Section7/stashIt.md file"
   92  git stash list
   93  git checkout Section7
   94  git merge featureStash 
   95  git checkout origin/Tasks Topic7/Task9.md
   96  git mv Topic7/Task9.md Section7
   97  git status
   98  cd Section7
   99  history >> history9.txt
  100  git status
  101  git add .
  102  git commit -m "Git Education - Topic7 - Task9 - Task#9 Details"
  103  git fetch
  104  git push origin Section7
  105  exit
  106  cd dkrautsova-git
  107  git push origin -d Section7
  108  git checkout development
  109  git branch -d Section7
  110  git branch -D Section7
  111  git branch -a
  112  git hist
  113  git branch -a
  114  git branch -d featureStash 
  115  git branch -D featureStash 
  116  git hist
  117  git pull
  118  git hist
  119  git checkout -b Section7
  120  mkdir Section7
  121  npp Section7/stashIt.md
  122  git status
  123  git stash save -u "Stashed!"
  124  git stash list
  125  git status
  126  git stash show stash@{0} -u
  127  npp Section7/stashIt2.md
  128  mkdir Section7
  129  npp Section7/stashIt2.md
  130  npp Section7/stashIt3.md
  131  git status
  132  git stash -u 
  133  git stash list
  134  git status
  135  git stash show -u stash@{0}
  136  git checkout stash@{0}^3 -- Section7/stashIt2.md
  137  git status
  138  git stash show -u stash@{0}
  139  git stash list
  140  git commit -m "Add new Section7/stashIt2.md file"
  141  git stash drop
  142  git stash list
  143  git stash branch featureStash
  144  git add .
  145  git commit -m "Add new Section7/stashIt.md file"
  146  git stash list
  147  git checkout Section7
  148  git merge featureStash
  149  git checkout origin/Tasks Topic7/Task9.md
  150  git mv Topic7/Task9.md Section7
  151  git status
  152  cd Section7
  153  history >> history9.txt
  154  git add .
  155  git status
  156  git commit -m "Git Education - Topic7 - Task9 - Task#9 Details"
  157  git hist
  158  git push origin Section7
  159  git checkout development
  160  git hist
  161  cd ..
  162  git hist
  163  git diff development origin/development
  164  git difftool development origin/development
  165  exit
  166  cd projects/starter-web
  167  git status
  168  hit hist
  169  git hist
  170  hit tag myTag
  171  git tag myTag
  172  git hist
  173  git tag --list
  174  git show myTag
  175  git tag --delete myTag
  176  git tag --list
  177  git hist
  178  git tag -a v-1.0
  179  git tag --list
  180  git hist
  181  git show v-1.0
  182  git tag --list
  183  npp index.html
  184  git commit
  185  git commit -a "Tweak file for tagging example"
  186  git commit -a 
  187  git hist
  188  git tag -a v-1.1
  189  npp simple.html
  190  git commit -am "Update for tag 1.1"
  191  git commit --amend
  192  git tag v-1.2 -m "Release 1.2"
  193  git tag --list
  194  git hist
  195  git diff v-1.1 v-1.2
  196  git difftool v-1.0 v-1.2
  197  git status
  198  git hist
  199  git tag -a v-0.9-beta ecffeab
  200  git hist
  201  git tag -a v-0.8-alpha 837fc99
  202  git hist
  203  git tag -a v-0.8-alpha -f 00add77
  204  git hist
  205  git status
  206  git tag --list
  207  git hist
  208  git push origin v-0.9-beta
  209  git push origin v-1.1
  210  git push origin master --tags
  211  git tag --list
  212  git push origin :v-0.8-alpha
  213  exit
  214  cd dkrautsova-git
  215  git pull
  216  git hist
  217  git checkout -b Section8
  218  git hist
  219  git hist
  220  exit
  221  cd dkrautsova-git
  222  git hist
  223  git tag Task#1 ef49467
  224  git hist
  225  git tag Task#2 68d2702
  226  git hist
  227  git tag Task#3 dfcc44a
  228  git hist
  229  git tag --list 
  230   git tag -a Task#4 0252e5c
  231  git show Task#4
  232   git tag -a Task#4 0252e5c
  233  git tag -d Task#4
  234  git tag --list 
  235  git tag -a Task#4 0252e5c
  236  git tag --list 
  237  git show Task#4
  238  git hist
  239  git tag -a Task#5 bdb23e9
  240  git tag -a Task#6 ed840cdb
  241  git tag -a Task#7 426b2782
  242  git tag -a Task#8 34a12f2c
  243  git tag -a Task#9 8abe63df
  244  git hist
  245  git tag --list
  246  git tag Task#1
  247  git tag -a -f Task#1
  248  git hist
  249  git tag -a -f ef494678
  250  git tag -f ef494678
  251  git hist
  252  git tag Task#1 -f ef494678
  253  git hist
  254  git tag -a -f Task#1 ef494678
  255  git tag -d Task#1 ef494678
  256  git hist
  257  git reflog
  258  git tag -d Task#1
  259  git tag -d ef494678
  260  git tag --list
  261  git tag Task#1 ef49467
  262  git tag --list
  263  git tag -a -m "Topic 3 Task 1 Playing with Basics." Task#1
  264  git tag -a Task#1 -f ef49467
  265  git tag --list
  266  git hist
  267  git show Task#4
  268  git show Task#1
  269  git tag -a Task#2 -f 68d2702a
  270  git show Task#2
  271  git tag -a Task#3 -f dfcc44af
  272  git show Task#3
  273  git hist
  274  git status
  275  ls
  276  mkdir Section8
  277  ls
  278  git mv Topic8/Task10.md Section8
  279  git checkout origin/Tasks Topic8/Task10.md
  280  git mv Topic8/Task10.md Section8
  281  cd Section8
  282  history >> history10.txt
  283  git status
  284  git add .
  285  git status
  286  git commit -m "Git Education - Topic8 - Task10 - Task#10 Details"
  287  git status
  288  git push origin Section8
  289  git push origin Section8 --tags
  290  exit
  291  cd projects/starter-web
  292  git log --oneline
  293  git log --oneline --ghraph --decorate --all
  294  git log --oneline --graph --decorate --all
  295  git reset HEAD^1
  296  git log --oneline --graph --decorate --all
  297  git reset HEAD^1
  298  git log --oneline --graph --decorate --all
  299  git reflog
  300  git reset 6c79b39
  301  git log --oneline --graph --decorate --all
  302  git reset HEAD@{2}
  303  git log --oneline --graph --decorate --all
  304  git reset 6c79b39
  305  git log --oneline --graph --decorate --all
  306  git reset HEAD^^
  307  git log --oneline --graph --decorate --all
  308  git reset 6c79b39
  309  git log --oneline --graph --decorate --all
  310  git reset HEAD@{3}
  311  git log --oneline --graph --decorate --all
  312  git reflog
  313  git reset 6c79b39
  314  git log --oneline --graph --decorate --all
  315  exit
  316  cd projects/starter-web
  317  git branch -a
  318  git pull origin master
  319  git branch -a
  320  git fetch origin master
  321  git branch -a
  322  git pull
  323  git branch -a
  324  git fetch origin test
  325  git branch -a
  326  git branch test origin/test
  327  git branch -a
  328  git checkout test
  329  git pull
  330  git diff master test
  331  git checkout master
  332  git branch -a
  333  git branch -d test
  334  git branch -a
  335  git status
  336  npp
  337  ls
  338  npp README.md
  339  git status
  340  git ls-files
  341  git stash
  342  git checkout -b test
  343  git stash pop
  344  git stash list
  345  git checkout master
  346  ls
  347  npp crossdomain.xml
  348  index.html
  349  npp index.html
  350  npp simple.html
  351  git status
  352  git stash
  353  git status
  354  ls
  355  npp humans.txt
  356  git status
  357  git stash
  358  git stash list
  359  git stash apply stash@{1}
  360  git stash list
  361  git stash clear
  362  git stash list
  363  git status
  364  exit
  365  cd projects/starter-web
  366  git status
  367  git commit -am "express updates of README and simple"
  368  git checkout dev
  369  git status
  370  ls
  371  npp simple.html
  372  git status
  373  git commit -am "cherry pick commit"
  374  ls
  375  cd js
  376  ls
  377  npp main.js
  378  npp plugins.js
  379  git commit -am "non-cherry picked commit"
  380  git log --oneline
  381  git checkout master
  382  cd ..
  383  npp simple.html
  384  git status
  385  git hist
  386  npp simple.html
  387  npp simple.html
  388  git commit -am "Updates away from dev"
  389  git hist
  390  git cherry-pick 54346ab
  391  git status
  392  git diff-tree --no-commit-id --name-only -r 54346ab
  393  git diff-tree --no-commit-id --name-only -r 2dc5b15
  394  git add simple.html
  395  git status
  396  git cherry-pick --continue
  397  git status
  398  npp simple.html
  399  git reset --hard HEAD^
  400  git status
  401  git hist
  402  git cherry-pick 54346ab
  403  git status
  404  git diftool 
  405  git difftool 
  406  git mergetool
  407  git status
  408  npp simple.html
  409  git cherry-pick --continue
  410  npp simple.html
  411  git status
  412  git pull origin master
  413  git push origin master
  414  exit
  415  cd projects/starter-web
  416  cd ../..
  417  cd dkrautsova-git
  418  clear
  419  git checkout development
  420  git pull
  421  git checkout -b "Section9"
  422  mkdir Seciton9
  423  cd Seciton9
  424  cd ..
  425  npp Section9/alpha.txt
  426  cd Sectiton9
  427  mkdir Section9
  428  npp Section9/alpha.txt
  429  git status
  430  git add .
  431  git commit -m "add Section9/alpha.txt"
  432  git checkout -b "s9feature"
  433  npp Section9/alpha.txt
  434  git commit -am "update Section9/alpha.txt to Non-Alpha"
  435  git hist
  436  npp Section9/beta.txt
  437  git status
  438  git commit -am "add Section9/beta.txt"
  439  git add .
  440  git status
  441  git commit -m "add Section9/beta.txt"
  442  git status
  443  npp Section9/gamma.txt
  444  git add .
  445  git commit -m "add Section9/gamma.txt"
  446  git status
  447  cd Section9/
  448  ld
  449  ls
  450  exit
  451  cd dkrautsova-git
  452  git hist
  453  git checkout b2411e9
  454  git hist
  455  git checkout s9feature
  456  git hist
  457  git reset --hard 292a8b3
  458  git revert 292a8b3
  459  git hist
  460  git reset 76c4498
  461  git stash -u
  462  git status
  463  git stash list
  464  git checkout Section9
  465  git reflog
  466  git reflog stash
  467  git reflog stash --grep-reflog=s9feature
  468  npp Section9/alpha.txt
  469  git status
  470  git commit -am "update Section9/alpha.txt"
  471  git checkout s9feature
  472  git stash list
  473  git stash apply 
  474  git commit -am "update again Section9/alpha.txt"
  475  git checkout Section9
  476  git hist
  477  git cherry-pick 3cf08fb
  478  git mergetool
  479  git status
  480  git commit -m "cherry-pick Section9/alpha.txt"
  481  git status
  482  npp Section9/alpha.txt
  483  npp Section9/Anwswer.md
  484  cd Section9/
  485  git mv Anwswer.md answer.md
  486  git status
  487  git status
  488  cd ..
  489  git checkout origin/Tasks Topic9/Task11.md
  490  git mv Topic9/Task11.md Section9
  491  cd Section9
  492  history >> history11.txt 
  493  git status
  494  git add .
  495  git status
  496  git commit -m "Git Education - Topic9 - Task11 - Task#11 Details"
  497  git status
  498  git hist
  499  git push origin Section9
  500  exit
  501  git clone https://dkrautsova:F6KQNZbTB4QJ5Kt@okd-gitlab.gomel.iba.by/git-education/templates/initial-final-git.git 
  502  pwd
  503  cd git-eduction
  504  cd initial-final-git
  505  cd ..
  506  cd initial-final-git/
  507  git hist
  508  git checkout a2bbc04
  509  ls 
  510  npp README.md 
  511  git hist
  512  npp README.md 
  513  git checkout bug
  514  ls
  515  npp README.md 
  516  npp code.js 
  517  git blame code.js
  518  git checkout MrDeadpool
  519  ls
  520  npp README.md 
  521  ls -a
  522  npp .gitignore 
  523  git checkout tree
  524  ls
  525  npp README.md 
  526  outClue.sh
  527  ./outClue.sh
  528  ./chamichanga.sh
  529  ./chamichanga.sh
  530  ls
  531  ./chamichangas.sh
  532  git merge live2code
  533  git merge origin/live2code
  534  ./outClue.sh
  535  git checkout mouse
  536  ls
  537  npp README.md 
  538  git hist
  539  git diff bug
  540  git checkout Tutor
  541  git hist
  542  ls
  543  npp README.md 
  544  git checkout origin/Tutor
  545  git hist
  546  ls
  547  npp README.md 
  548  npp README.md 
  549  git remote add yobboDeadpool https://dkrautsova:F6KQNZbTB4QJ5Kt@okd-gitlab.gomel.iba.by/git-education/templates/initial-final-end-git.git
  550  git remote
  551  ls
  552  npp README.md 
  553  git hist
  554  npp README.md 
  555  git fetch
  556  git hist
  557  git fetch yobboDeadpool
  558  git hist
  559  npp README.md 
  560  git checkout master
  561  git hist
  562  git pull yobboDeadpool master
  563  npp README.md 
  564  npp README.md 
  565  cd ../dkrautsova-git/
  566  git checkout gitFinalQuest
  567  git checkout master
  568  git fetch
  569  git checkout gitFinalQuest
  570  history >> gitQuestHistory.md
