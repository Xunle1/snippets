# Remove NBSP Spaces From Tree Command Output

The `tree` command output has a lot of NBSP spaces, which can be removed by using `sed` command.

```shell
tree | sed 's/\xc2\xa0/ /g' > output.txt
```

Copy from [askubuntu](https://askubuntu.com/a/1467798)
