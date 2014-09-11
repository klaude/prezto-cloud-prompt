prezto-cloud-prompt
===================

![Screenshot](http://i.imgur.com/mJCZ8rE.png "Screenshot")

This is a port of [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)'s [cloud theme](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/cloud.zsh-theme) to the [prezto](https://github.com/sorin-ionescu/prezto) prompt module. The prompts are the same as the omz version, but instead of defining the prompt's prefix in the `ZSH_THEME_CLOUD_PREFIX` environment variable it's done via the config. 

Installation
------------

Copy `modules/prompt/functions/prompt_cloud_setup` to `~/.zprezto/`.

Usage
-----
This prompt's prefix symbol and colors are customizable:
```
prompt cloud [<symbol>] [<color1>] [<color2>]
```
In `~/.zpreztorc`:
```
zstyle ':prezto:module:prompt' theme 'cloud' ['<symbol>'] ['<color1>'] ['<color2>']
```
If these options are not provided, the symbol defaults to ☁ with colors cyan and green.

Help
----

Run `prompt -h cloud` for more information or `prompt -p cloud` to preview the cloud prompt with custom symbols and colors.
