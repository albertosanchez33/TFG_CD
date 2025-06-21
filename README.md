# TFG_CD
Repositorio de scripts utilizados para realizar el sistema referido a la detección de maleza en cultivos de zanahoria

📄Nvidia_Jetson_Nano.pdf : explica cómo inicializar el Jetson Nano, sus componentes, los paquetes que proporciona, el sistema de software y los diferentes frameworks utilizados. Esta guía también se explica con imágenes para comprender mejor la información.

📁system -> recopila todos los scripts necesarios para ejecutar el modelo. Consiste en un archivo main.py que se ejecuta mediante el archivo .sh.

📁train -> Explica cómo se entrenó el sistema, la cantidad de datos y el método de aprendizaje por transferencia utilizado. También incluye el archivo Trt_model.py, que optimiza el modelo para que sea más ligero y agilice la inferencia. La versión del modelo se encuentra en la sección de lanzamiento del repositorio.
