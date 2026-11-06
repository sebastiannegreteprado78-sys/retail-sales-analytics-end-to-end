# Retail Sales & Returns Analysis

Análisis de ventas y devoluciones en retail con Python, SQL, Excel y Looker Studio.

## Proyecto

Este proyecto evalúa el rendimiento real de un negocio de retail analizando más de 20.000 transacciones para responder dos preguntas clave:

1. ¿Qué canales de marketing generan ingresos netos reales tras descontar devoluciones?
2. ¿Qué categorías tienen mayor tasa de devolución y qué explica ese comportamiento?

La propuesta combina análisis financiero, limpieza de datos y reporting ejecutivo para convertir información operativa en decisiones de negocio.

---

## Resumen ejecutivo

El negocio registró **701,78K €** en ventas brutas, pero tuvo **208,39K €** en devoluciones, lo que equivale a una tasa de devolución aproximada del **29,7%**.

Tras descontar devoluciones, el ingreso neto real fue de **493,39K €**, mostrando que el volumen bruto no siempre refleja la rentabilidad real del canal.

### Hallazgos clave

- **Instagram fue el canal con mejor rendimiento neto**: **173,45K €** de ingreso neto con una tasa de devolución del **26,8%**.
- **Google y Email quedaron por detrás** en rendimiento neto, aunque sus ventas brutas fueron elevadas.
- **Vestidos y calzado fueron las categorías más problemáticas** por devoluciones relacionadas con ajuste y talla.
- **El principal problema no era solo el volumen de ventas, sino la calidad de la experiencia de compra y la información del producto**.

---

## Stack tecnológico

- **Python + Pandas**: limpieza de datos, normalización de categorías, tratamiento de formato monetario y cálculo de métricas.
- **SQL**: validación y agregación de ventas, devoluciones y KPI financieros.
- **Excel**: construcción de resúmenes operativos y auditoría de resultados.
- **Looker Studio**: dashboard ejecutivo y visualización de KPI por canal.

---

## Flujo de trabajo

1. Carga y consolidación de tablas transaccionales.
2. Limpieza de categorías, montos y fechas.
3. Unificación de pedidos y devoluciones.
4. Cálculo de ventas brutas, importe devuelto, tasa de devolución e ingreso neto real.
5. Exportación de datos limpios para análisis y dashboard.

---

## Impacto de negocio

Este análisis permite tomar decisiones con base cuantitativa:

- **Reorientar inversión por canal** según rendimiento neto real.
- **Reducir devoluciones** enfocando esfuerzos en categorías con mayor riesgo.
- **Mejorar la experiencia de compra** con información más clara sobre tallas y ajuste.
- **Priorizar campañas** con mayor rentabilidad y menor riesgo financiero.

---

## Métricas principales

- Ventas brutas por canal
- Importe devuelto por canal
- Tasa de devolución por canal
- Ingreso neto real
- Rendimiento por categoría de producto
- Identificación de productos con mayor problema de ajuste

---

## Repositorio

- `limpieza_con_python_y_sql.ipynb` — notebook principal con limpieza, análisis y KPI.
- `reporte_ventas_limpio(Resumen Canales) (1).csv` — dataset final de resumen por canal.
- `dashboard_preview.png` — vista previa del dashboard.
- `requirements.txt` — dependencias del proyecto.
- `README.md` — documentación del proyecto.

---

## Cómo reproducirlo

1. Clona el repositorio.
2. Instala las dependencias:

```bash
pip install -r requirements.txt
```

3. Abre el notebook `limpieza_con_python_y_sql.ipynb` en Jupyter o VS Code.
4. Ejecuta las celdas para cargar, limpiar y analizar los datos.

---

## Estado del proyecto

El proyecto está finalizado como una base sólida de análisis de negocio con enfoque comercial y financiero. Su siguiente evolución natural sería automatizar el pipeline y publicar el dashboard en un entorno compartible.

---

## Siguientes pasos

- Mejorar la narrativa del notebook con secciones más ejecutivas.
- Añadir más gráficos por categoría de producto y canal.
- Preparar una versión final para portfolio y presentación profesional.

