### Git configurations

| Alias&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| Config Command         |
|:--------------|:-------------|
| git lo        | ```git config --global alias.lo "log --pretty=format:'%C(magenta)%h%Creset %C(blue)%ad%Creset %C(cyan)%an%Creset - %s%d' --date=short"```|
| git ci        | ```git config --global alias.ci commit``` |
| git co        | ```git config --global alias.co checkout``` |
| git st        | ```git config --global alias.st status``` |
| git br        | ```git config --global alias.br branch``` |
| git dim       | ```git config --global alias.dim 'diff --diff-filter=M -- . ":!package-lock.json"'``` |
                  
                
                  
