# Thunderview
A War Thunder data mine visualization project  

To seed data:

> git clone --depth=1 https://github.com/gszabi99/War-Thunder-Datamine  
> mv War-Thunder-Datamine/aces.vromfs.bin_u/gamedata data/  
> mv War-Thunder-Datamine/char.vromfs.bin_u/config data/  
> cd data  
> zmv -n '(**/)(*).blkx' '$1$2.json' | bash  
> cd ..  
> hugo server  
