# !bash
## Run multiple commands in one line with `;`, `&&` and `||`

1) Use `;`

No matter the first command cmd1 run successfully or not, always run the second command cmd2:
```bash
# cmd1; cmd2
$ cd myfolder; ls   # no matter cd to myfolder successfully, run ls
```

2) Use `&&`
Only when the first command cmd1 run successfully, run the second command cmd2:
```bash
# cmd1 && cmd2
$ cd myfolder && ls  # run ls only after cd to myfolder
```

3) Use `||`
Only when the first command cmd1 failed to run, run the second command cmd2:

```bash
# cmd1 || cmd2
$ cd myfolder || ls  # if failed cd to myfolder, `ls` will run
```
