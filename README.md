# Nombre del Proyecto

Breve descripción o resumen del proyecto.

## Instalación

### Requisitos

- Python >= 3.6
- R >= 3.6

### Instalación de Python

1. Clona este repositorio:

    ```bash
    git clone https://github.com/yucaloid/AEDHackathon.git
    ```

2. Navega hasta el directorio de tu proyecto:

    ```bash
    cd AEDHackathon
    ```

3. Crea y activa tu entorno virtual de Python (opcional pero recomendado):

    ```bash
    python3 -m venv AEDHackathon
    source AEDHackathon/bin/activate  # Linux/macOS
    AEDHackathon\Scripts\activate  # Windows
    ```

4. Instala las dependencias de Python desde el archivo `requirements.txt`:

    ```bash
    pip install -r requirements.txt
    ```

### Instalación de R

1. Instala R desde [CRAN](https://cran.r-project.org/).

2. Opcionalmente, instala RStudio desde [su sitio web](https://www.rstudio.com/products/rstudio/download/).

3. Ejecuta R o RStudio y ejecuta los siguientes comandos para instalar los paquetes de R necesarios:

    ```R
    install.packages(c("ggplot2"))  
    ```

## Estructura de Carpetas

El proyecto sigue una estructura de carpetas organizada de la siguiente manera:

- **data/**: Contiene conjuntos de datos utilizados en el proyecto.
- **src/**: Contiene el código fuente del proyecto, incluidos los scripts de análisis y visualización.
  - **scripts/**: Contiene scripts de Python y R para análisis y visualización.
  - **tests/**: Contiene pruebas unitarias y de integración.
- **docs/**: Contiene documentación relacionada con el proyecto, como especificaciones y manuales de usuario.
- **results/**: Contiene resultados generados por el proyecto, como gráficos y informes.
- **resources/**: Contiene recursos adicionales utilizados en el proyecto, como imágenes y archivos de configuración.
- **env/**: Contiene el entorno virtual de Python utilizado para gestionar las dependencias del proyecto.

## Uso





## Licencia

