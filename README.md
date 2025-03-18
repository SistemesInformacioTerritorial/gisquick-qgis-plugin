# Plugin compatible amb servidor windows

## Instal.lacio plugin
0. Desinstalar plugin oficial, si s'escau
1. Descarregar dbhash-plugin.zip
2. Instal·lar el plugin com a ZIP



## Development

### Build plugin's library

```
cd go
go build -ldflags="-s -w" -buildmode=c-shared -o ../python/gisquick.so cmd/main.go
```

### Plugin development (Linux):
```
ln -s `pwd`/python ~/.local/share/QGIS/QGIS3/profiles/default/python/plugins/gisquick
```
