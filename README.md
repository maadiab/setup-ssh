# setup-ssh
setting up ssh on github

<hr>
$ cd ~/.ssh
<hr>
$ ssh-keygen -o -t rsa -C "mohanad.dev@gmail.com"
<hr>
$ cat id_rsa.pub
<hr>
$ ssh -T git@github.com
<hr>
$ git config --global user.name "maadiab"
<hr>
$ git config --global user.email "mohanad.dev@gmail.com"
