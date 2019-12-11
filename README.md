Please confirm these results for yourself by following the instructions here:
https://github.com/cosmos/gaia/blob/master/docs/migration/cosmoshub-2.md


The exported genesis file:

```
$ jq -S -c -M '' cosmoshub_2_genesis_export.json | shasum -a 256
0fad76f1a598b16aa857f1e2c6538d0b66d7e13d954195afc8cf5026fb88d099  -
```

The final genesis file for cosmoshub-3:

```
$ jq -S -c -M '' genesis.json | shasum -a 256
749c3244ed1bda96309d12b44184666423a258f8aeb249d94dec8b69c0fc83de  -
```

The final genesis time is: `2019-12-11T16:11:34Z`
