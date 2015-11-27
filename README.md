# Shell-for-git
the shell commands is used to simplify git commands

# .gitconfig

    [user]
            name = aaa
            email = aaa@ericsson.com
    [color]
            status = auto
            diff = auto
    [merge]
            tool = vimdiff
    [core]
            editor = vim
            pager = less -r
    [alias]
            lg = log --graph --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(bold        white)- %an%C(reset)%C(bold yellow)%d%C(reset)' --abbrev-commit --date=relative
            d = difftool
    [diff]
            tool = vimdiff
    [difftool]
            prompt = false
