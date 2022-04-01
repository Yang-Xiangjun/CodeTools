# basic usage
## deploy to git
reference: https://www.jianshu.com/p/7edb6b838a2e

**Github is just like a larger bracket out of git (git is local, and github is distributed)**
1. make sure git is installed\
easy way: install xcode on mac
2. create ssh key & set git\
    set user.Name and user.Email\
    ssh-keygen -t rsa -C "email"\
    cat .ssh/id_rsa.pub\
    add ssh key in github setting page\
    verify using "ssh -T git@github.com "
3. clone and push github project\
    git clone "SSH"\
    git push\
    other basic git operation\
