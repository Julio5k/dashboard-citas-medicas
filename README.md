# Dashboard de Gestión de Citas Médicas

Proyecto del Laboratorio 13 de Business Intelligence and Big Data. El dashboard se construyó con Streamlit, pandas y Plotly a partir de 5 000 citas médicas simuladas para un hospital de Lima Norte.

## Visualizaciones

- Citas por especialidad.
- Distribución por estado de la cita (atendida, cancelada o no asistió).
- Cantidad de citas por número de mes del calendario.

## Archivos

| Archivo | Contenido |
| --- | --- |
| `app.py` | Código del dashboard de Streamlit. |
| `citas_medicas.csv` | Datos simulados del laboratorio. |
| `requirements.txt` | Dependencias de Python. |
| `README.md` | Descripción e instrucciones de ejecución. |

## Ejecutar en tu computadora

Abre una terminal en la carpeta donde están los archivos y ejecuta:

```bash
python -m pip install -r requirements.txt
python -m streamlit run app.py
```

## Publicar en Streamlit Community Cloud

Selecciona el repositorio `Julio5k/dashboard-citas-medicas`, la rama `main` y el archivo principal `app.py`. Los cuatro archivos deben estar en la raíz del repositorio.
