# Archie Build Environment for [LGR/Alexa](https://gitlab.sandia.gov/alexa/lgr)

First time use:

```bash
git clone git@gitlab.sandia.gov:alexa/archie.git
cd archie
echo "make_threads=4" >> archie_config
./archie update
```

Pulling all new changes into existing copy:

```bash
./archie pull all
```

Developing a package:
```bash
./archie changed src/lgrtk_ouo
```
