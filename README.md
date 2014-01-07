# get-shit-done
get-shit-done is an easy to use command line program that blocks websites known to distract us from our work.

After cloning this repository, put it in your $PATH and ensure it is executable.

Execute it as root because it modifies your hosts file and restarts your network daemon.

## To get-shit-done
$ sudo get-shit-done work

## To procrastinate
$ sudo get-shit-done procrastinate

### $siteList
Add or remove elements of this array for sites to block or unblock.

### ~/.config/get-shit-done.ini
Appends additional sites to block.  Duplicates will be removed, and www is prepended.
sites = foo.com, bar.com, baz.com

### Forked from leftnode/get-shit-done
http://github.com/leftnode/get-shit-done
