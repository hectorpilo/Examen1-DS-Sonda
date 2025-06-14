
# Proyecto: Análisis y Limpieza de Datos - Entrega Final

Este repositorio contiene el análisis y la limpieza de un dataset utilizando Python y Pandas, como parte de la entrega evaluada del curso. Se aplicaron buenas prácticas de data science para la exploración, detección y tratamiento de valores faltantes, duplicados, y conversión de tipos de datos.

## 📁 Estructura del Proyecto

- `script_analisis.py`: contiene el código principal del análisis.
- `dataset.csv`: archivo fuente de datos utilizado.
- `README.md`: este documento.
- `Entregable_Final.ipynb`: notebook con el desarrollo y visualización.

## 🔧 Requerimientos

- Python 3.8+
- Pandas
- NumPy
- Matplotlib
- Seaborn

Puedes instalarlos con:

```bash
pip install -r requirements.txt
```

## 🚀 Instrucciones de ejecución

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu_usuario/nombre_del_repo.git
   cd nombre_del_repo
   ```

2. Ejecuta el notebook `Entregable_Final.ipynb` o el script `script_analisis.py`.

## 🏷️ TAG de entrega

Se utilizó el siguiente TAG para esta versión entregada:

```bash
git tag entrega-final
git push origin entrega-final
```

Este TAG marca el commit correspondiente a la versión final enviada para evaluación.  
Asegúrate de revisar la sección de **Tags** en GitHub para confirmar su correcta creación y subida.

---

## 📌 Notas adicionales

- No se encontraron duplicados en el dataset.
- Se convirtieron columnas `object` con pocos valores únicos a tipo `category` para optimización.
- Se imputaron valores faltantes en `TotalCharges` tras conversión a tipo `float`.
- Se incluyeron visualizaciones univariadas y multivariadas para el análisis exploratorio.

---

### Autor

Héctor Acevedo – [@tu_usuario](https://github.com/tu_usuario)
