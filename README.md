Ejemplo de uso de `requirements.txt`
====================================

Este es un repositorio de ejemplo sobre el uso combinado de `pip`, `venv` y `requeriments`.


## Uso

En un entorno con `python3.8` y `pip3` instalado, ejecutar los siguientes comandos:

```bash
# clonamos repositorio
$ git clone git@github.com:AJVelezRueda/ejemplo_venv_requirements.git
$ cd ejemplo_venv_requirements
# creamos y activamos un entorno virtual
$ python3 -m venv .venv
$ source .venv/bin/activate
# Instalamos las dependencias listadas en requirements.txt
$ pip3 install -r requirements.txt
# Observamos que dependencias instaló
$ pip freeze
```
