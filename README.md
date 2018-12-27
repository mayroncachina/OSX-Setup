# Mac OS X Dev Setup


## oh-my-zsh

### Measuring Overall Startup Time

````
time  zsh -i -c exit
````
or 

`````
for i in $(seq 1 10); do /usr/bin/time zsh -i -c exit; done
`````
