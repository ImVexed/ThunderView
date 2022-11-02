# Thunderview

To seed data:

> git clone --depth=1 https://github.com/gszabi99/War-Thunder-Datamine
> mv War-Thunder-Datamine/aces.vromfs.bin_u/gamedata data/
> cd data
> zmv -n '(**/)(*).blkx' '$1$2.json' | bash
> cd ..