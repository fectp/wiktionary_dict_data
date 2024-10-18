# wiktionary_dict_data
Repositorio de información en español

Versión más reciente del diccionario: 2024-10-17

# Cómo usar estos datos

En un sistema GNU/Linux asegure tener instalado `dict` y `dictd`, por ejemplo en
Debian/Ubuntu

```
apt install dict dictd
```

Decargue wkt_es.dict.gz y wkt_es.index, va a requerir permisos de administrador
para hacer la instalación y actualizar el servicio

```
sudo cp wkt_es.dict.gz wkt_es.index /usr/share/dictd
sudo dictdconfig -w
sudo /etc/init.d/dictd restart
```

Esto instalará una versión local del servicio de diccionario que puede
accederse desde la línea de comandos con `dict` o desde la interfaz gráfica
con [goldendict](https://www.goldendict.org)

Para verificar que el diccionario está correctamente instalado puede usar
```
dict -I
```
Que mostrará los diccionarios instalados, entre los cuales debe estar `wkt_es`

## Más información

* [Un video mostrando wkt_es](https://www.youtube.com/watch?v=bdksv05M0hk)
* [uso de goldendict con wkt_es](https://www.youtube.com/watch?v=3YcWzW1LagY)

## Histórico


## Archivos

Las sumas MD5 de los archivos son

```
e6056665b56dd14d96eb845836526fe1  wkt_es.dict.dz
48151becfe88737c315a4098e2773b4c  wkt_es.index
```
* 2024-10-17 A partir de dump 2024-10-02
* 2024-10-15 Primera versión publicada

