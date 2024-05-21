### Make an installer 
```shell
pyinstaller game.py --noconsole  --add-data="data:data" --add-data="scripts:scripts"
```

### Or

```shell
poetry install
python game.py

```