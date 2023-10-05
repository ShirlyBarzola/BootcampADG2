# BootcampADG2
* Perfilamiento de datos: https://shirlybarzola.github.io/BootcampADG2/AutomobileDataProfile
* [Perfilamiento de datos](https://shirlybarzola.github.io/BootcampADG2/AutomobileDataProfile)
* Queries de Python
# Importar libreria requerida
import pandas as pd
#Leer datos desde archivo CSV
csv_path="https://raw.githubusercontent.com/ShirlyBarzolaBrusil/ProyectoColaborativo/main/diabetes_data.csv"
data = pd.read_csv(csv_path, sep=",",error_bad_lines=False)
data.head() 
