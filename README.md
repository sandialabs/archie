# Archie Build Environment for [LGR/v3](https://github.com/sandialabs/lgrtk)

First time use:

```bash
git clone git@github.com:sandialabs/archie.git
cd archie
echo "make_threads=8" >> archie_config
./archie update
```

Pulling all new changes into existing copy:

```bash
./archie pull all
```

Developing a package:
```bash
./archie changed src/lgrtk
```
