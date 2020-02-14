# ibus-mozc for Solus Linux
## About
This repository has configure files to build ibus-mozc for Solus Linux.

## Build
You can see instruction of solbuild at https://getsol.us/articles/packaging/building-a-package/en/

1. Install develop components : ```sudo eopkg it -c system.devel```
2. Install solbuild : ```sudo eopkg it solbuild```
3. Initialize solbuild : ```sodo solbuild init```
4. Clone this repository : ```git clone https://github.com/PG-MANA/solus-ibus-mozc && cd solus-ibus-mozc```
5. Build ibus-mozc package : ```sudo solbuild build```

If success, you can see "ibus-mozc-2.23.2815-1-1-x86_64.eopkg" on current directory.

## Package submit
I submitted this package at https://dev.getsol.us/D7470

## Links
### Twitter
[https://twitter.com/PG_MANA_](https://twitter.com/PG_MANA_)
### Homepage
https://pg-mana.net/
