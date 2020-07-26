# push-test

temp repo to figure out why WSL2 can't push anymore 😖

words words words

Great, worked from PowerShell. Now what?

Trying from /tmp

So libsecret didn't really work out too well. It throws these errors:

```
** (process:20354): CRITICAL **: 17:55:07.807: could not connect to Secret Service: Cannot autolaunch D-Bus without X11 $DISPLAY
```

Back to trying this from Git Bash

and now back to Ubuntu. Gave up and switched credential.helper to cache:

```
git config --global credential.helper 'cache --timeout=3600'
```

Fine for now, will revisit later on.

Safe to delete this repo.
