# .bash_profile
my .bashrc file, dot files,
  
  
A typical install of OS X won't create a .bash_profile for you. When you want to run functions from your command line, this is a must-have.  
Start up Terminal  
Type "cd ~/" to go to your home folder  
Type "touch .bash_profile" to create your new file.  
Edit .bash_profile with your favorite editor (or you can just type "open -e .bash_profile" to open it in  TextEdit.  
Type ". .bash_profile" to reload .bash_profile and update any functions you add.  
  
  
export CLICOLOR=1    
export LSCOLORS=GxFxCxDxBxegedabagaced  
export PS1='\[\033[01;36m\]root--@\e[33mxxx\[\033[00m\]:\[\033[01;36m\]\w\[\033[00m\] \$  '  
alias msfconsole='/opt/metasploit-framework/bin/msfconsole'  
alias msfvenom='/opt/metasploit-framework/bin/msfvenom'  
alias msfupdate='/opt/metasploit-framework/bin/msfupdate'  
alias ngrok='cd ~/Downloads/exploits/'  
alias Desktop='cd ~/Desktop/'  
alias Downloads='cd ~/Downloads/'  
alias etc='cd ~/etc/'  
alias var='cd ~/var/'  
alias usr='cd ~/usr/'  
echo $(curl -s https://api.ipify.org)  
alias ls='ls -1'  
