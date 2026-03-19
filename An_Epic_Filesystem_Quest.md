# An Epic Filesstem Quest
### An Epic Filesystem Quest

In this challenge, I have _hidden the flag_! Here, you will use `ls` and `cat` to follow my breadcrumbs and find it! Here's how it'll work:

0. Your first clue is in `/`. Head on over there.
1. Look around with `ls`. There'll be a file named HINT or CLUE or something along those lines!
2. `cat` that file to read the clue!
3. Depending on what the clue says, head on over to the next directory (or don't!).
4. Follow the clues to the flag!

Good luck!

**Flag:** `pwn.college{UV4dbtuk7Y5TXPHMOOWh1aLGKE1.QX5IDO0wyNwkzNyEzW}`

This is what I did: hacker@commands~an-epic-filesystem-quest:~$ cd /
hacker@commands~an-epic-filesystem-quest:/$ ls
DISPATCH  challenge  flag  lib32   media  opt	run   sys  var
bin	  dev	     home  lib64   mnt	  proc	sbin  tmp
boot	  etc	     lib   libx32  nix	  root	srv   usr
hacker@commands~an-epic-filesystem-quest:/$ ls -a
.	    DISPATCH  challenge  flag  lib32   media  opt   run   sys  var
..	    bin       dev	 home  lib64   mnt    proc  sbin  tmp
.dockerenv  boot      etc	 lib   libx32  nix    root  srv   usr
hacker@commands~an-epic-filesystem-quest:/$ cat flag
cat: flag: Permission denied
hacker@commands~an-epic-filesystem-quest:/$ cat ./flag
cat: ./flag: Permission denied
hacker@commands~an-epic-filesystem-quest:/$ cat challenge
cat: challenge: Is a directory
hacker@commands~an-epic-filesystem-quest:/$ cat boot
cat: boot: Is a directory
hacker@commands~an-epic-filesystem-quest:/$ cat DISPATCH
Tubular find!
The next clue is in: /usr/share/racket/pkgs/scribble-html-lib/scribble/html
hacker@commands~an-epic-filesystem-quest:/$ cat /usr/share/racket/pkgs/scribble-html-lib/scribble/html
cat: /usr/share/racket/pkgs/scribble-html-lib/scribble/html: Is a directory
hacker@commands~an-epic-filesystem-quest:/$ cd /usr/share/racket/pkgs/scribble-html-lib/scribble/html
hacker@commands~an-epic-filesystem-quest:/usr/share/racket/pkgs/scribble-html-lib/scribble/html$ ls
WHISPER   extra.rkt  info.rkt  lang.rkt  resource.rkt
compiled  html.rkt   lang      main.rkt  xml.rkt
hacker@commands~an-epic-filesystem-quest:/usr/share/racket/pkgs/scribble-html-lib/scribble/html$ cat WHISPER
Great sleuthing!
The next clue is in: /usr/lib/python3/dist-packages/jedi/inference/compiled/subprocess

The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special options to 'ls'.
hacker@commands~an-epic-filesystem-quest:/usr/share/racket/pkgs/scribble-html-lib/scribble/html$ cd /usr/lib/python3/dist-packages/jedi/inference/compiled/subprocess
hacker@commands~an-epic-filesystem-quest:/usr/lib/python3/dist-packages/jedi/inference/compiled/subprocess$ ls -a
.  ..  .SNIPPET  __init__.py  __main__.py  __pycache__	functions.py
hacker@commands~an-epic-filesystem-quest:/usr/lib/python3/dist-packages/jedi/inference/compiled/subprocess$ cat .SNIPPET
Yahaha, you found me!
The next clue is in: /usr/lib/x86_64-linux-gnu/gedit/plugins/quickopen/__pycache__

The next clue is **delayed** --- it will not become readable until you enter the directory with 'cd'.
hacker@commands~an-epic-filesystem-quest:/usr/lib/python3/dist-packages/jedi/inference/compiled/subprocess$ cd /usr/lib/x86_64-linux-gnu/gedit/plugins/quickopen/__pycache__
hacker@commands~an-epic-filesystem-quest:/usr/lib/x86_64-linux-gnu/gedit/plugins/quickopen/__pycache__$ ls
DOSSIER  __init__.cpython-38.pyc  popup.cpython-38.pyc	virtualdirs.cpython-38.pyc
hacker@commands~an-epic-filesystem-quest:/usr/lib/x86_64-linux-gnu/gedit/plugins/quickopen/__pycache__$ ls -a
.   DOSSIER		     popup.cpython-38.pyc
..  __init__.cpython-38.pyc  virtualdirs.cpython-38.pyc
hacker@commands~an-epic-filesystem-quest:/usr/lib/x86_64-linux-gnu/gedit/plugins/quickopen/__pycache__$ cat DOSSIER
Yahaha, you found me!
The next clue is in: /opt/linux/linux-5.4/net/6lowpan
hacker@commands~an-epic-filesystem-quest:/usr/lib/x86_64-linux-gnu/gedit/plugins/quickopen/__pycache__$ cd /opt/linux/linux-5.4/net/6lowpan
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/net/6lowpan$ ls
6lowpan_i.h  debugfs.c	nhc_dest.c	    nhc_ghc_ext_route.c  nhc_mobility.c
BRIEF	     iphc.c	nhc_fragment.c	    nhc_ghc_icmpv6.c	 nhc_routing.c
Kconfig      ndisc.c	nhc_ghc_ext_dest.c  nhc_ghc_udp.c	 nhc_udp.c
Makefile     nhc.c	nhc_ghc_ext_frag.c  nhc_hop.c
core.c	     nhc.h	nhc_ghc_ext_hop.c   nhc_ipv6.c
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/net/6lowpan$ cat BRIEF
Great sleuthing!
The next clue is in: /opt/pwndbg/.venv/lib/python3.8/site-packages/pkg_resources/_vendor/importlib_resources

Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/net/6lowpan$ ls /opt/pwndbg/.venv/lib/python3.8/site-packages/pkg_resources/_vendor/importlib_resources
INFO-TRAPPED  __pycache__   _common.py	_itertools.py  abc.py	 readers.py
__init__.py   _adapters.py  _compat.py	_legacy.py     py.typed  simple.py
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/net/6lowpan$ cat /opt/pwndbg/.venv/lib/python3.8/site-packages/pkg_resources/_vendor/importlib_resources/INFO-TRAPPED
Great sleuthing!
The next clue is in: /opt/linux/linux-5.4/tools/arch/arm64/include

Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/net/6lowpan$ ls /opt/linux/linux-5.4/tools/arch/arm64/include
TRACE-TRAPPED  asm  uapi
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/net/6lowpan$ cat /opt/linux/linux-5.4/tools/arch/arm64/include/TRACE-TRAPPED
Lucky listing!
The next clue is in: /usr/local/lib/python3.8/dist-packages/jinja2-3.1.6.dist-info

The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special options to 'ls'.
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/net/6lowpan$ cd /usr/local/lib/python3.8/dist-packages/jinja2-3.1.6.dist-info
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/jinja2-3.1.6.dist-info$ ls -a
.  ..  .SECRET	INSTALLER  METADATA  RECORD  WHEEL  entry_points.txt  licenses
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/jinja2-3.1.6.dist-info$ cat .SECRET
Congratulations, you found the clue!
The next clue is in: /usr/lib/python3/dist-packages/sage/media/__pycache__
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/jinja2-3.1.6.dist-info$ cd /usr/lib/python3/dist-packages/sage/media/__pycache__
hacker@commands~an-epic-filesystem-quest:/usr/lib/python3/dist-packages/sage/media/__pycache__$ ls
LEAD  __init__.cpython-38.pyc  all.cpython-38.pyc  wav.cpython-38.pyc
hacker@commands~an-epic-filesystem-quest:/usr/lib/python3/dist-packages/sage/media/__pycache__$ cat LEAD
CONGRATULATIONS! Your perserverence has paid off, and you have found the flag!
It is: pwn.college{4kvQtnSEAAVl4uCwk9gI26YkH4C.QX5IDO0wyM1UjM2EzW}
