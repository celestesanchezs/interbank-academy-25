## **Introducción:** 
El siguiente proyecto esta realizado en Python el cual procesa un archivo CSV con transacciones bancarias y genera un reporte con:

- **Balance Final:**  
  Suma de los montos de las transacciones de tipo "Crédito" menos la suma de los montos de las transacciones de tipo "Débito".

- **Transacción de Mayor Monto:**  
  Identificar el ID y el monto de la transacción con el valor más alto.

- **Conteo de Transacciones:**  
  Número total de transacciones para cada tipo ("Crédito" y "Débito").
---

## **Instrucciones de Ejecución:** 

1.  **Requisitos Previos:**
    Asegúrate de tener Python instalado en tu sistema. 
    
    Si no tienes Python instalado, puedes descargarlo desde el sitio web oficial de Python: [https://www.python.org/downloads/](https://www.python.org/downloads/)

2. **Clonar el Repositorio (Opcional):**
    https://github.com/celestesanchezs/Reto-T-cnico-Cobol


3.  **Ejecución de la Aplicación:**
    * Asegúrate de que el archivo `data.csv` esté en el mismo directorio que el script `main.py`.
    * Ejecuta el script Python.
    * El reporte de transacciones se mostrará en la terminal.


## **Enfoque y Solución:** 

- La solución se divide en tres funciones principales:
    * leer_csv(): Lee el archivo CSV y convierte los datos en una lista de transacciones.

    * calcular_reporte(): Procesa las transacciones para calcular el balance final, la transacción de mayor monto y el conteo de créditos y débitos.

    * mostrar_reporte(): Muestra en la terminal un resumen claro y formateado de los resultados.

- Decisiones de diseño:

    * Se usa csv.DictReader para leer los datos de forma más estructurada.

    * Se implementa el manejo de errores (try-except) para evitar fallos si el archivo no existe o está corrupto.

    * Se sigue un enfoque modular para facilitar el mantenimiento y la escalabilidad del código.

## **Estructura del Proyecto:** 
interbank-academy-25  # Carpeta principal
- main.py  # Código principal del proyecto
- datos.csv  # Archivo de ejemplo con transacciones
- README.md  # Documentación del proyecto