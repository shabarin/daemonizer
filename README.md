# daemonizer
Run any command in a loop as if it were a daemon, correctly forwarding SIGTERM to it

This script executes given command in a loop and forwards SIGTERM to it.

It can be used to run php scripts in 'daemonized' way  and control execution via tools like [supervisord](http://supervisord.org/).

```
Usage: daemonizer <sleep> <command>
```
