# Test-A-B-en-tienda-online
## Descripción del Proyecto

Este proyecto corresponde al Sprint 10 del curso “La toma de decisiones de negocios basadas en datos” en TripleTen.
El objetivo fue priorizar hipótesis para aumentar ingresos, ejecutar un test A/B y analizar los resultados para tomar decisiones fundamentadas sobre las estrategias de marketing de una tienda online.

## 💻 Funcionalidades

Parte 1 – Priorización de hipótesis:

Evaluación de 9 hipótesis usando los frameworks ICE (Impact, Confidence, Effort) y RICE (Reach, Impact, Confidence, Effort).

Comparación de resultados de ICE vs. RICE y explicación de los cambios en la priorización.

Parte 2 – Análisis de test A/B:

Limpieza y preprocesamiento de datos (visitas y pedidos).

Representación gráfica de:

Ingreso acumulado por grupo.

Tamaño promedio de pedido acumulado por grupo.

Diferencia relativa en tamaño promedio de pedido entre grupo B y grupo A.

Tasa de conversión diaria por grupo.

Distribución de pedidos por usuario y precios de pedidos (gráficos de dispersión).

Cálculo de percentiles 95 y 99 para detectar anomalías.

Evaluación de la significancia estadística de las diferencias entre grupos (con y sin filtrado de outliers).

Toma de decisiones basada en los resultados: determinar si continuar la prueba, detenerla o elegir un grupo como líder.

## 🔧 Herramientas

- Python
- Pandas
- NumPy
- Matplotlib
- seaborn
- scipy
- Estadística y análisis de datos para A/B testing

## Resultados

Priorización clara de hipótesis según frameworks ICE y RICE, con cambios significativos al incorporar el alcance (Reach) en RICE.

Visualización de ingresos y tamaños de pedidos permitió identificar patrones de comportamiento por grupo.

Tasa de conversión y tamaño promedio de pedido mostraron diferencias entre grupos, con identificación de posibles anomalías.

Cálculo de significancia estadística ayudó a fundamentar la decisión final sobre el test A/B.

## Conclusiones

El valor p de 0.960 indica que no hay evidencia estadísticamente significativa para rechazar la hipótesis nula, que asume que las distribuciones de los tamaños de pedido (ingresos) en ambos grupos son iguales.

Aunque el grupo B muestra un ingreso promedio 23.5% mayor que el grupo A, esta diferencia no es estadísticamente significativa, como lo confirma el valor p elevado.

Recomendación: detener la prueba, ya que no hay diferencia real entre los grupos. Continuar la prueba no tiene sentido porque la probabilidad de que el grupo B sea mejor que el grupo A es casi inexistente.

Esta conclusión refuerza la importancia de basar decisiones en evidencia estadística, no solo en diferencias aparentes en métricas promedio.
