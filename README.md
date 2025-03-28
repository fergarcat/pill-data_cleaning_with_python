
# Data Cleaning with Python

## Autores
<table>
  <tr>
    <td align="center">
      <a href="https://github.com/jruizndev">
        <img src="https://avatars.githubusercontent.com/u/198059227?v=4" width="100px;" alt="Fernando García"/>
        <br />
        <sub><b>Fernando García Catalán</b></sub>
      </a>
    </td>
     <td align="center">
      <a href="https://github.com/juancmacias">
        <img src="https://avatars.githubusercontent.com/u/53483587?v=4" width="100px;" alt="Juan Carlos"/>
        <br />
        <sub><b>Juan Carlos Macías</b></sub>
      </a>
    </td>
  </tr>
</table>

## Introducción
La limpieza de datos (Data Cleaning o Data Cleansing) es el proceso de detectar, eliminar, corregir o transformar cualquier anomalía, perturbación o irrelevancia de los datos. Es un paso fundamental antes de cualquier tarea de análisis, visualización o modelado en Machine Learning, ya que mejora la confiabilidad de los resultados y reduce sesgos.

## Importancia de la Limpieza de Datos
- Garantiza resultados precisos y confiables.
- Reduce sesgos y errores en el análisis.
- Evita tendencias falsas y estadísticas inexactas.

## Tipos Comunes de Datos "Sucios"
- **Celdas vacías**: Datos faltantes o sin valor.
- **Datos en formato incorrecto**: Ej. Fechas como texto en lugar de formato fecha.
- **Datos erróneos**: Valores fuera de rango o incorrectos.
- **Datos duplicados**: Registros repetidos.
- **Valores nulos**: Representaciones específicas de la ausencia de datos.
- **Valores atípicos (Outliers)**: Valores que se desvían significativamente de la norma.
- **Incoherencias**: Diferencias en unidades, formatos o estilos.

## Limpieza de Datos con Pandas
### Importación de Datos
- `pd.read_csv()`: Leer archivos CSV y convertirlos en DataFrames.

### Detección y Tratamiento de Valores Nulos
- `isnull()`: Detecta valores nulos.
- `dropna()`: Elimina filas con valores nulos.
- `fillna()`: Rellena valores nulos con un valor predeterminado.
- **Métodos avanzados**: Imputación por media, mediana, moda, KNN o regresión.

### Tratamiento de Datos en Formato Incorrecto
- Conversión con `pd.to_datetime()`.
- Eliminación de filas con formato incorrecto.

### Tratamiento de Datos Erróneos y Duplicados
- Identificación con `.head()`, `.describe()`.
- Reemplazo directo o eliminación de valores incorrectos.
- `duplicated()`: Detectar filas duplicadas.
- `drop_duplicates()`: Eliminar duplicados.

### Detección y Tratamiento de Valores Atípicos
- Inspección visual con histogramas y boxplots.
- Métodos estadísticos como Z-score e IQR.
- Eliminación o transformación de outliers.

### Manejo de Incoherencias
- Normalización con `.strip()`, `.upper()`, `.lower()`, `.astype()`.
- Conversión de unidades y valores categóricos.

## Técnicas Avanzadas y Operaciones con DataFrames
- **Eliminación de columnas irrelevantes**: `drop()`.
- **Cambio de índice**: `set_index()`.
- **Manipulación de strings**: `str.replace()`, `str.split()`, etc.
- **Reemplazo condicional**: `np.where()`.
- **Aplicación de funciones**: `apply()`, `applymap()`.
- **Renombrar columnas**: `rename()`.

## Exploración de Datos y Feature Engineering
- **Exploración de Datos (EDA)**: Comprender la estructura y detectar problemas.
- **Ingeniería de Características**: Crear o modificar características para mejorar modelos.

## Buenas Prácticas y Exportación de Datos
- **Conservar los datos brutos**: Guardar una copia original antes de modificar.
- **Documentar el proceso**: Mantener registro de cambios.
- **Escribir funciones reutilizables**: Encapsular tareas comunes.
- **Utilizar listas de verificación**: Para no omitir pasos.
- **Exportación**: `to_csv()`, `to_excel()`, `to_json()`, `to_sql()`, `to_pickle()`.

---
[📄 Descargar el documento PDF](./Copy-of-Data-Cleaning-with-Python.pdf)


¡Esperamos que esta guía te ayude en tus proyectos de limpieza de datos con Python y Pandas!

