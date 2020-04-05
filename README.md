# Utilizando técnicas de Machine Learning con datos abiertos

Este repositorio detalla los ejemplos prácticos mostrados en la charla 
"Utilizando técnicas de Machine Learning con datos abiertos". Pueden descargar
la presentación de la charla en el siguiente 
[link](https://drive.google.com/file/d/1Q5Q03Kxu7xK5d_2WeRA2YiygTpT9TD92/view?usp=sharing)

## Caso de Predicción de niveles de pobreza de Costa Rica

El código presentado en la carpeta costa-rica se desarrolló en el marco
de la competencia Kaggle [Costa Rican Household Poverty Level Prediction](https://www.kaggle.com/c/costa-rican-household-poverty-prediction).
El código fue desarrollado por [Will Koehrsen](https://www.kaggle.com/willkoehrsen)
y en este repositorio hemos hecho una traducción y adaptación junto a 
[Alejandra Neely](https://github.com/AlejandraNeely). 


## Caso de la Encuesta Longitudinal de Primera Infancia (ELPI) en Chile

Motivados por el código del caso de Costa Rica, se desarrolló con
[Alejandra Neely](https://github.com/AlejandraNeely) un ejemplo de
predicción de niveles de notas basado en variables administrativas
presentes en la ELPI. Para este caso se cuenta con un ejemplo 
de múltiples clases y otro de 2 clases.


## Requisitos

Para correr los códigos de este repositorio se necesita:
- Python 3 ([link](https://www.python.org/downloads/))
- Jupyter Notebooks ([link](https://jupyter.org/install))

## Probar el código de forma local

Una vez que se cuenten con los requisitos es posible instalar
los requerimientos de los notebooks y probar 
el código ejecutando los siguientes comandos en la terminal:

```
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook
```

Luego se les abrirá una ventana del navegador por defecto y podrán correr 
el código bloque por bloque.

## Probar el código en Google Colab

También es posible probar el código utilizando la herramienta de Google
llamada Colab. Básicamente la herramienta te permite trabajar con jupyter 
notebooks en la nube, sin necesidad de instalar nada en tu computador.
Además, tiene la ventaja de poder trabajar colaborativamente de forma
remota.

### Pasos
- Ingresar a https://colab.research.google.com/notebooks/
- Subir el notebook que se quiere revisar
- Subir los datos que utiliza el notebook
- Ejecutar los bloques de código

Google Colab se encargará de instalar los requerimientos necesarios para
ejecutar el código.

## Colaboradores
<table>
  <tr>
    <td align="center"><a href="https://github.com/AlejandraNeely"><img src="https://avatars2.githubusercontent.com/u/32967927?s=400&u=c54a303716f7c4544690e86b18eb2ed5ddc122a1&v=4" width="100px;" alt=""/><br /><sub><b>Alejandra Neely</b></sub></a></td>
    <td align="center"><a href="https://claudioaracena.com"><img src="https://avatars1.githubusercontent.com/u/7471555?s=460&v=4" width="100px;" alt=""/><br /><sub><b>Claudio Aracena</b></sub></a></td>
  </tr>
</table>