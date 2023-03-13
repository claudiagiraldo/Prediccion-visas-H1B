# Proyecto
## Miembros del grupo
- Claudia Yaneth Giraldo Vergara, C.C. 1001745178, Ingeniería Industrial
- Sebastian Zuluaga Cano, C.C. 1020428207, Ingeniería Industrial

## Datos

Los datos del proyecto vienen de [este dataset de Kaggle](https://www.kaggle.com/datasets/jonamjar/h1b-data-set-2017?select=H-1B_Disclosure_Data_FY17.csv), y se pueden hacer disponibles siguiendo estos pasos:

1. Descargar dataset de Kaggle
2. Descomprimir carpeta .zip
3. Cargar archivo 'H-1B_Disclosure_Data_FY17.csv' en Colab (disclaimer: esto puede tardar un tiempo)

Finalmente se ejecutan los siguientes comandos:

    ! import pandas as pd
    ! import numpy as np
    ! nfilas_previas = 20000 #Para realizar una vista previa del dataset vamos a cargar solamente las primeras 20 mil filas, este dato es modificable
    ! data = pd.read_csv('H-1B_Disclosure_Data_FY17.csv', delimiter=',', nrows = nfilas_previas)




