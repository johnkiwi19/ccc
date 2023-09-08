


alias  s='clear;echo "git status";git status '

alias  s='clear ; echo -e "git status  \n" ; git status'



#add
alias   a='clear ; echo -e "git add \ngit status  \n" ;git add ; git status'

alias   a='git add . '

alias  aa='git   add -A'



# Remove 
alias ra="git rm --cached '*'"

alias r="git rm --cached "



# git log
alias  l='clear ; echo "git log "     ;git log -1'

alias ll='clear ; echo "git log "     ;git log -2'

alias la='clear ; echo "git log All"  ;git log'

alias  l='clear ; echo -e "git log --oneline  \n" ; git log --oneline'

alias lk='clear ; git log "--pretty=format:\"%C(yellow)%h%Cred%d\\ %Creset%s%Cblue\\ [%cn]\""'





# diff 
alias d="clear ; echo -e 'echo git diff \n\n ' ;git diff "

alias rh='clear;echo "git reset HEAD -- ";git reset HEAD -- '

alias r='clear;echo "git reset";git reset '


alias  n="nvim "

alias  c='git commit -m "'

alias  b=' git branch '




