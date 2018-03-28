# sssh
ssh alias creator


## How to install

```
$ git clone https://github.com/lukluk/sssh.git
$ cd sssh && chmod +x sssh && cp sssh /usr/local/bin
```

done


## How it work

```
$ sssh root@192.168.10.2
you want create alias for 192.168.10.2 [Y/n] ?
alias name : dbmaster
alias created!


Welcome to Ubuntu 16.04.3 LTS (GNU/Linux 4.4.0-116-generic x86_64)

 * Documentation:  https://help.ubuntu.com
 * Management:     https://landscape.canonical.com
 ....

```

next time you can just type this

```
$ ssh dbmaster
or
$ sssh dbmaster
```