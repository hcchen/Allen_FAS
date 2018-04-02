# Linix Tips
##  How do I grep recursively through .gz files?
```sh
find -name \*.eml.gz -print0 | xargs -0 zgrep "STRING"
[agps@ttiavc2 logs]$ find -name catalina.out-20180103.gz -print0 | xargs -0 zgrep "2018-01-03 22:27"
```
[How do I grep recursively through .gz files?](https://unix.stackexchange.com/questions/187742/how-do-i-grep-recursively-through-gz-files)

##
