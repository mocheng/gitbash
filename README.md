gitbash
=======

better bash settings for git usage

check out `git-prompt.sh` to somewhere in your local machine. For example

```
cd ~/.bash/
git clone https://github.com/mocheng/gitbash
```

Then, in your `~/.bashrc`, add below lines

```
source ~/.bash/gitbash/git-prompt.sh
PS1="\u@:\w\[\e[1;32m\]\$(parse_git_branch_or_tag)\[\e[0m\]$"

```

Now, your have current branch name displayed in your prompt.

