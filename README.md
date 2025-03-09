# Proyecto de Análisis

Este es un proyecto de análisis de datos que utiliza un conjunto de datos muy grande. El archivo de datos se encuentra en **Google Drive** y se puede descargar desde el siguiente enlace:

https://drive.google.com/file/d/1QCY7WYwSzFQyhM0oY4_xP7C6ict4Oj17/view?usp=sharing

## Carga de Datos en Python

Para cargar los datos en tu script de Python, puedes usar el siguiente código:

```python
import pandas as pd

# Cargar el archivo CSV desde el enlace de Google Drive (asegúrate de cambiar el enlace)
url = 'https://drive.google.com/uc?id=1aBcD3fG4HiJklmnOpQ'
df = pd.read_csv(url, usecols=['Indice Masa Corporal = Peso/talla Al Cuadrado', '24_Talla', '23_Peso',
       '25_TenArtSis', '26_TenArtDitlica', '36_RcbeIECA_SI', '37_RcbeARA2_SI',
       'EDAD (Años cumplidos)', '8_Sexo_F', '18_DxHTA_SI', '20_DxDM_SI',
       '22_EtiologiaERC_HTA', '22_EtiologiaERC_DM', '22_EtiologiaERC_HTA-DM',
       'CLASIFICACION FINAL DEL RIESGO_ALTO','CLASIFICACION FINAL DEL RIESGO_BAJO',
       'CLASIFICACION FINAL DEL RIESGO_MODERADO','CLASIFICACION FINAL DEL RIESGO_MUY ALTO'])
