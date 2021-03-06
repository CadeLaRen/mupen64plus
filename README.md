mupen64plus-install
===================

A set of utilities for automatically installing mupen64plus on the Raspberry Pi

Users should run the following to install:
```
git clone https://github.com/ricrpi/mupen64plus
cd mupen64plus
./build.sh
sudo ./install.sh
```

mupen64plus will be installed into `/usr/local/bin` and `/usr/local/lib/mupen64plus`

Developers should do the following:
<pre>git clone https://github.com/ricrpi/mupen64plus
cd mupen64plus</pre>
Then modify the 'defaultList' file to point to repositories you want to use.
Run `./dev_build.sh` to download and build into `./test/`

Run `./cfg_developer.sh` to set username/email for pushing updates, setting 'upstream' remotes and creating symbolic links.

Optionally, run `./cfg_ssh.sh` if you want to use ssh keys to push/pull from Github
