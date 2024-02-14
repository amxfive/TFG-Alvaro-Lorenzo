# TFG-Alvaro-Lorenzo
## Desarrollo de Fármacos con técnicas de Deep Learning Generativo
En este repositorio se encuentra el código desarrollado para el Trabajo de Fin de Grado del alumno Álvaro Lorenzo Hidalgo, estudiante de Ingeniería de la Salud. A continuación, se detalla el contenido del repositorio
- **Experimentation code:** El código desarrollado para trabajar con un modelo generativo denominado MolGAN y el análisis de moléculas.
  - AnalisisMuestrasGeneradas.ipynb --> Cuadernillo jupyter notebook que analiza las distribuciones en base las propiedades de las moléculas generadas mediante gráficas de distribución
  - ExperimentacionHiperparametros.ipynb --> Cuadernillo jupyter notebook que experimenta con diferentes entrenamientos de MolGAN en base al dataset usado y a determinados hiperparámetros.
  - GeneracionMoleculasCOnHIVDataset.ipynb --> Cuadernillo jupyter notebook que explica el flujo de programación que ha de seguirse en DeepChem para implementar MolGAN y poder generar moléculas
- **ExperimentationData:** Las diferentes moléculas que se han generado durante la experimentación con la MolGAN. Estan nombrados con un patrón de nomenclatura específico de la siguiente forma "dataset_atomos_epocas_pasosgendis.csv". La estructuración de las columnas del CSV es la siguiente:
  - Moléculas en formato SMILES
  - Peso Molecular
  - Valor de LogP
  - Valor de QED
  - Cumple con la regla de Lipinski?
- **Images:** Imagenes en formato .jpg de las gráficas generadas durante el análisis de las muestras generadas
- **TutorialesDC:** Diferentes tutoriales realizados para aprender el manejo de la librería
- **Tabla EstadoDelArte Modelos para el descubrimiento de fármacos:** Tabla excel que contiene todo el estudio del estado del arte realizado en el TFG. Hay 3 tablas:
  - Tabla de modelos generativos en papers cientificos
  - Tabla de bases de datos centrada en fármacos
  - Tabla de librerias en Python centradas en fármacos y química.
- **Memoria:** Memoria del TFG donde se recopila toda la información realizada durante el proyecto
