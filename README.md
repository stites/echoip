echoip
======

A simple script to get your public and gateway addresses via [ipecho](http://ipecho.net/) and netstat.

To install, simply execute `./install` from the repo directory. Run the command with `echoip`.

Run `./uninstall` to uninstall.

Output
======
The output will look something like this:
``` {bash}
$ echoip
public: 26.106.59.169      # public ip
en0:    10.1.10.2          # local ip and which interface it's attached to
```
However, expect a short lag as wget makes a call to ipecho.net.
