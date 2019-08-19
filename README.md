# jupyter-starter

Tried adding some scripts for running/quitting so it would be easier to remember, but I think the activate script just activates in the shell instance that's spun up by running the script in the first place, so that's not gonna work...

Here are the actual commands, anyway:

## To run from terminal (starting in the project root directory, omit `$ `)
```
$ source env/bin/activate
$ cd ./src
$ jupyter notebook
```

## To quit
crtl+c to close the jupyter notebook server, then just:
`deactivate`
