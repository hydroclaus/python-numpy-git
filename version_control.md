# Distributed Version Control

VEGAS has its group repository on GitHub: [https://github.com/VEGASIWS](https://github.com/VEGASIWS)

If you want in:

1. sign up to **github** via the [student developer pack][github_student]
2. send your GitHub username to [claus.haslauer@iws.uni-stuttgart.de](mailto:max.muster@domain.de?subject=Please%20add%20my%20username%20to%20VEGAS-GitHub)

## Reasoning – Why Version Control?
- locally: flag the state of code that is known to work, you can always go back to that ("backup in some sense"); you can go back in time and access different versions / revisions or go back to the state when you know something worked;
- if used with remote (online) server (e.g., GitHub): one set of codes available for everybody in the team (everything should exist only once; same reason why we write functions and aim for modularity);
- de facto standard for coding best practices (which flavour of version control is a matter of choice);
- not only codes, but all ASCII files, can and should be version controlled, also the jupyter notebooks of this course (i.e., the course notes);

## Which System?
- two big contenders in distributed version control: [git](https://git-scm.com) (`git`) and [mercurial](https://www.mercurial-scm.org) (`hg`);
- any system can be installed on the command line / terminal, and might be readily available depending on your system;
- any computer might act as a server, however there are providers such as [GitHub](https://github.com), [GitLab](https://about.gitlab.com) or others. GitHub seems to be the most common online host, and it provides rendering of jupyter notebook (at the time of writing this, maybe others have caught up); git is implemented by github, gitlab and bitbucket; bitbucket also provides mercurial hosting;

## Connecting to a Host / a Server
In order to communicate with the server (either a hosted computer or one in "the cloud" like GitHub), you need to authenticate -- either via username/password or via a secure connection ([ssh][ssh] via [public-private key pairs](https://en.wikipedia.org/wiki/Public-key_cryptography); [video](https://www.youtube.com/watch?v=YEBfamv-_do) explaining this visually). SSH is the recommended way of communication, even though the initial learning curve is a bit steep:


### Steps to get you up and running on your machine:

0. GitHub provides [excellent documentation][github_setting_up] for setting up git depending on your operation system.

    If you are working on __Windows__:

    - there is an excellent terminal environment for git: [git bash][git_bash]
    - there is also [windows gui][github_win_desktop]

1. sign up to **github** via the [student developer pack][github_student]
   
    you need to have an account with github for this course. Please email me your github username or the email adress you used to sign up to bitbucket. __Please sign up with your "academic" email address, i.e. the one that contains `... @ ... uni-tuebingen.de`__. Please set your username such that I have a fair chance to identify who you are. If you don't send me this info, you will not be able to pull/push to that repository, i.e. access relevant course information and codes.   
2. (*optionally*) Generate ssh key pair; upload public key (demo)

    - Windows: [Putty Package](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html)
        - keygen
        - pageant
    - most flavours of linux
        
3. get familiar with `git` (demo)
4. clone our repository

    [this][our_repo] is the link to my public profile. The link to our course is given in the course notes.

    
 
    command to clone with ssh

        git clone git@github.com:hydroclaus/XXX.git
        
    command to clone with http
    
        git clone https://github.com/hydroclaus/XXX.git
    
    

## Resources
- [Beej's Guide to Git](https://beej.us/guide/bggit/)
- ["Mastering git" an online tutorial](https://thoughtbot.com/upcase/mastering-git)
- [Version Control Resources](https://www.git-tower.com/learn/), e.g., [introductory videos "git for complete beginners"](https://www.git-tower.com/learn/git/videos/) from ["Tower", which is a git GUI](https://www.git-tower.com/) for Mac and Windows. For students it is available via the [GitHub Student Developer Pack][github_student]
- [as part of a python course on openedx, there is also information related to git](https://openedx.seas.gwu.edu/courses/course-v1:MAE+MAE6286+2017/courseware/9db220161df94f3a80e44ee70974a17a/8ed5f5580eab45618106f900b8d059f8/)
- [learn git and version control at tower](https://www.git-tower.com/learn/git/ebook/en/command-line/remote-repositories/integrating-remote-changes#start)
- [Oh Shit, Git!?!](https://ohshitgit.com/)
- [git cheat sheet.pdf](https://wizardzines.com/git-cheat-sheet.pdf)
- full git [documentation][git_doc]
- a [git and github tutorial][git_github_tutorial]
- full mercurial [documentation][hg_doc]

## Systems
I recommend you try the key commands (`pull`, `commit`, `push`, `status`) on the command line (if you are on windows, [this is wonderful!](https://gitforwindows.org)) 

### GUIs
- [Tower](https://www.git-tower.com/) -- I recommend this; part of the GitHub student developer pack
- [Github provides a windows gui][github_win_desktop];

### Comparing Files
It is generally a powerful tool to be able to [compare two files](https://en.wikipedia.org/wiki/File_comparison). This is particularly useful if a conflict between versions exists. [Many tools exist on various platforms](https://en.wikipedia.org/wiki/Comparison_of_file_comparison_tools). On the Mac, [Kaleidoscope](https://kaleidoscope.app) or [Delta Walker](https://www.deltawalker.com) (cross-platform) work well; [Changes](https://changesapp.com) has not been updated in a while






[our_repo]: https://github.com/hydroclaus/
[hg_doc]: http://hgbook.red-bean.com/read/
[bibu_ssh]: https://confluence.atlassian.com/bitbucket/set-up-ssh-for-mercurial-728138122.html
[ssh]: https://en.wikipedia.org/wiki/Secure_Shell
[github_ssh]: https://help.github.com/articles/connecting-to-github-with-ssh/
[github_student]: https://education.github.com/pack
[github_win_desktop]: https://desktop.github.com/
[github_setting_up]: https://help.github.com/articles/set-up-git/#platform-mac
[git_bash]: https://git-for-windows.github.io/
[git_doc]: https://git-scm.com/docs
[git_github_tutorial]: https://realpython.com/python-git-github-intro/