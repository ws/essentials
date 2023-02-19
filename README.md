# essentials

## Tools I rely on daily:
- [espanso](https://espanso.org) - Complex keyboard shortcuts, fully OSS
- [fzf](https://github.com/junegunn/fzf)
- [autojump](https://github.com/wting/autojump)
- [Rectangle](https://github.com/rxhanson/Rectangle) - After getting burned by [Divvy](https://apps.apple.com/us/app/divvy-window-manager/id413857545?mt=12)'s death I decided to never rely on commercial window management software ever again
- [dateutils](https://github.com/hroptatyr/dateutils)
- [awsume](https://awsu.me) - AWS CLI if the AWS CLI cared about profiles


## Extremely handy when you need it:
- [duti](https://github.com/moretension/duti) - Programatically tell MacOS which app to open a given file extension with. I have a script that sets all the important ones for me (JS, JSX, TS, etc) that runs every time I install apps
- [timezsh](https://blog.mattclemente.com/2020/06/26/oh-my-zsh-slow-to-load/)
- [jq](https://stedolan.github.io/jq/)
- 
```
    timezsh() {
    
    shell=${1-$SHELL}
    
    for  i  in  $(seq 1  10); do /usr/bin/time $shell -i -c exit; done
    
    }
```
- [difftastic](https://github.com/Wilfred/difftastic) - structured diff
- [dog](https://github.com/ogham/dog) - DNS CLI

## Keeping my eye on:
- [dum](https://github.com/egoist/dum)
- [bun](https://bun.sh)
- 
