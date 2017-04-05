# Análisis de datos con Python
# Temario 

* [Clase1: Introducción al análisis de datos](http://nbviewer.jupyter.org/github/C-Lara/Analisis_datos_Python/blob/master/Clase1/Clase1.ipynb).
* [Clase 2: Ipython and Jupyter](https://nbviewer.jupyter.org/github/C-Lara/Analisis_datos_Python/blob/master/Clase2/Ipython-Jupyter.ipynb).
  - [Errores, depuracion , perfiles en Jupyter](https://nbviewer.jupyter.org/github/C-Lara/Analisis_datos_Python/blob/master/Clase2/Errores-depuracion-perfiles.ipynb).
* [Clase 3-5: Introducción a Pandas](http://nbviewer.jupyter.org/github/C-Lara/Analisis_datos_Python/blob/master/Pre-requisitos/pandas/Pandas.ipynb).
  - [Introducción a Numpy](https://nbviewer.jupyter.org/github/CC-001/Analisis_datos/blob/master/Pre-requisitos/numpy-scipy/Notas-Numpy.ipynb).
  - [Objeto Series de  pandas](https://nbviewer.jupyter.org/github/CC-001/Analisis_datos/blob/master/Clase3/Objeto_series_panda.ipynb).
  - Objeto Dataframe de pandas.
* Clase 6: Numpy para pandas.
* Clase 7-8 Accediendo a los datos con pandas.
* Clase 9-10 Formas de corregir los datos con pandas(tidying up).
* Clase 11-14: Manipulación de datos con pandas.
* Clase 16-18: Aplicaciones: Uso de Scrapy.
* Clase 19-21: Introducción a la visualización con seaborn y Bokeh.
* Clase 22-25: Algoritmos de machine learning.
* clase 26-28: D3 en Jupyter. Ejemplos.

## Requisitos

### Git y Github

[Git](https://git-scm.com/) es un sistema de control de versiones de gran potencia y versatilidad en el manejo de un gran número de archivos de  código fuente a a través del desarrollo no lineal, es decir vía la gestión rápida de ramas y mezclado de diferentes versiones.

Para poder revisar y aprender los comandos necesarios de Git, puedes darle una ojeada al excelente [tutorial de CodeSchool](https://try.github.io/levels/1/challenges/1) o a la [guía](http://rogerdudler.github.io/git-guide/index.es.html) de Roger Dudle para aprender  Git.

[Github](https://github.com/) es una plataforma de desarrollo colaborativo de software utilizado para alojar proyectos (muchos proyectos importantes como paquetes de R, Django, el Kernel de Linux, se encuentran alojados ahí) utilizando Git y el framework Ruby on Rails.

Podemos instalar Git en Ubuntu utilizando el administrador de paquetes `Apt`:

```bash
c-lara@Lara:~$sudo apt-get update
c-lara@Lara:~$sudo apt-get install git
```

Referencias y Lecturas:

- [Usando el GIT](http://www.cs.swarthmore.edu/~newhall/unixhelp/git.php).
- [Practical Git Introduction](http://marc.helbling.fr/2014/09/practical-git-introduction).
- [Visual Git Guide](http://marklodato.github.io/visual-git-guide/index-es.html).

### GitHub Classroom

[GitHub Classroom ](https://classroom.github.com/)  es una propuesta de Github para ser una guía para el salón de clases, donde explican como crear una organización para dictar una clase determinada  y paso a paso convertirla en el motor de aprendizaje del curso.

Videos:

- [Github-Classroom-Getting Started](https://www.youtube.com/watch?v=ChA_zph7aao).
- [GitHub Classroom — How to set up individual assignments ](https://www.youtube.com/watch?v=rTsfBAV7sOo).
- [GitHub Classroom — How to set up group assignments ](https://www.youtube.com/watch?v=-52quDR2QSc).

## Lecturas

###  Clases 1-2

* [What is data science? The future belongs to the companies and people that turn data into products.](https://www.oreilly.com/ideas/what-is-data-science).
* [The End of Theory: The Data Deluge Makes the Scientific Method Obsolete](https://www.wired.com/2008/06/pb-theory/).
* What do you need to Know about Python, Pierluigi Riti 2016 Packt Publishing.
* [Data Science from Scratch](https://www.amazon.com/Data-Science-Scratch-Principles-Python/dp/149190142X/ref=sr_1_1?ie=UTF8&qid=1489852822&sr=8-1&keywords=joel+grus) de  Joel Grus 2015 O’Reilly Media : Chapter 1- 2.
* [Introducing Data Science, Big Data, Machine Learning and more using Python Tools](https://www.manning.com/books/introducing-data-science), Davy Cielen, Arno D. B. Meysman, and Mohamed Ali   Chapter 1-2.
* [Why Python is Slow: Looking Under the Hood](https://jakevdp.github.io/blog/2014/05/09/why-python-is-slow/).
* [Numba vs cython](https://jakevdp.github.io/blog/2013/06/15/numba-vs-cython-take-2/).


### Clase 3-4

* [Memory layout of multi-dimensional arrays](http://eli.thegreenplace.net/2015/memory-layout-of-multi-dimensional-arrays/).
* [Broadcasting in Numpy](http://scipy.github.io/old-wiki/pages/EricsBroadcastingDoc).
* [Intro to pandas data structures](http://www.gregreda.com/2013/10/26/intro-to-pandas-data-structures/).


## Herramientas a  usar 

### Anaconda 

[Anaconda](https://www.continuum.io/downloads) es una distribución completa  libre de [Python](https://www.python.org/) incluye [paquetes de Python ](http://docs.continuum.io/anaconda/pkg-docs).

Anaconda incluye los instaladores de Python 2.7 y 3.5.  La instalación en **Linux**, se encuentra en la página de Anaconda y es más o menos así

1 . Descargar el instalador de Anaconda para Linux.

2 . Después de descargar el instalar, en el terminal, ejecuta para 3.5

```bash
c-lara@Lara:~$ bash Anaconda3-2.4.1-Linux-x86_64.sh

```

Es recomendable leer, alguna de las característica de Anaconda en el siguiente material [conda 30-minutes test drive](http://conda.pydata.org/docs/test-drive.html).

3 . La instalación de paquetes como [seaborn](http://stanford.edu/~mwaskom/software/seaborn/) o [bokeh](http://bokeh.pydata.org/en/latest/) se pueden realizar a través de Anaconda, de la siguiente manera:



``` bash
c-lara@Lara:~$ conda install bokeh
```

Alternativamente podemos desde PyPI usando **pip**:

```bash
c-lara@Lara:~$ pip install bokeh
``` 

El proyecto [Anaconda](https://www.continuum.io/downloads) ha creado [R Essentials](http://anaconda.org/r/r-essentials), que incluye el IRKernel y alrededor de 80 paquetes para análisis de datos, incluyendo `dplyr`, `shiny`, `ggplot2`,`caret`, etc. Para instalar **R Essentials** en un entorno de trabajo, hacemos

```bash
c-lara@Lara:~$ conda install -c r r-essentials
``` 

### Proyecto Jupyter y el Jupyter Nbviewer

El [Proyecto Jupyter](http://jupyter.org/)  es una aplicación web que te permite crear y compartir documentos que contienen código de diversos lenguajes de programación, ecuaciones,  visualizaciones y texto en diversos formatos. El uso de Jupyter incluye la ciencia de datos, simulación numérica, la modelización en estadística, Machine Learning, etc.


[Jupyter nbviewer](https://nbviewer.jupyter.org/)  es un servicio web gratuito que te permite compartir las versiones de archivos realizados por Jupyter, permitiendo el renderizado de diversos fórmatos incluyendo, código latex.

- [Jupyter Documentation](https://jupyter.readthedocs.io/en/latest/).

### MongoDB

[MongoDB](https://www.mongodb.org/) es una sistema de base de datos NoSQL de código abierto utilizado  en aplicaciones web modernas, escrito en C++ le confiere cierta cercanía a los recursos del hardware, de modo que es bastante rápido a la hora de ejecutar sus tareas. MongoDB es una base de datos orientada a documentos, es decir guarda los datos en documentos que son almacenados en un representación binaria de JSON, llamado BSON.

Genbeta:dev tiene una lista de [artículos](http://www.genbetadev.com/bases-de-datos/una-introduccion-a-mongodb) para empezar en el mundo de las bases de datos NoSQL y MongoDB. Es interesantes ver los videos colgados en Youtube sobre MongoDB.

- [¿Qué es MongoDB?](https://www.youtube.com/watch?v=CvIr-2lMLsk).
- [Comparación de SQL y MongoBD](https://www.youtube.com/watch?v=kDSjVTpu8kI).
- [Mongo demo](https://rsandstroem.github.io/MongoDBDemo.html)
- [Contruyendo tu primera aplicación con MongoDB](https://www.youtube.com/watch?v=ClAQEARNUoQ).

Para poder instalar en Ubuntu, es preferible revisar la [documentación](http://docs.mongodb.org/master/tutorial/install-mongodb-on-ubuntu/) desde la página de MongoDB.

## Software

* NumPy, es la biblioteca natural para  python numérico. La característica más potente de NumPy es la  matriz n-dimensional. Esta biblioteca  contiene funciones básicas de álgebra lineal, transformadas de Fourier, capacidades avanzadas de números aleatorios y herramientas para la integración con otros lenguajes de bajo nivel como Fortran, C y C ++.

* SciPy es la biblioeteca para python científico. SciPy se basa en NumPy y es una de las bibliotecas más útiles por la variedad de módulos de ciencia y ingeniería de alto nivel con la que cuenta, como la transformada discreta de Fourier,  álgebra lineal, optimización,  matrices dispersas, etc.

* Matplotlib es una librería de Python  para  crear una gran variedad de gráficos, a partir de histogramas, lineas, etc, usando si es necesario  comandos de látex para agregar matemáticas a los gráficos.

* Pandas es una librería  para operaciones y manipulaciones de datos estructurados. Pandas ha sido añadido  recientemente a Python y han sido fundamental para impulsar el uso de Python en la ciencia de datos.

* Scikit Learn, es tal vez la mejor biblioteca para Machine Learning, construida sobre NumPy, SciPy y Matplotlib, esta biblioteca contiene una gran cantidad de herramientas eficientes para el Machine Learning y el modelado estadístico incluyendo clasificación, regresión, agrupación y reducción de la dimensionalidad.

* Statsmodels es una biblioteca  para el modelado estadístico. Statsmodels es un módulo de Python que permite a los usuarios explorar datos, estimar modelos estadísticos y realizar pruebas estadísticas.

* Seaborn es una libreria para la visualización de datos estadísticos. Seaborn es una biblioteca para hacer atractivos e informativos los gráficos estadísticos en Python. Se basa en matplotlib. Seaborn pretende hacer de la visualización una parte central de la exploración y la comprensión de los datos.

* Bokeh es una biblioteca para crear gráficos interactivos y aplicaciones de datos en modernos navegadores web. Permite al usuario generar gráficos elegantes y concisos al estilo de D3.js. Además, tiene la capacidad de interactividad de alto rendimiento en conjuntos de datos muy grandes o en streaming.

* Blaze es una libreria que sirve  para ampliar la capacidad de Numpy y Pandas a conjuntos de datos distribuidos y en streaming. Puede utilizarse para acceder a datos de una multitud de fuentes, incluyendo Bcolz, MongoDB, SQLAlchemy, Apache Spark, PyTables, etc. Junto con Bokeh, Blaze puede actuar como una herramienta muy potente para crear visualizaciones y  dashboards eficaces con los datos.
 
* Scrapy, es un framework  muy útil para obtener patrones específicos de datos. Tiene la capacidad de comenzar en una URL de sitio web y luego buscar a través de las páginas web del sitio web para recopilar información.
 
* SymPy es una biblioteca  para la computación simbólica. Tiene amplias capacidades desde la aritmética simbólica básica hasta el cálculo, el álgebra, la matemática discreta y la física cuántica. Otra característica útil es la capacidad de formatear el resultado de los cálculos como código LaTeX.
  
