Entrega 1: Descripción y Formulación del Objetivo

Alumno: Dario Emmanuel  Verdun  

Título del Proyecto: Detección de Fallas por Desbalance en Motores Eléctricos.

Descripción del Proyecto:  
En este proyecto alineado con mis intereses y mi experiencia laboral actual. Dado mi trabajo en el campo del análisis predictivo de vibraciones, he decidido abordar un problema que considero relevante y que tiene el potencial de tener un impacto significativo en 
la industria: la detección de fallas por desbalance en motores eléctricos mediante el análisis de vibraciones.

Motivación:  
Mi interés en este proyecto surge de la necesidad de mejorar los métodos de detección de fallas en maquinaria, particularmente en motores eléctricos, que son componentes críticos en una amplia gama de industrias. La capacidad de predecir y detectar problemas de desbalance en estos motores de manera temprana puede ayudar a evitar costosas interrupciones no planificadas y optimizar el mantenimiento preventivo, lo que puede resultar en ahorros significativos de tiempo y recursos para las empresas.

Objetivo del Proyecto:  
El objetivo principal de este proyecto es desarrollar un modelo de aprendizaje automático que pueda predecir eficientemente problemas de desbalance en motores eléctricos a partir del análisis de datos de vibraciones. Este modelo deberá ser capaz de identificar patrones característicos en las señales de vibración que indiquen la presencia de desbalance en el motor, permitiendo así una detección temprana y precisa de posibles fallas.

Preguntas de Investigación:
¿Es posible desarrollar un modelo de aprendizaje automático que pueda detectar eficazmente problemas de desbalance en motores eléctricos a partir de datos de vibraciones?
¿Qué características o patrones en las señales de vibración son más indicativos de la presencia de desbalance en un motor?
¿Cuál es el rendimiento del modelo en términos de precisión, recall y F1-score?
¿Cuál es el impacto potencial de implementar este modelo en términos de reducción de costos y optimización de la eficiencia operativa?

Contexto del Problema: 
Los motores eléctricos son componentes críticos en una amplia gama de aplicaciones industriales, desde la fabricación hasta la generación de energía. El desbalance en estos motores puede causar vibraciones excesivas, lo que puede provocar daños en los rodamientos, acortar la vida útil del motor y aumentar el riesgo de fallas catastróficas. Por lo tanto, la detección temprana de problemas de desbalance es fundamental para garantizar la fiabilidad y la eficiencia de los equipos industriales.

Conclusión:
Este proyecto representa una oportunidad emocionante para aplicar técnicas avanzadas de aprendizaje automático en un área de gran importancia en la industria. La detección eficaz de fallas por desbalance en motores eléctricos puede tener un impacto significativo en la productividad y la rentabilidad de las empresas. Además, mi mayor motivación radica en el potencial de continuar con el desarrollo de este proyecto, abarcando otros tipos de fallas como desalineación, fallas de rodamientos, entre otras. Esto permitiría ampliar el alcance del modelo y brindar soluciones integrales para la detección y prevención de problemas en maquinaria industrial, contribuyendo así a la mejora continua de la eficiencia operativa y la reducción de costos en diversos sectores industriales.

├── LICENSE            <- Open-source license if one is chosen
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default mkdocs project; see mkdocs.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for {{ cookiecutter.module_name }}
│                         and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.cfg          <- Configuration file for flake8
│
└── {{ cookiecutter.module_name }}                <- Source code for use in this project.
    │
    ├── __init__.py    <- Makes {{ cookiecutter.module_name }} a Python module
    │
    ├── data           <- Scripts to download or generate data
    │   └── make_dataset.py
    │
    ├── features       <- Scripts to turn raw data into features for modeling
    │   └── build_features.py
    │
    ├── models         <- Scripts to train models and then use trained models to make
    │   │                 predictions
    │   ├── predict_model.py
    │   └── train_model.py
    │
    └── visualization  <- Scripts to create exploratory and results oriented visualizations
        └── visualize.py
