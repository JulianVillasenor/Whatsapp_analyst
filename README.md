# WhatsApp Analyst

Proyecto de análisis de datos de un grupo de WhatsApp utilizando Python y Jupyter Notebook.

El proyecto transforma un chat exportado de WhatsApp a un conjunto de datos estructurado y analiza distintos patrones de comunicación, entre ellos:

- Actividad de los participantes.
- Promedio y cantidad de palabras por usuario.
- Uso de emojis y stickers.
- Actividad por día de la semana y hora.
- Palabras más utilizadas.
- Palabras más frecuentes eliminando *stop words*.
- Adjetivos más utilizados.

Los participantes son anonimizados para evitar exponer sus números telefónicos.

## Requisitos

- Python 3.12 o superior
- Git
- Jupyter Notebook o Visual Studio Code con la extensión de Jupyter

## Instalación

Clonar el repositorio:

```bash
git clone https://github.com/JulianVillasenor/Whatsapp_analyst.git
cd Whatsapp_analyst
```

Crear un entorno virtual:

```bash
python -m venv .venv
```

En Windows PowerShell, activar el entorno:

```powershell
.\.venv\Scripts\Activate.ps1
```

Instalar las dependencias:

```bash
pip install -r requirements.txt
```

## Ejecución

Abrir la libreta:

```text
whatsapp_analyst.ipynb
```

Seleccionar como kernel el intérprete de Python ubicado en `.venv` y ejecutar las celdas en orden.

## Datos

El archivo original exportado de WhatsApp no se incluye en el repositorio para proteger la privacidad de los participantes.

La libreta incluida en el repositorio se encuentra ejecutada para permitir la revisión de los resultados sin necesidad de acceder a los datos originales.

## Tecnologías utilizadas

- Python
- Pandas
- Matplotlib
- Seaborn
- NLTK
- spaCy
- emoji
- Jupyter Notebook