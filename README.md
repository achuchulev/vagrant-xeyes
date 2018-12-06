# vagrant-xeyes
a Vagrantproject with graphical interface



## pre-requirements

in macos:

make sure you have [xquartz](https://www.xquartz.org/) installed

## how to use this

make sure x11 accepts connections

```
xhost +
```

make sure your local environment works
```
xeyes
```

then do

```
vagrant up
vagrant ssh -c 'xeyes'
```

