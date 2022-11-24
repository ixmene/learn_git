# learn_git

KHALEDRABHALLAH@KHALED MINGW64 ~
$ mkdir learn_git_again

KHALEDRABHALLAH@KHALED MINGW64 ~
$ cd learn_git_again

KHALEDRABHALLAH@KHALED MINGW64 ~/learn_git_again
$ touch third.txt


KHALEDRABHALLAH@KHALED MINGW64 ~/learn_git_again
$

KHALEDRABHALLAH@KHALED MINGW64 ~/learn_git_again
$ git init
Initialized empty Git repository in C:/Users/KHALEDRABHALLAH/learn_git_again/.git/

KHALEDRABHALLAH@KHALED MINGW64 ~/learn_git_again (master)
$ git add third.txt

KHALEDRABHALLAH@KHALED MINGW64 ~/learn_git_again (master)
$ git commit -m "adding third.txt"
[master (root-commit) e139a60] adding third.txt
 Committer: KHALED MAISON <KHALED MAISON>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 third.txt

KHALEDRABHALLAH@KHALED MINGW64 ~/learn_git_again (master)
$ git log
commit e139a60032eb1a646ad021887eaca1e5082ecf70
Author: KHALED MAISON <KHALED MAISON>
Date:   Thu Nov 24 20:26:18 2022 +0100

    adding third.txt

KHALEDRABHALLAH@KHALED MINGW64 ~/learn_git_again (master)
$ touch fourth.txt

KHALEDRABHALLAH@KHALED MINGW64 ~/learn_git_again (master)
$ git add fourth.txt

KHALEDRABHALLAH@KHALED MINGW64 ~/learn_git_again (master)
$ git commit -m "adding fourth.txt"
[master fea00c9] adding fourth.txt
 Committer: KHALED MAISON <KHALED MAISON>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 fourth.txt

KHALEDRABHALLAH@KHALED MINGW64 ~/learn_git_again (master)
$ rm third.txt

KHALEDRABHALLAH@KHALED MINGW64 ~/learn_git_again (master)
$ git add third.txt

KHALEDRABHALLAH@KHALED MINGW64 ~/learn_git_again (master)
$ git commit -m "removing third.txt"
[master a9e6248] removing third.txt
 Committer: KHALED MAISON <KHALED MAISON>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 0 insertions(+), 0 deletions(-)
 delete mode 100644 third.txt

KHALEDRABHALLAH@KHALED MINGW64 ~/learn_git_again (master)
$ git log
commit a9e62484faa870c3243854e30395dbfb858afaaf
Author: KHALED MAISON <KHALED MAISON>
Date:   Thu Nov 24 20:27:29 2022 +0100

    removing third.txt

commit fea00c940c7b8b7db780f395f0c75063b3a47b73
Author: KHALED MAISON <KHALED MAISON>
Date:   Thu Nov 24 20:27:04 2022 +0100

    adding fourth.txt

commit e139a60032eb1a646ad021887eaca1e5082ecf70
Author: KHALED MAISON <KHALED MAISON>
Date:   Thu Nov 24 20:26:18 2022 +0100

    adding third.txt

KHALEDRABHALLAH@KHALED MINGW64 ~/learn_git_again (master)
$ git config --global core.pager "cat"

KHALEDRABHALLAH@KHALED MINGW64 ~/learn_git_again (master)
$ - git config --global --list
bash: -: command not found
