Minimalistic oh-my-zsh theme
============================

This is a theme for [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh).

Since version 3.3 iTerm supports a configurable statusbar, which is capable of
showing, among other things, the git repo status. So, there is no need to
display git status in the prompt anymore. This frees up a lot of space.

So, I took basic
[robbyrussell](https://github.com/robbyrussell/oh-my-zsh/wiki/Themes#robbyrussell)
theme, removed `git_prompt_info` field and added a clock into `$RPROMPT`.

Here is how it looks:

![theme](https://raw.github.com/pavdmyt/simple-oh-my-zsh-theme/master/static/theme_in_nutshell.png)


## Installation

```bash
$ git clone https://github.com/pavdmyt/simple-oh-my-zsh-theme.git
$ cp simple-oh-my-zsh-theme/pavdmyt.zsh-theme ~/.oh-my-zsh/custom/themes/
$ exec $SHELL
```
