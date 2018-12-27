# Mac OS X Dev Setup


## oh-my-zsh

### Measuring Overall Startup Time
https://www.growingwiththeweb.com/2018/01/slow-nvm-init.html
````
time  zsh -i -c exit
````
or 

`````
for i in $(seq 1 10); do /usr/bin/time zsh -i -c exit; done
`````
