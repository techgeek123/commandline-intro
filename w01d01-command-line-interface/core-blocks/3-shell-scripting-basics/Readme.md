# Shell scripting

## Release 0

Write a script called `sum.sh` which accepts two arguments and echoes the sum of the two numbers. You might need to do some research [here](http://stackoverflow.com/questions/6348902/how-can-i-add-numbers-in-a-bash-script).

Here's a solution:

```shell
echo $(($1+$2))
```

## Release 1
There is much more we can do with shell scripting, including conditional logic, if statements, and much more. But for now, let's try to write some handy scripts to help us with daily tasks. Very commonly we are searching for a process using `ps aux | grep "Something"`. Instead of typing that whole thing, we could make a script that does that for us and passes in an argument. Let's try that out with a script called `process.sh`. It might look something like this.

```shell
ps aux | grep $1
```
Now this is useful if we want to search for a process! If you would like to use the script frequently, you will want to make sure it is somewhere in your $PATH. You can also remove the `.sh` extension if you are doing this.
