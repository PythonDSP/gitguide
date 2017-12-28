This tutorial is available at following link, 
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

http://gitguide.readthedocs.io/en/latest/gitguide/index.html

See below link, for complete list of tutorial,
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

http://pythondsp.readthedocs.io/en/latest/pythondsp/toc.html


Command Summary 
^^^^^^^^^^^^^^^

.. Table:: Commands summary

    +-----------------------------------+--------------------------------------------------+
    | Commands                          | Descriptions                                     |
    +===================================+==================================================+
    | **Local Repository**              |                                                  |
    +-----------------------------------+--------------------------------------------------+
    | sudo apt-get install git          | Install git in Linux Ubuntu                      |
    +-----------------------------------+--------------------------------------------------+
    | git config --global               | Set username as 'meher'                          |
    | user.name *meher*                 |                                                  |
    +-----------------------------------+--------------------------------------------------+
    | git config --global user.email    | Set email as 'abc@gmail.com                      |
    | *abc@gmail.com*                   |                                                  |
    +-----------------------------------+--------------------------------------------------+
    | git config --global               | Set 'vim' as default text-editor                 |
    | core.editor "vim"                 |                                                  |
    +-----------------------------------+--------------------------------------------------+
    | git config --global               | Cache username and password                      |
    | credential.helper cache           |                                                  |
    +-----------------------------------+--------------------------------------------------+
    | git init                          | Initialize git repository                        |
    +-----------------------------------+--------------------------------------------------+
    | git status                        | File status i.e. modified and untracked etc.     |
    +-----------------------------------+--------------------------------------------------+
    | git add .                         | Add all untracked files                          |
    +-----------------------------------+--------------------------------------------------+
    | git add *file1 file2*             | Add (stage) file1 and file2                      |
    +-----------------------------------+--------------------------------------------------+
    | git rm --cached *file1*           | Remove the staged file *file1*                   |
    +-----------------------------------+--------------------------------------------------+
    | git commit -m *"commit message"*  | Commit stage file with 'commit message'          |
    +-----------------------------------+--------------------------------------------------+
    | git log                           | Show detail list of commits                      |
    +-----------------------------------+--------------------------------------------------+
    | git log --oneline                 | Show hash and commit name only                   |
    +-----------------------------------+--------------------------------------------------+
    | git log --graph                   | Show commits in the form of graph                |
    +-----------------------------------+--------------------------------------------------+
    | git log --oneline --graph         | Show online-commit in the form of graph          |
    +-----------------------------------+--------------------------------------------------+
    | git diff                          | Differences between unstaged files               |
    |                                   | and previous commit                              |
    +-----------------------------------+--------------------------------------------------+
    | git diff --cached                 | Differences between staged files and             |
    +-----------------------------------+--------------------------------------------------+
    | git diff --stat                   | Show only changed filenames (not the details)    |
    +-----------------------------------+--------------------------------------------------+
    | git reset                         | Remove *all files* from stage list               |
    |                                   | (i.e. back to modified)                          |
    +-----------------------------------+--------------------------------------------------+
    | git reset *file1*                 | Remove *file1* from stage list                   |
    |                                   | (i.e. back to modified)                          |
    +-----------------------------------+--------------------------------------------------+
    | git reset --hard *13802e3*        | Reset to previous commit with hash 13802e3       |
    +-----------------------------------+--------------------------------------------------+
    | git checkout *file1*              | Remove changes from non-staged file1             |
    |                                   | to previous commit                               |
    +-----------------------------------+--------------------------------------------------+
    | git rm *file1*                    | Delete file1 from git (but available             |
    |                                   | in previous commit                               |
    +-----------------------------------+--------------------------------------------------+
    | git branch                        | Show all the branches                            |
    +-----------------------------------+--------------------------------------------------+
    | git branch *branch1*              | Create branch1                                   |
    +-----------------------------------+--------------------------------------------------+
    | git branch -d *branch1*           | Delete branch1                                   |
    +-----------------------------------+--------------------------------------------------+
    | git checkout *branch1*            | Go to branch1                                    |
    +-----------------------------------+--------------------------------------------------+
    | git checkout master               | Go to master branch                              |
    +-----------------------------------+--------------------------------------------------+
    | git merge *branch1*               | Merge the *brach1* to current branch e.g. master |
    +-----------------------------------+--------------------------------------------------+
    | git checkout *13802e3*            | Create new branch from previous commit 13802e3   |
    +-----------------------------------+--------------------------------------------------+
    | git checkout -b *branch1*         | First checkout and then create branch            |
    +-----------------------------------+--------------------------------------------------+
    | **Remote repository**             |                                                  |
    +-----------------------------------+--------------------------------------------------+
    | git remote add *repoName*         | Add remote repo with name 'repoName'             |
    | *https://url_of_repo*             |                                                  |
    +-----------------------------------+--------------------------------------------------+
    | git remote -v                     | Show list of added repoNames                     |
    +-----------------------------------+--------------------------------------------------+
    | git remote remove *repoName*      | Remove repoName from list                        |
    +-----------------------------------+--------------------------------------------------+
    | git push *repoName* *branch1*     | Push 'branch1' to 'repoName'                     |
    +-----------------------------------+--------------------------------------------------+
    | git push *repoName* --all         | Push all branches to repoName                    |
    +-----------------------------------+--------------------------------------------------+
    | git clone                         | Clone or download remote repository              |
    | https://nameOfRemoteRepository    |                                                  |
    +-----------------------------------+--------------------------------------------------+
    | git clone  --depth 1              | Clone only last branch                           |
    | https://nameOfRemoteRepository    |                                                  |
    +-----------------------------------+--------------------------------------------------+
    | git pull *repoName* *branchName*  | Download and merge 'branchName' of repoName      |
    +-----------------------------------+--------------------------------------------------+
    | git fetch *repoName* *branchName* | Download, but not merge repoName                 |
    +-----------------------------------+--------------------------------------------------+