# get-shit-done
get-shit-done is an easy to use command line program that blocks websites known to distract us from our work. 

After cloning this repository, put it in your $PATH and ensure it is executable. Execute it as root because it modifies your hosts file and restarts your network daemon.

## To get-shit-done
$ sudo get-shit-done work

## To procrastinate
$ sudo get-shit-done procrastinate

### Add sites to block-list
You can add more sites to the blocked manually by adding it in ~/.config/get-shit-done.ini
Duplicates will be removed, and www is automatically prepended.
For eg. sites = foo.com, bar.com, baz.com

* $siteList
Add or remove elements of this array for sites to block or unblock.


### Source
Forked from https://github.com/leftnode/get-shit-done
