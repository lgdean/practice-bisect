# practice-bisect

This `hello.py` script has a bug.  Oh no!
Luckily, we can take this opportunity to practice using `git bisect`.

For reference, we know things were good at this commit: `b81375a1c`

Here are some steps to get started:
1. git bisect start
1. git bisect good <whatever>
1. git bisect bad HEAD    # or the earliest point where you know it was broken -- often HEAD

Now you've started!  git will help narrow it down for you.
Run `python hello.py` and tell git whether the code is good or bad at each step,
using `git bisect good` and `git bisect bad` as appropriate.

## bonus: scripting

TODO document the check.sh script.

