# Thunderview
A War Thunder data mine visualization project  

To seed data:

> git clone --depth=1 https://github.com/gszabi99/War-Thunder-Datamine  
> cp -r War-Thunder-Datamine/char.vromfs.bin_u/config data  
> cp -r War-Thunder-Datamine/aces.vromfs.bin_u/gamedata data/  
> cd data  
> find . -name '*.blkx' -exec bash -c 'mv "$0" "${0%.blkx}.json"' {} \;  
> cd ..  
> hugo server  
