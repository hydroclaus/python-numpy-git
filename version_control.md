# Distributed Version Control


## Intro
### Basic Concepts

<font color='red'>demo</font> → draw on board


### Reasoning

- one set of codes available for everybody (everything should exist only once)
- can go back in time and access different versions
- we have one repository for the class; you can create your own repositories in your account (see section "our repo")
- de facto standard for coding best practices (which flavour of version control is a matter of choice)
- not only codes, but all ASCII files, can and should be version controlled, also the jupyter notebooks of this course (i.e. the course notes)


### Which One?
- two big contenders in distributed version control: git (`git`) and mercurial (`hg`);
- github seems to be the most common online host, and it provides rendering of jupyter notebook, hence we will use this one;
- git is also implemented by gitlab and bitbucket; bitbucket also provides mercurial hosting

### Connecting to a Host / a Server
- secure communication ([ssh][ssh]) via [public-private key pairs](https://en.wikipedia.org/wiki/Public-key_cryptography); [video](https://www.youtube.com/watch?v=YEBfamv-_do) explaining this visually
- note: at the beginning, this might add too much complexity, hence you can use the [windows gui][github_win_desktop] which allows authentification with username and password



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

    [this][our_repo] is the link to the repository of our course:

        https://github.com/clausTue/geostats18
    
 
    command to clone with ssh

        git clone git@github.com:clausTue/geostats18.git
        
    command to clone with http
    
        git clone https://github.com/clausTue/geostats18.git
    
    

### Notes
- full git [documentation][git_doc]
- a [git and github tutorial][git_github_tutorial]
- full mercurial [documentation][hg_doc]


[our_repo]: https://github.com/clausTue/geostats18
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