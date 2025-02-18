# BVC Stock prices
[![edr-gh](https://img.shields.io/badge/edr%20gh-blue?&logo=github)](https://github.com/edr-gh) [![esteband-dr](https://img.shields.io/badge/Linkedin-esteban_dr-white)](https://www.linkedin.com/in/esteban-dr/)


Este script nace con la inteción de poder almacenar de forma eficiente los precios de acciones del mercado local (ml) y del mercado global colombiano (mgc) de la Bolsa de Valores de Colombia (BVC) en una base de datos local para que puedan ser utilizados en futuras consultas o análisis.
## Recomendaciones
1) Para realizar una previsualización del notebook, pueden usar la extensión de Google Colab para navegadores.
2) Instalen las librerias que vean en el código y no tengan en sus maquinas.
3) Para usar este repositorio tal cual y como está solo requieren tener Microsoft Edge o pueden optar por descargar el edgedriver en el siguiente enlace: [Microsoft Edge WebDriver](https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/?form=MA13LH#downloads) y escogen el archivo según su sistema operativo.
Si escogen utilizar el WebDriver, entonces deben agregar la ubicación donde esta instalado, por ejemplo:
```python
    driver_ml = webdriver.Edge(options=opciones_ml, service = webdriver.EdgeService(executable_path = "path\to\webdriver"))
```
5) Pueden sustituir Edge por otro navegador como Chrome, Firefox o Safari sustituyendo las lineas en donde vean "Edge" por cualquiera de los navegadores y utilizando el WebDriver según el navegador escogiddo.
