# mkdocs-material-template-es

Plantilla de [mkdocs.org](http://mkdocs.org) con [mkdocs-material](http://squidfunk.github.io/mkdocs-material/) y en español.


## Puesta en marcha

* Clonar repositorio:
```bash
$ git clone https://github.com/fpsampayo/mkdocs-material-template-es.git
```
* Instalar [virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/install.html).
* Crear virtualenv:
```bash
$ mkvirtualenv mkdocs
```
* Instalar dependencias: 
```bash
(mkdocs)$ pip install -r requirements.txt
```
* Iniciar servidor desarrollo: 
```bash
(mkdocs)$ mkdocs serve
```
* Listo!

## Publicación en gh-pages

MkDocs incluye una opción para subir automaticamente a gh-pages la documentación generada.
```
(mkdocs)$ mkdocs gh-deploy
```

## Recursos

* Documentación de [MkDocs](http://www.mkdocs.org/#getting-started)
* Documentación de [mkdocs-material](http://squidfunk.github.io/mkdocs-material/)
