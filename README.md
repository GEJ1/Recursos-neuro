# Recursos-neuro  🧠

Repo para ir agregando recursos en Neurociencia Cognitva, computacional y temas relacionados (estadística, métodos de análisis, Machine Learning, etc).
Enfocado a cursos/tutoriales en español e inglés.
Solo contenido gratuito.

Si conocés a alguien a quien le pueda servir, compartilo y si te gustó dale una estrella :star:

Si deseas agregar un recurso podés hacer un pull request (si no sabes cómo fijate [acá](https://www.freecodecamp.org/espanol/news/como-hacer-tu-primer-pull-request-en-github/))

## Temas
- [EEG](#EEG)
- [fMRI](#fMRI)
- [Eye/gaze tracking](#Eyetracking)
- [Software para crear experimentos (online y offline)](#Experimentos)
- [Neurociencia computacional](#Neurociencia-computacional)
- [Neuroanatomía](#Neuroanatomia)
- [Herramientas matemáticas / ciencia de datos](#Herramientas)
- [Programacion en Python](#Python)
- [Programacion en R](#R)
- [Ciencias Cognitivas](#Ciencias-Cognitivas)
- [Machine Learning](#Machine-Learning)
- [Deep Learning](#Deep-Learning)

# EEG

* En general el contenido de Mike X Cohen es genial. [Su canal](https://www.youtube.com/channel/UCUR_LsXk7IYyueSnXcNextQ/playlists)
    * Neuroscience source separation:
      * [Playlist](https://youtu.be/xhKkl53sgwU)
      * [Repositorio](https://github.com/mikexcohen/NeuroscienceSourceSeparation)

* [EEGLAB youtube channel (canal de su creador Arnaud Delorme)](https://www.youtube.com/channel/UCK8x1bdiHWmT0yCNEjTcEvA)
    * [EEGLAB introduction](https://www.youtube.com/playlist?list=PLXc9qfVbMMN2NksmDeqizCI1z5DJBlqC6)
    * [General Linear Model of EEG using EEGLAB/LIMO](https://www.youtube.com/playlist?list=PLXc9qfVbMMN2Vrzte9ul3nrrG8AgB5OkU)
    * [ICA applied to EEG](https://www.youtube.com/playlist?list=PLXc9qfVbMMN2uDadxZ_OEsHjzcRtlLNxc)
    * [Time-Frequency Analysis of EEG Time Series](https://www.youtube.com/playlist?list=PLXc9qfVbMMN2TAoLHVW5NvNmJtwiHurzw)

* [Resources for ERP research](https://erpinfo.org/resources)
   * Recursos sobre Potenciales Relacionados a Eventos (Universidad de California en Davis).

* [MNE Tutorials for EEG anaysis in Python](https://mne.tools/dev/auto_tutorials/)
   * MNE es la libreria de Python mas usada para analizar datos de Electroencefalogrfia (EEG).

* [MNE in Python by Berdakh Abibullaev](https://youtube.com/playlist?list=PLXtvZiGkmNVvPS0N9UNBVkIFe0_0t_Nqt)
   * Muy interesante lista de reproducción con tutoriales para aprender a usar MNE.  
* [COGS118C [Neural Signal Processing] @ UCSanDiego](https://github.com/rdgao/cogs118c)
   * Procesamiento de señales neuronales usando Python.


# fMRI

* [fMRI Bootcamp dictado por Rebecca Saxe en MIT](https://www.youtube.com/playlist?list=PLyGKBDfnk-iDVpUGSR_GlDmQrZOS0Lk6k)

* [Principles of fMRI by Martin Lindquist and Tor Wager](https://www.youtube.com/channel/UC_BIby85hZmcItMrkAlc8eA)

* [Multivariate pattern analysis by Martin Hebart](https://fmrif.nimh.nih.gov/public/other-courses/mvpa)

* [Andy’s Brain Book](https://andysbrainbook.readthedocs.io/en/latest/index.html)
   * Libro y videos que tienen como objetivo enseñar a analizar datos de fMRI 

# Eyetracking

* [PyGaze: Open-source toolbox for eye tracking in Python](http://www.pygaze.org/)
   * La principal opcion para analizar movimientos oculares en Python

* [Gaze tracking estimation video by learnopencv Youtube Channel](https://youtu.be/-lmc2-podgQ)
   * In this video, we explain the problem of gaze estimation, current methods for collecting ground truth data, public datasets, and current methods for solving the      gaze estimation/tracking problem.
   * [blog post](https://www.learnopencv.com/gaze-tracking/)

* [WebGazer.js](https://webgazer.cs.brown.edu/)
   * WebGazer.js is an eye tracking library that uses common webcams to infer the eye-gaze locations of web visitors on a page in real time. The eye tracking model it contains self-calibrates by watching web visitors interact with the web page and trains a mapping between the features of the eye and positions on the screen. WebGazer.js is written entirely in JavaScript and with only a few lines of code can be integrated in any website that wishes to better understand their visitors and transform their user experience. WebGazer.js runs entirely in the client browser, so no video data needs to be sent to a server, and it requires the user's consent to access their webcam.

* [Eye Tracking Methodology (Clemson University, Fall 2023)](http://andrewd.ces.clemson.edu/courses/cpsc412/fall23/sched.html)
   * Contenido del curso de metodología de seguimiento ocular dictado por Andrew T. Duchowski, uno de los principales especialistas en el tema a nivel mundial 

# Neurociencia computacional

* Todo el material de la escuela de verano neurociencia computacional [**Neuromatch Academy 2020**](https://www.neuromatchacademy.org/syllabus)
    * Incluye videos de las clases, notebooks en Google Colab, etc.
* [Fleur Zeldenrust COMPUTATIONAL NEUROSCIENCE resources](https://fleurzeldenrust.nl/computational-neuroscience-resources/)
    * "Almost no-one coming to computational neuroscience has a degree in computational neuroscience: most have degrees in biology, physics, mathematics or AI. Therefore, I often receive the question what good introductory material is. Here, I compiled a list of some introductory material I like."

* [Repositorio: awesome-neuroscience](https://github.com/analyticalmonk/awesome-neuroscience)
   * Lista curada de bibliotecas de neurociencia, software y cualquier contenido relacionado con el tema.

* [Essentials of Neuroscience with MATLAB by Mike X Cohen](http://sincxpress.com/neuroscience)

* [STATS320: Machine Learning Methods for Neural Data Analysis 2021](https://github.com/slinderman/stats320)
   * Repo de la materia de Stanford University. Algunos de los temas:  Spike sorting algorithm , Kilosort: Spike sorting by Deconvolution, CNMF: Calcium          deconvolution via constrained NMF, DeepLabCut: Markerless pose tracking with CNNs, DeepRetina: Deep encoding models of retinal spike trains, Kalman Smoothers: Decoding movement from neural data, MoSeq: Autoregressive HMMs for animal movements, SLDS: Switching LDS model of neural data

# Neuroanatomia

* [FUNCTIONAL NEUROANATOMY resources from The University of British Columbia](http://www.neuroanatomy.ca/)
   * Excelente material interactivo proporcionado por la Dra. Claudia Krebs.

# Experimentos

* [Canal de Youtube de Psychopy para hacer experimentos con Python](https://www.youtube.com/playlist?list=PLFB5A1BE51964D587)

* [Recursos para aprender y enseñar Psychopy](https://workshops.psychopy.org/teaching/index.html)

* [Canal de Youtube de Josh de Leeuw (creador de jsPsych)](https://www.youtube.com/playlist?list=PLnfo1lBY1P2Mf_o6rV5wiqqn92Mw3UTGh)
   * [jsPsych](https://www.jspsych.org/) es una poderosa librería para hacer experimentos de psicología y neurociencias utilizando el lenguaje javaScript.

* [Moving research online workshop 2020](https://www.youtube.com/playlist?list=PLb_Brg3lLp-2HUVoc0SpFft3lu-rQOgAe)

* [jsPsych tutorials by Winson Yang](https://www.youtube.com/playlist?list=PLtdKTIOUlb42qG962wz30fzlUMibJCGQW)
   * Muy buenos tutoriales para aprender a usar la librería jsPsych.

* [Videos de la conferencia #BeOnline2020 sobre experimentos comportamentales online](https://beonline.research.sc/2020/videos)

# Herramientas

* [Data Science for Biologists. Playlist del curso de la Unversidad de Washington](https://www.youtube.com/playlist?list=PLMrJAkhIeNNQz4BMoGSsN8cbt8pHlokhV)

* Class lectures for Mathematical Tools for Neural and Cognitive Science, a graduate course at NYU. Topics include: Linear algebra, least-squares and total-least-squares regression, eigen-analysis and PCA, linear shift-invariant systems, convolution, Fourier transforms, Nyquist sampling, basics of probability and statistics, hypothesis testing, model comparison, bootstrapping, estimation and decision theory, signal detection theory, linear discriminants, classification, clustering, simple models of neural spike generation, white noise (reverse-correlation) analysis.
    * [Playlist](https://www.youtube.com/playlist?list=PLhOZWeo463baxX56-Qnt3jiG6P76a4gis)
    * [Web de la materia](http://www.cns.nyu.edu/~eero/math-tools/)

* Biometría 2, materia de FCEyN (Universidad de Buenos Aires). Temas:  Modelos (lineales, no lineales, mixtos), Análisis de la varianza, regresiones, métodos de comparación multivariada, diseño de medidas repetidas, entre otros.
    * [Playlist](https://www.youtube.com/playlist?list=PLlZeP0wo7-V-FESy7Jrl-OjzZh4np3aob)
    * [Web de la materia](http://www.ege.fcen.uba.ar/academico/materias-de-grado/materias-del-ciclo-superior-segundo-cuatrimestre/materias-del-area-ecologia/biometria-ii/)

* [Essence of linear algebra (Youtube playlist by 3Blue1Brown)](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)

* [Introduction to statistics (Youtube playlist by Khan Academy)](https://www.youtube.com/playlist?list=PL1328115D3D8A2566)

* [Canal de Youtube de Steve Brunton](https://www.youtube.com/c/Eigensteve/playlists) explica muchos temas de matemática útiles para neurociencias (posee listas de: álgebra lineal, SVD,  Fourier, data science, entre otros).

* [StatQuest: Canal de Youtube de Josh Starmer](https://www.youtube.com/c/joshstarmer)
    * [Statistics fundamentals](https://www.youtube.com/playlist?list=PLblh5JKOoLUK0FLuzwntyYI10UQFUhsY9)
    * [Linear regression and linear models](https://www.youtube.com/playlist?list=PLblh5JKOoLUIzaEkCLIUxQFjPIlapw8nU)
    * [Índice conteniendo todos los videos](https://statquest.org/video-index/)

* [Mathematical Tools for Neuroscience (Neurobio 212 at Harvard)](https://github.com/ebatty/MathToolsforNeuroscience)
   * Curso con temática similar al de Math tools de NYU. Diferencias: Código en Python (cuadenos de Colab) en vez de Matlab y que está pensado específicamente para ser dictado online con una estética tipo Khan Academy.
   * Temas: Álgebra lineal, estadística, ecuaciones diferenciales, sistemas dinámicos y bases de Machine Learning.
   * La idea es lograr incluir temas variados (de matemática) que a una persona trabaje en neurociencia pueda resultarle de utilidad.

* [Introduction to Mathematics and Python using Neuroscience Examples](https://github.com/john-s-butler-dit/Basic-Introduction-to-Python)
   * Se propone como una breve introducción a las herramientas matematicas en Python.
   * Una buena opción previa a Mathematical Tools for Neuroscience (Neurobio 212 at Harvard)   

* [Introduction to Linear Algebra for Applied Machine Learning with Python](https://pabloinsente.github.io/intro-linear-algebra)
   * Muy buen recurso para arrancar con álgebra lineal desde cero. Recomiendo la sección sobre notación matemática que, como dice el autor, suele ser uno de los problemas más grandes para quienes no venimos de ese campo.

* ["Viendo la teoria". Libro interactivo para iniciarse en nociones de probabilidad](https://seeing-theory.brown.edu/es.html#firstPage)
   * Recurso creado por Daniel Kunin mientras era un estudiante de pregrado en la Universidad de Brown. El objetivo de la página es hacer la Estadística más accesible usando visualizaciones interactivas en el navegador.

* [Canal de Youtube de Andres Farall](https://www.youtube.com/channel/UC5Rup8Tq90zOekekkNlSdRQ/playlists)
   * Videos sobre Ciencia de Datos con implementaciones prácticas en R.
   Los videos subidos a este canal comprenden los recursos asincrónicos de los cursos de posgrado que dicta regularmente en la Facultad de Ciencias Exactas y    Naturales de la Universidad de Buenos Aires. Algunos de estos cursos son:
   Enfoque Estadístico del Aprendizaje (Maestría en "Data Mining")
   Introducción al Análisis Multivariado (Carrera de Especialización en Estadística para profesionales en Ciencias de la Salud)
   Ciencia de Datos con R (Materia optativa de grado y posgrado)
   Técnicas Avanzadas de Regresión (Carrera de Especialización en Estadística para profesionales en Ciencias de la Salud)

* [Material de la materia "Laboratorio de Datos" (Universidad de Buenos Aires)](http://materias.df.uba.ar/lda2021c1/171-2/)
   * Excelente contenido en español sobre análisis de datos y Machine Learning con Python: Videos, slides y notebooks
   * Algunos de los temas abarcados: análisis exploratorio de datos numéricos, modelos de regresión, modelos de clasificación, clustering y reducción de la dimensionalidad, obtención de datos, datos no numéricos, introducción al procesamiento del lenguaje natural.

* [NSCI 801: Quantitative Neuroscience by Dr Gunnar BLOHM](https://github.com/BlohmLab/NSCI801-QuantNeuro)
   * Todo el material del curso de Neurociencia cuantitativa utilizando Python y Google Colab
   * Temas: Intro Python, Advanced Python, Data collection / signal processing, Statistics and Hypothesis testing - basics, Statistics and Hypothesis testing - advanced, Quantitative wet lab / bench methods , Statistics and Hypothesis testing - Bayesian, Models in Neuroscience, Data Neuroscience overview , Correlation vs causality, Reproducibility, reliability, validity,

* [Stanford's "Introduction to Statistics"](https://www.coursera.org/learn/stanford-statistics)
   * Curso de coursera introductorio con los siguientes temas: Estadística descriptiva, Muestreo y Experimentos Controlados Aleatorizados, Probabilidad, Distribuciones de Muestreo y Teorema Central del Limite, Regresión, Pruebas Comunes de Significancia, Remuestreo, Comparaciones Múltiples.

* [Computational linear algebra by Rachel Thomas](https://www.fast.ai/2017/07/17/num-lin-alg/)
   * Excelente curso de una de las creadoras de [fast.ai](https://www.fast.ai/), con un enfoque fuertemente práctico.
   * Repo con el contenido del curso: https://github.com/fastai/numerical-linear-algebra

* [Mathematical Tools for Data Science dictado por Carlos Fernandez-Granda (NYU University)](https://cds.nyu.edu/math-tools/)
   * [Repo](https://github.com/cfgranda/math-tools-nyu)

* [Fundamentals for Neuro Data Science](https://neurodatascience.github.io/QLS612-Overview/)
   * Este curso está destinado a investigadores en ciencias de la vida (neurólogos, psiquiatras, psicólogos, neurocientíficos) que desean mejorar sus prácticas de investigación u otros investigadores que desean una introducción a la ciencia de datos con ejemplos en neurociencia y neuroimágenes. El objetivo es brindar herramientas para ser capaz de analizar datos de manera reproducible y colaborativa utilizando Python.
   * Temas: Introducción a la reproducibilidad, terminal y Bash, Introducción a Python, Caja de herramientas de Python para análisis de datos, Git/GitHub, Preprocesamiento de datos en Python, Aprendizaje automático 1: aprendizaje supervisado, Machine Learning 2: selección y validación de modelos, Introducción a la visualización de datos, Contenedores, Computación de alto rendimiento.

# Ciencias Cognitivas

* [Introduction to Cognitive Science for Undergraduates. Lectures delivered in University College Dublin in Spring 2020](https://www.youtube.com/playlist?list=PLTIeLyBa6PfJCSiIiwVhJIjl_lMZZQ-rD)

* [Cognitive Neuroscience (PSY 449), University of Oregon, 2020](https://www.youtube.com/playlist?list=PL7xIGdTUcr0qpua0zaIn2KGwI_IEGS-qy)

* [Fundamentals of Cognitive Neuroscience by Hamed Ekhtiari](https://youtube.com/playlist?list=PLoYAKQ4_GWnDKeZwTjxNE2LkLyXil96mt)
   * 87 videos cubriendo gran cantidad de contenidos de neurociencias cognitivas.

# Machine Learning

* [Playlist del ya clásico curso de Machine Learning de Andrew Ng](https://www.youtube.com/watch?v=PPLop4L2eGk&list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN&ab_channel=ArtificialIntelligence-AllinOne)

* [Stat-451: Intro to Machine Learning (Fall 2020) by Sebastian Raschka](https://www.youtube.com/playlist?list=PLTKMiZHVd_2KyGirGEvKlniaWeLOHhUF3)

* [Repositorio: "A curated list of awesome machine learning frameworks, libraries and software (by language)"](https://github.com/josephmisiti/awesome-machine-learning)

* [Repositorio: Completely free access list of resources to learn machine learning and deep learning](https://github.com/madscientist98/Machine-Learning-Deep-Learning-Resources)

* [Made With ML Topics: An automatically and constantly up-to-date collection of the best ML resources by topic, curated by the community](https://madewithml.com/topics/)
   * Realmente tiene de todo sobre el tema! (Tutoriales separados por: Frameworks, librerías, algoritmos, modelos, técnicas, áreas, etc)

* [Repositorio de la materia Aprendizaje Automático (Universidad Nacional de San Martin)](https://github.com/exord/UNSAM_IA)
    * Valioso recurso en español, donde son más escasos. Contiene videos, slides y código.

* [Machine Learning Practico (2020). Curso en español dictado por Pablo Zivic en el Instituto de Cálculo, FCEyN, UBA](https://elsonidoq.github.io/machine-learning-practico/)

* [Lectures and slides for the UvA Master AI course Machine Learning 1](https://uvaml1.github.io/)
   * El curso sigue el famoso libro de Christopher Bishop: [Pattern Recognition and Machine Learning](https://www.microsoft.com/en-us/research/people/cmbishop/prml-book/)
   * Contiene tanto los PDF con las anotaciones de la clase como los videos del dictado de cada una de ellas.

* [MIT's 6.036 course: Introduction to Machine Learning by Tamara Broderick (2020)](http://people.csail.mit.edu/tbroderick//ml.html)   
   * Contenido del curso: slides + videos en Youtube.

* ["Aprendizaje de Máquinas 2021" (Universidad de Chile)](https://github.com/GAMES-UChile/Curso-Aprendizaje-de-Maquinas)
   * Curso completo con videos, notebooks y ejercicios. Completamente en español.
   * Temas: Introducción: ¿qué es la Inteligencia Artificial y cómo se relaciona con el AM? , Regresión, Clasificación, Selección y evaluación de modelos, Máquinas de soporte vectorial, Aprendizaje no supervisado, Redes neuronales, Process Gaussianos.

* [CS224W: Machine Learning with Graphs | Stanford | Winter 2021](http://web.stanford.edu/class/cs224w/)
   * What is this course about? Complex data can be represented as a graph of relationships between objects. Such networks are a fundamental tool for modeling social, technological, and biologic  al systems. This course focuses on the computational, algorithmic, and modeling challenges specific to the analysis of massive graphs. By means of studying the underlying graph structure and its features, students are introduced to machine learning techniques and data mining tools apt to reveal insights on a variety of networks.
   * Todos los videos de las clases, ejercicios y notebooks.

# Deep Learning

* [Repositorio: "Open Deep Learning and Reinforcement Learning lectures from top Universities like Stanford, MIT and UC Berkeley"](https://github.com/Machine-Learning-Tokyo/AI_Curriculum)

* [The use of Keras with Tensor Flow applied to neural models and data analysis](http://ceciliajarne.web.unq.edu.ar/cns-2020-tutorial/)
   * This tutorial will help participants implement and explore simple neural models using Keras as well as the implementation of neural networks to apply Deep  learning tools for data analysis. It will include an introduction to modeling and hands-on exercises.
   * Curso con videos + notebooks creado por Cecilia Jarne, investigadora del Departamento de Ciencia y Tecnología de la Universidad Nacional de Quilmes


* Designing, Visualizing and Understanding Deep Neural Networks (CS W182 / 282A) (2021 edition)
   * All the lectures for the Sergey Levine's deep 182 learning class. This is an introductory deep learning course (advanced undergraduate + graduate) covering a broad range of deep learning topics.
   * [Website](https://cs182sp21.github.io/)
   * [Playlist](https://m.youtube.com/playlist?list=PL_iWQOsE6TfVmKkQHucjPAoRtIJYt8a5A)

* [Recurrent Neural Network (RNN) for Neuroscience Tutorial Materials by Kanaka Rajan](https://www.rajanlab.com/resources)
   * El mejor recurso que he visto sobre RNNs en neurociencias. Todo el material del curso dictado en el congreso COSYNE 2021
* [Deep Learning for Computer Vision: Fundamentals and Applications Spring 2021 (Weizmann Institute of Science) ](https://dl4cv.github.io/index.html)
   * [Lista de videos en Youtube](https://youtube.com/playlist?list=PLUgbVHjDharjSSHF1EQq6h8FFp4XEX5AF)

* [awesome-neuro-ai-papers](https://github.com/CYHSM/awesome-neuro-ai-papers)
   * Recopilación de papers en la intersección entre la Neurociencia y el Deep Learning.

# Python

* [Aprendiendo Python | Curso de Python 2020 desde cero COMPLETO by Fede Yulita](https://www.youtube.com/playlist?list=PLZMkywH6sgYja6iXYNFTAcItHHvt842gH)
  * El curso es ameno, Fede es un chico de computación en Exactas, UBA.

* [Curso PYTHON DATA SCIENCE 🐍💻 2020 en Español by Rafa Gonzalez Gouveia](https://www.youtube.com/playlist?list=PLbDLkhJ5sFvBJC6XnRSHMltAdKXI7Drw9)
  * Muy buen canal para ciencia de datos con Python (también tiene videos con R!) en español.

* [Canal de YouTube de CCTMéxico](https://www.youtube.com/c/cctmexico/playlists)
  * Excelente canal mexicano con videos de temas relacionados a las ciencias básicas, programación en Python, ciencia de datos entre otros.

* [Python Tutorial - Python for Beginners by Programming with Mosh](https://www.youtube.com/watch?v=_uQrJ0TkZlc&t=7s)
  * Intro amigable.

* [Python for Everybody - Full University Python Course by FreeCodeCamp](https://www.youtube.com/watch?v=8DvywoWv6fI&feature=youtu.be)
  * Amigable pero super extenso y con explicaciones más formales.

* [Python for the practicing neuroscientist: an online educational resource](https://elifesciences.org/labs/f779833b/python-for-the-practicing-neuroscientist-an-online-educational-resource)
  * Herramientas de programación para empezar a analizar datos de neurociencias usando Python.

* [Neuromatch Deep Learning 2021](https://deeplearning.neuromatch.io/tutorials/intro.html)
  * Contenido de la excelente escuela de verano de [Neuromatch](https://neuromatch.io/) sobre Deep Learning.
  * Sirve para aprender Deep Learning en general pero las aplicaciones son principalmente en neurociencias.  

# R

* ["Learn R for free"](https://www.learnr4free.com/)
  * Tiene todo tipo de recursos (libros, videos, sitios web interactivos, artículos) para aprender R. Algunos son para principiantes y comienzan desde el proceso de instalación de R.
  * Tiene versión en español!

* [Iniciación en R para científicos - Miguel Rojas](https://github.com/itsmiguelrojas/taller_r)
  * Intro muy completa a R desde un vistazo a la interfaz de RStudio hasta pruebas de hipótesis, pasando por graficación y estructura de datos. Miguel es estudiante de la licenciatura en biología de la Facultad de Ciencias de la Universidad Central de Venezuela.
