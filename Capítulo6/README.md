# Control de Gastos Personales

## Objetivo de la práctica:

Al finalizar esta práctica, el participante será capaz de crear y dar formato a una tabla en Excel, aplicar estilos visuales, insertar y eliminar filas, utilizar nombres estructurados para cálculos, así como ordenar y filtrar los datos de manera eficiente.

## Objetivo Visual

![imagen resultado](..\images\cap6_obj.png)

## Duración aproximada:
- 30 minutos.

## Instrucciones

### Tarea 1. **Crear una tabla desde cero**

Paso 1. Abre un nuevo archivo de Excel y crea una hoja llamada `Gastos`.

Paso 2. En la fila 1, escribe los siguientes encabezados:

- Fecha  
- Categoría  
- Descripción  
- Monto  

Paso 3. Llena 5 filas con los siguientes datos:

| Fecha      | Categoría     | Descripción       | Monto |
|------------|----------------|--------------------|--------|
| 01/04/2025 | Alimentación   | Supermercado       | 75     |
| 03/04/2025 | Transporte     | Recarga de gasolina| 40     |
| 05/04/2025 | Entretenimiento| Cine               | 20     |
| 06/04/2025 | Alimentación   | Restaurante        | 50     |
| 07/04/2025 | Servicios      | Electricidad       | 60     |

---

![imagen resultado](..\images\cap6_1.png)

### Tarea 2. **Convertir el rango en tabla**

Paso 4. Selecciona los datos con sus encabezados.

Paso 5. Ve a `Insertar > Tabla`. Asegúrate de que esté marcada la opción `La tabla tiene encabezados`.

![imagen resultado](..\images\cap6_2.png)

Paso 6. Selecciona la tabla, y desde la pestaña `Diseño de tabla`, cambia el nombre de la tabla a `tblGastos` 

![imagen resultado](..\images\cap6_3.png)

---

### Tarea 3. **Aplicar estilo y diseño**

Paso 7. Desde la pestaña `Diseño de tabla`, selecciona un estilo visual que diferencie encabezados y filas alternas.

![imagen resultado](..\images\cap6_4.png)

Paso 8. Activa las siguientes opciones:  
✔ Fila de encabezado  
✔ Fila de totales  
✔ Fila con bandas

![imagen resultado](..\images\cap6_5.png)

---

### Tarea 4. **Insertar una nueva fila y eliminar otra**

Paso 9. En la parte inferior de la tabla, inserta una nueva columna que tenga los siguientes gastos:  

- Fecha: 08/04/2025  
- Categoría: Servicios  
- Descripción: Agua  
- Monto: 35

| Fecha      | Categoría     | Descripción       | Monto |
|------------|----------------|--------------------|--------|
| 08/04/2025  | Servicios   |      Agua       | 35     |

![imagen resultado](..\images\cap6_6.png)

Paso 10. Elimina la fila que contiene el gasto en el cine, en la categroia "Entretenimiento", y vera como se ajusta el total.

![imagen resultado](..\images\cap6_7.png)

---

### Tarea 5. **Ordenar y filtrar los datos**

Paso 11. Selecciona la flecha de filtro, y para ordenar la tabla por fecha, selecciona `Ordenar de más reciente a más antiguos`.

![imagen resultado](..\images\cap6_8.png)

Paso 12. Aplica un filtro para mostrar solo los gastos de la categoría "Alimentación".

![imagen resultado](..\images\cap6_9.png)

---

### Tarea 6. **Utilizar fórmulas con nombres estructurados**

Paso 13. Agrega una nueva columna a la derecha con el encabezado `Monto con IVA`.

Paso 14. En la primera celda de esa columna, escribe esta fórmula usando referencias estructuradas:

```excel
=[@Monto]*1.16
```

Paso 15. Presiona Enter y verifica que se haya aplicado a toda la columna.

![imagen resultado](..\images\cap6_10.png)

---

### Tarea 7. **Guardar el archivo**

Paso 16. Guarda el archivo como `Control_Gastos.xlsx`.

Paso 17. Usa `Guardar como` para crear una copia: `Control_Gastos_v2.xlsx`.

---

### Resultado esperado:

![imagen resultado](..\images\cap6_resultado.png)