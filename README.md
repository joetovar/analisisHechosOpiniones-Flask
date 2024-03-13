# analisisHechosOpiniones-Flask
Proyecto de trabajo curricular sobre Análisis de hechos y opiniones en redes sociales digitales utilizando técnicas de aprendizaje automático 
Instrucciones para configurar y ejecutar el proyecto MIC


1. Instalación de Python:
   - Descargue e instale Python desde [https://www.python.org/downloads/](https://www.python.org/downloads/).
   - Durante la instalación, marcar la opción "Add Python to PATH".
2. Instalación de pip:
   - `pip` es el gestor de paquetes de Python y generalmente se instala automáticamente con Python.
   - Para verificar si `pip` está instalado, abra una terminal o CMD y ejecute `pip --version`.
   - Si `pip` no está instalado, siga las instrucciones en [https://pip.pypa.io/en/stable/installation/](https://pip.pypa.io/en/stable/installation/).
3. Instalación de Flask y otras librerías:
   - Abra una terminal o CMD y navegue a la carpeta donde se encuentra su proyecto.
   - Ejecute el siguiente comando para instalar Flask y otras librerías necesarias:
     
     `pip install Flask torch transformers pandas scikit-learn selenium matplotlib`
     
4. Configuración del entorno de desarrollo:
   - Se recomienda utilizar un entorno virtual para manejar las dependencias de su proyecto. Para crear un entorno virtual, ejecute:
     `python -m venv venv`
   - Active el entorno virtual:
     - En Windows: `venv\Scripts\activate`
   - Instale las dependencias dentro del entorno virtual:
     `pip install Flask torch transformers pandas scikit-learn selenium matplotlib`
5. Ajuste de direcciones en el código:
   - En los archivos `app.py`, `principal.py`, `train.py`, `precision.py`, `predict.py` ajustar las direcciones de acuerdo a su computador
   - Reemplazar las direcciones de correo electrónico y contraseñas en el archivo `principal.py` con sus credenciales de Facebook.
6. Ejecución del proyecto:
   - Navegue a la carpeta `Flask` .
   - Ejecute el archivo `app.py` con el siguiente comando:
     `python app.py`
   - Abra un navegador y acceda a [http://localhost:5000](http://localhost:5000) para ver la aplicación en funcionamiento.
7. (Opcional) Instalación del navegador y driver para Selenium:
   - Si su proyecto utiliza Selenium para la extracción de publicaciones de Facebook, necesitará instalar un navegador compatible (por ejemplo, Chrome) y su respectivo driver.
   - Descargue el ChromeDriver correspondiente a la versión de su navegador desde [https://sites.google.com/a/chromium.org/chromedriver/downloads](https://sites.google.com/a/chromium.org/chromedriver/downloads).
   - Descomprima el archivo descargado y coloque el ejecutable `chromedriver` en una carpeta accesible desde el PATH del sistema o especifique la ruta directamente en su código.
