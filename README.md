# python-mysql-sqlalchemy

Es un proyecto construido con python y el microframework flask para generar un api rest con base de datos mysql. Decidimos utilizar este lenguaje debido a las siguientes características.

  - Portabilidad: Python se ejecuta en Mac, Linux y Windows. Esta diseñado para ser portable, pues se encarga de las particularidades de cada sistema operativo (SO). Lo que es positivo si no queremos escribir código diferente para cada plataforma.
  - Coherencia: Es extremadamente lógico y coherente. La mayoria de veces puede saber como se llama un método sin necesidad de consultar la documentación.
  - Productividad del desarrollador: Python se ejecuta sin la necesidad de pasar por varios pasos de compilacion, por lo que no es necesario esperar para ver los resultados del trabajo.

# Requerimientos
You can also:
  - Es necesario tener instalador python en nuestro equipo
  - Es necesario contar con un IDE como Visual Studio Code
  - Es necesario contar con mysql instalado en el equipo

Markdown is a lightweight markup language based on the formatting conventions that people naturally use in email.  As [John Gruber] writes on the [Markdown site][df1]

> The overriding design goal for Markdown's
> formatting syntax is to make it as readable
> as possible. The idea is that a
> Markdown-formatted document should be
> publishable as-is, as plain text, without
> looking like it's been marked up with tags
> or formatting instructions.

This text you see here is *actually* written in Markdown! To get a feel for Markdown's syntax, type some text into the left window and watch the results in the right.

### Tecnología

Este proyecto utiliza las siguientes tecnologías y librerías para funcionar.

* [Python] - HTML enhanced for web apps!
* [PIP] - awesome web-based text editor
* [SQLAlchemy] - Markdown parser done right. Fast and easy to extend.
* [MySql] - Base de datos relacional
* [Navicat] - Gestor de base de datos

### Instalación

El proyecto requiere [Python](https://www.python.org/) v3+ to run.

Instalamos el entorno virtual en el terminal y lo activamos.

```sh
$ python3 -m venv tutorial-env
$ source tutorial-env/bin/activate
```

Instalamos las dependencias del proyecto e iniciamos el servidor.

```sh
$ pip3 install flask flask-sqlalchemy flask-marshmallow marshmallow-sqlalchemy pymysql
$ python3 src/app.py
```

### Desarrollo

Para documentar el api rest utilizamos swagger

```sh
$ pip3 install flask-restplus
$ python3 src/app.py
```

License
----

MIT


**Tengo deberes sagrados que cumplir ...**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
