# unix aliases

This alias script does give you helpful scripts for you.
Often you waste your time typing bunch of verbose commands and its arguments but it is not necessary.
And the more chance you type those command sequences, it means you
often waste you time for those repetitive commandline strokes because you do not have any alias for it. This script does solve this issue.

## installation

```
./installer
```

## commands

```
rid    ... git rebase -i develop
rebase ... git rebase $@
bring  ... cp /usr/local/bin/$1 .
cx     ... chmod +x $@ 
amend  ... git commit --amend
commit ... git commit "$@"
```

## author

Kei Sugano tobasojyo@gmail.cim


## special thanks

Curt J. Sampson
