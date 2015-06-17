Title: Bancos-json
Date: 2015-06-16 09:26
Category: web
Tags: json, mongodb
Slug: bancos-json
Author: abr4xas
twitter: abr4xas
Summary: Creemos que las bases de datos No-SQL son geniales, por ello queremos ofrecele a los desarrolladores Venezolanos un recurso útil para sus proyectos. Básicamente, BANCOS-JSON es un documento en formato JSON que agrupa gran parte de los bancos dentro del territorio nacional.
image: http://i.imgur.com/88FpuUJ.png

![] (http://i.imgur.com/88FpuUJ.png)
# bancos-json
Código y Bancos correspondientes de Venezuela

Creemos que las bases de datos No-SQL son geniales, por ello queremos ofrecele a los desarrolladores Venezolanos un recurso útil para sus proyectos. Básicamente, BANCOS-JSON es un documento en formato JSON que agrupa gran parte de los bancos dentro del territorio nacional.

Inspirado en el excelente trabajo de:

* [**xombra**](https://github.com/xombra) Por crear este gist sobre: "Código y Bancos correspondientes de Venezuela"
* [**marydn**](https://github.com/marydn) en venezuela-sql
* [**zokeber**](https://github.com/zokeber) en venezuela-json

Y motivado por la ausencia de proyectos de éste tipo, BANCOS-JSON apunta a ser la mejor elección para todo aquél que requiera la organización bancaria de Venezolana en ```.json.```

## Uso
El documento ```bancos.json``` es ideal para ser importado a una base de datos No-SQL. Aunque sabemos que existen muchas soluciones de este tipo, sólo te dejaremos las instrucciones necesarias para importarlo a una de las más conocidas.

#### MongoDB

Para importar ```bancos.json``` a MongoDB sólo debes escribir en tu consola:

```bash
mongoimport --jsonArray --db tu_base_de_datos --collection tu_coleccion --type json --file "/ruta/a/bancos.json"
```

## Referencias

* [JSON](https://es.wikipedia.org/wiki/JSON)
* [MongoDB](http://www.mongodb.com/mongodb-overview)
* [Venezuela-SQL](https://github.com/marydn/venezuela-sql)
* [Venezuela-JSON](https://github.com/zokeber/venezuela-json)
* [Código y Bancos correspondientes de Venezuela](https://gist.github.com/xombra/11335801)

## Licencia

Licencia [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/deed.es_ES)
