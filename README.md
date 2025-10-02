# Resumen de actividad. Visualización y Análisis de Ventas

## 🧩 Actividades Realizadas

Durante esta sesión, construimos y analizamos múltiples visualizaciones clave para el dataset `ventas_techstore`, tanto en **Power BI** como en **Tableau**:

- **Top productos vendidos por cantidad**  
  Aplicamos filtros Top N y ordenamos por volumen.

- **Total de ventas por mesa**  
  Evaluamos el rendimiento por punto de atención.

- **Gráfico de líneas: Ventas por mes**  
  Visualizamos tendencias temporales con campos calculados.

- **Tabla comparativa por vendedor**  
  Incluimos ventas totales y ticket promedio.

- **Total de ventas por categoría**  
  Usamos barras y gráficos circulares con porcentajes.

---

## ⚙️ Uso Técnico de las Herramientas

### 🔹 Power BI

- Uso de medidas DAX como `ProductosVendidos = SUM(cantidad)`
- Aplicación de filtros Top N desde el panel visual
- Interacción directa con los ejes sin modificar la estructura
- Visualizaciones dinámicas con segmentadores y filtros contextuales

### 🔹 Tableau

- Creación de campos calculados para ventas y agrupaciones temporales
- Uso de la tarjeta de marcas para controlar color, etiquetas y ángulos
- Filtros Top N aplicados desde el menú de campo → pestaña Top
- Visualizaciones limpias y altamente personalizables

---

## ⚖️ Comparativa: Power BI vs Tableau

| Aspecto                  | Power BI                              | Tableau                                 |
|--------------------------|----------------------------------------|------------------------------------------|
| Aplicación de filtros    | Directa, desde el panel visual         | Requiere navegación por menú de campo    |
| Creación de medidas      | DAX, con control total                 | Campos calculados, menos expresivos      |
| Interacción con visuales | Inmediata y contextual                 | Más técnica y estructurada               |
| Curva de aprendizaje     | Más rápida para usuarios nuevos        | Requiere mayor familiaridad              |
| Dinamismo                | Segmentadores, filtros cruzados       | Visualmente potente pero menos inmediato |

> 🟢 **Power BI destaca por su fluidez en la interacción**, permitiendo aplicar filtros, ordenar datos y construir visualizaciones sin salir del flujo de trabajo. Su panel de filtros es más accesible y su lógica de medidas es más directa para quienes buscan resultados rápidos y funcionales.

---

## 🧠 Conclusión

Ambas herramientas son potentes y complementarias, pero en esta actividad quedó claro que **Power BI ofrece una experiencia más intuitiva y dinámica**, especialmente para tareas como filtros Top N, visualización de KPIs y exploración de datos categóricos. Tableau brilla en personalización visual y control técnico, pero requiere más pasos para lograr lo mismo.

