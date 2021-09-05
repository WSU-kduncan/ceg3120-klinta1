Setup:
    $ sudo adduser git
    $ su git
    $ cd
    $ mkdir .ssh && chmod 700 .ssh
    $ touch .ssh/authorized_keys && chmod 600 .ssh/authorized_keys
    (append any neccessary keys into this file with $ cat)
    $ cd /srv/git
    $ mkdir project.git
    $ cd project.git
    $ git init --bare
    (then copy this to the local system with the clone command below)
Usage:
    git clone git@3.209.150.255:/home/git/project1.git/
    git add git@3.209.150.255:/home/git/project1.git/
    git commit git@3.209.150.255:/home/git/project1.git/
    git push git@3.209.150.255:/home/git/project1.git/

Proof:
    Screenshots in folder