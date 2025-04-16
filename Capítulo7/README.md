# Análisis Visual de Ventas Mensuales

## Objetivo de la práctica:

Al finalizar esta práctica, el participante será capaz de crear gráficos simples a partir de datos, insertar diferentes tipos de gráficos (columnas, líneas, circular), personalizar sus elementos visuales, utilizar las recomendaciones automáticas de Excel, y guardar una plantilla de gráfico para reutilizarla.

## Objetivo Visual

![imagen resultado](..\images\cap7_obj.png)

## Duración aproximada:
- 35 minutos.

## Instrucciones

### Tarea 1. **Crear la tabla de datos**

Paso 1. Abre un nuevo archivo de Excel y nombra la hoja como `Ventas`.

Paso 2. En la fila 1, escribe los siguientes encabezados:

- Producto  
- Categoría  
- Enero  
- Febrero  
- Marzo  

Paso 3. Llena las filas con los siguientes datos:

| Producto     | Categoría     | Enero | Febrero | Marzo |
|--------------|----------------|--------|----------|--------|
| Lápiz        | Papelería      | 120    | 135      | 150    |
| Cuaderno     | Papelería      | 90     | 100      | 110    |
| Taza         | Hogar          | 60     | 80       | 70     |
| Mochila      | Escolar        | 75     | 90       | 85     |
| Bolígrafo    | Papelería      | 130    | 125      | 140    |

![imagen resultado](..\images\cap7_1.png)

Paso 4. Selecciona la tabla y conviértela en tabla con `Insertar > Tabla`, marcando la opción `La tabla tiene encabezados`.

![imagen resultado](..\images\cap7_2.png)

---

### Tarea 2. **Insertar un gráfico de columnas**

Paso 5. Selecciona los datos de productos y sus ventas por mes (sin incluir la columna de categoría).

![imagen resultado](..\images\cap7_3.png)

Paso 6. Con las columnas seleccionadas, ve a `Insertar > Gráficos recomendados`, y selecciona uno de tipo **Columna agrupadas**.

![imagen resultado](..\images\cap7_4.png)

Paso 7. Coloca el gráfico debajo de la tabla.

![imagen resultado](..\images\cap7_5.png)

---

### Tarea 3. **Insertar gráfico circular para proporción por categoría**

Paso 8. Crea una nueva columna llamada `Total` con fórmula `=SUMA([@Enero]:[@Marzo])`, y selecciona las columnas `Categoría` y este nuevo total de ventas por producto.

![imagen resultado](..\images\cap7_6.png)

Paso 9. Usa `Insertar > Circular > Circular 2D`.

![imagen resultado](..\images\cap7_7.png)

Paso 10. Personaliza el gráfico:
- Da doble clic en el titulo que aparece y reemplazalo por `Distribución por categoría`
- Da clic en el simbolo `+` y selecciona `Etiquetas de datos`, y luego `Llamada de datos` para mostrar porcentaje en las etiquetas

![imagen resultado](..\images\cap7_8.png)

---

### Tarea 4. **Insertar gráfico de líneas para evolución mensual**

Paso 11. Selecciona las columnas `Producto`, `Enero`, `Febrero` y `Marzo`.

Paso 12. Inserta un **gráfico de líneas** desde `Insertar > Línea > Línea con marcadores`.

![imagen resultado](..\images\cap7_9.png)

Paso 13. Cambia el título del gráfico a: `Tendencia mensual de ventas`.

![imagen resultado](..\images\cap7_10.png)

### Tarea 5. **Guardar un gráfico como plantilla**

Paso 14. Haz clic derecho sobre el gráfico de lineas.

Paso 15. Selecciona `Guardar como plantilla`.

![imagen resultado](..\images\cap7_11.png)

Paso 16. Asigna el nombre: `plantilla_columna_ventas`.

![imagen resultado](..\images\cap7_12.png)

---

### Tarea 6. **Guardar el archivo**

Paso 17. Guarda el archivo como `Ventas_Graficos.xlsx`.

Paso 18. Usa `Guardar como` para crear una copia: `Ventas_Graficos_v2.xlsx`.

---

### Resultado esperado:

![imagen resultado](..\images\cap7_resultado.png)
![imagen resultado](..\images\cap7_resultado_2.png)

