# practice-bisect
practice using git bisect

For reference, we know things were good at this commit: b81375a1c

Here are some steps to get started:
git bisect start
git bisect good <whatever>
git bisect bad HEAD    # or the earliest point where you know it was broken -- often HEAD

Then it'll get you going!  Try `python hello.py` and tell git what's good or bad.

TODO document the check.sh script.

