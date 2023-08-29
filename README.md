# pulpocon2023-cybersecurity-data

## Instalación de dependencias

Antes de nada, creamos unos entornos con python instalado para no tener ningún problema de versiones durante el taller.

### En conda / miniconda
```
conda create --name pulpo2023 python=3.9.15
conda activate pulpo2023
pip install -r requirements.txt
```

### En venv
```
source bin/activate/pulpo2023
pip install -r requirements.txt
```

## Ejecución

Durante el taller vamos a trabajar con libretas de jupyter.
Podemos ejecutarlas levantando jupyter lab, lo cual nos abrirá una pestaña nueva en el navegador desde donde podemos ejecutar nuestras libretas: 

```
jupyter lab
```

...o abriendo directamente los archivos .ipynb en nuestro editor de código favorito como VsCode o PyCharm. Jupyter y VsCode no siempre se llevan bien, así que recomendamos usar el navegador.
