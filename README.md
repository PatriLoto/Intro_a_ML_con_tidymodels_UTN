# Introducción a machine learning con R y Tidymodels


Presentadoras: Patricia Loto y Roxana Noelia Villafañe.


Fecha y Lugar
-------------

🗓️ Miércoles 29 de septiembre del 2020  
⏰ Horario: 15 a 17 hs.
:world: [Jornadas Universitarias de Tecnología e Informática 2020 - UTN FRRE](http://juc.frre.utn.edu.ar/)


Descripción
------------------------------------------------------------
Durante los últimos años, el interés y la aplicación de machine learning ha experimentado tal expansión, que se ha convertido en una disciplina aplicada en prácticamente todos los ámbitos de investigación académica e industrial. El creciente número de personas dedicadas a esta disciplina ha dado como resultado todo un repertorio de herramientas con las que acceder a métodos predictivos potentes.
La modelización de datos en estos últimos años ha despertado una gran atención debido al acceso a datos no antes visto. Esto trae aparejado el interés creciente de aprender herramientas útiles que permitan realizar análisis de manera simple, eficaz y reproducible. Tidymodels es un conjunto de paquetes dedicado al aprendizaje automático, que nos proporciona una gramática para modelado de datos con la filosofía del tidyverse. En este taller brindaremos una introducción  a tidymodels y su aplicación a problemas de regresión y clasificación.


# ¿Este curso es para mí?

1.  Tienes conocimientos básicos del lenguaje R y la IDE de Rstudio.
2.  Tienes manejo básico de tidyverse.
3.  Quieres aprender especificamente sobre modelado de datos utilizando el conjunto de paquetes comprendidos en Tidymodels.


Si crees que necesitar reforzar algún punto de los enunciados anteriormente, puedes practicar con los [primers de Rstudio]().

# Objetivos de aprendizaje
Los estudiantes entenderán cómo se entrenan, supervisan y generan predicciones con modelos de Regresión y clasificación utilizando los paquetes del universo Tidymodels.


💻 Antes del workshop
------------------------------------------------------------

En el taller trabajaremos con la versión más reciente de R y Rstudio, por lo que para aprovecharlo es necesario que los tengas instalado:

Instalación de R and RStudio

-   Una versión reciente de **R (>=3.6.4)** disponible de manera gratuita para su descarga en [CRAN](https://cran.r-project.org/).
    
-   Una versión reciente de **Rstudio Desktop (>= 1.3.959)** disponible de manera gratuita para su descarga en [Rstudio](https://www.rstudio.com/download).
    

    En ambos casos, ten en cuenta cuál es el Sistema Operativo que utilizas y la versión del mismo (32 o 64 bits) para descargar la versión correcta tanto de R como de Rstudio.

-   Los paquetes que utilizaremos pueden instalarse, abriendo Rstudio y ejecutando las siguientes sentencias:

```r
mis_paquetes <- c("tidyverse", "tidymodels","devtools", "datos", "kknn", "rpart", "rpart.plot", "ranger", "partykit", "vip", "easypackages")

install.packages(mis_paquetes, repos = "http://cran.rstudio.com")

```

Para poder instalar de manera exitosa los paquetes, es necesario que estés conectado a Internet.

¿Cómo verifico que los paquetes se instalaron correctamente?

Para verificar que los paquetes se cargaron correctamente, por favor ejecutá las sentencias que están a continuación:

```r
easypackages::libraries("tidyverse", "tidymodels","devtools", "datos", "kknn", "rpart", "rpart.plot", "ranger", "partykit", "vip")

```
✍️ Slides y Código
------------------------------------------------------------

Tanto la [presentación]() como los [archivos rmarkdown]() se encuentran en la carpeta **Material**.

📓 **Bibliografía**
-------------------------------------------------------------------------------------------------------------------

Para la elaboración tanto del material teórico como de los ejercicios prácticos se utilizaron como referencia, los libros y sitios descriptos a continuación:

- [Página oficial del proyecto Tidymodels](https://github.com/tidymodels) de Rstudio

- [Tutoriales de Tidymodels](https://www.tidymodels.org/learn/)

- [Introduction to ML con Tidymodels](https://conf20-intro-ml.netlify.app/) de [Allison Hill](https://github.com/rstudio-conf-2020/intro-to-ml-tidy/commits?author=apreshill) en la rstudio::conf 2020

- [Tutoriales de Max Kuhn en la rstudio::conf 2017-2020- Repositorio](https://github.com/topepo/rstudio-conf)

- [Canal de Youtube de Julia Silge](https://www.youtube.com/channel/UCTTBgWyJl2HrrhQOOc710kA) y el [código](https://juliasilge.com/) en su blog personal  

- [Three reasons to use Tidymodels](https://t.co/1HqiujvEDn?amp=1) por Julia Silge en Youtube

- [Tidymodels noRth Conference](https://github.com/llendway/2020_north_tidymodels)

- Free book [Hands on Machine Learning with R](https://bradleyboehmke.github.io/HOML/)

    

:books: Cheatseets and books
============================================================

- [Useful R packages](https://github.com/rstudio/RStartHere)

- [Introduction to Machine Learning](https://ldi.upenn.edu/sites/default/files/Introduction-to-Machine-Learning.pdf)

- Max Kuhn & Johnson Kjell.  [Applied Predictive Modeling](https://link.springer.com/book/10.1007/978-1-4614-6849-3)

- [Data Science Cheatsheets](https://st3.ning.com/topology/rest/1.0/file/get/1211570060?profile=original)

- [Probability Cheatsheets](https://github.com/wzchen/probability_cheatsheet)

