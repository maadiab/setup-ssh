# setup-ssh
setting up ssh on github

$ cd ~/.ssh
$ ssh-keygen -o -t rsa -C "mohanad.dev@gmail.com"
$ cat id_rsa.pub
$ ssh -T git@github.com
$ git config --global user.name "maadiab"
$ git config --global user.name "mohanad.dev@gmail.com"
