# Programa-Python
Code Entorno de Evaluación - Fase 5 - Evaluación Final POA
### El programa simula una herramienta automatizada para auditar el inventario de un almacén y decidir qué artículos necesitan ser reabastecidos.
La información se maneja a través de una matriz con la siguiente estructura:
`[Código Artículo, Nombre, Stock Actual, Stock Mínimo Requerido]`

### Lógica de Negocio Aplicada:
*   **Si el Stock Actual < Stock Mínimo:** Se calcula la cantidad exacta a pedir como la diferencia ($Mínimo - Actual$).
*   **Si el Stock Actual ≥ Stock Mínimo:** La cantidad a pedir es cero ($0$).


### Reporte de salida
    La función generar_reporte_pedidos se encarga de "leer" toda la matriz, procesar artículo por artículo con el "cerebro" que explicamos arriba, y diseñar una tabla limpia en la pantalla.

Al final, el programa imprime un reporte fácil de leer para el administrador, mostrando únicamente el Nombre del Artículo y la Cantidad Exacta que se debe solicitar al proveedor. Por ejemplo:

Para los Monitores 24' (hay 12, pero el mínimo es 15), el código calcula que debes pedir 3.

Para los Teclados Mecánicos (hay 45 y el mínimo es 30), el código detecta que estás bien y te muestra 0.

o de acuerdo a lo que especifiquemos en el codigo


## Características del Desarrollo
*   **Matriz de Datos:** Implementación de una matriz con 5 artículos tecnológicos de prueba.
*   **Modularidad:** Uso de funciones (módulos) específicas para separar la lógica del cálculo de la generación del reporte.
*   **Lenguaje:** Python .
