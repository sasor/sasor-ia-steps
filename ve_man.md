## Abstract

Por problemas de pipenv con la version de python (3.7) que estoy usando, pipenv como entorno
virtual sera removido de este repo, no he probado con otras versiones pero al parecer varios
tienen el problema de Locking...despues de instalar algo pipenv install numpy en mi caso,
decidi usar el venv que viene por defecto con la version 3.7.

#### Pasos
1. crear el entorno virtual
  
  python3.7 -m venv .ia

  source .ia/bin/activate

  pip install jupyter numpy (hasta este commit, se ira actualizando para cada nuevo package)

### Enlaces para el entorno virtual
1. [venv](https://docs.python.org/3/tutorial/venv.html)

### Enlaces del porque no usar pipenv

1. https://www.reddit.com/r/learnpython/comments/928jfq/help_using_pipenv_with_python_37/
2. https://stackoverflow.com/questions/41573587/what-is-the-difference-between-venv-pyvenv-pyenv-virtualenv-virtualenvwrappe
3. https://github.com/pypa/pipenv/issues/4058
4. https://github.com/pypa/pipenv/issues/3827
5. https://stackoverflow.com/questions/56007074/pipenv-is-getting-a-timeout

### Enlaces para jupyter
1. [jupyter sitio oficial](https://jupyter.org/install)
2. [jupyter instalacion](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html)
3. [mas de jupyter](https://jupyter.readthedocs.io/en/latest/running.html#running)
