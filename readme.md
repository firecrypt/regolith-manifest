## Fetch Sources
```
mkdir yocto-regolith
cd yocto-regolith
repo init -u https://github.com/firecrypt/regolith-manifest.git
repo sync
```

## Build
```
source setenv
bitbake regolith-core-image
```
