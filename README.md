# Dashboard del Dólar Colombiano

Análisis estadístico interactivo del comportamiento del dólar en Colombia desde 1991 hasta 2026, basado en datos oficiales del Banco de la República.

**Dashboard en vivo:** [Abrir aquí](https://lunaalmanza2004-stack.github.io/dashboard-dolar-colombia/)

---

## Resumen del proyecto

Este proyecto aplica conceptos de estadística descriptiva a 35 años de datos del mercado cambiario colombiano, con el objetivo de responder tres preguntas clave:

1. ¿Cómo se ha comportado el dólar en el largo plazo?
2. ¿Qué tan estable o volátil ha sido en lo que va del 2026?
3. ¿Cómo se compara el año actual con los cinco anteriores?

El resultado es un dashboard interactivo construido con Python y Plotly, alojado en GitHub Pages.

---

## Hallazgos principales

- El dólar lleva cuatro años en tendencia bajista desde su máximo histórico de $5,061 COP, alcanzado en noviembre de 2022.
- En lo corrido de 2026, el dólar ha caído un 2.36% frente al cierre de 2025.
- 2026 es el año más estable de los últimos cinco, con una desviación estándar de $59 COP, frente a valores superiores a $200 en años anteriores.
- La media ($3,685) y la mediana ($3,684) prácticamente coinciden, lo que indica ausencia de outliers significativos durante el período analizado.

---

## Tecnologías utilizadas

- **Python 3** — Lenguaje de programación
- **Pandas** — Manipulación y análisis de datos
- **Plotly** — Visualización interactiva
- **Google Colab** — Entorno de desarrollo
- **GitHub Pages** — Hosting del dashboard

---

## Conceptos estadísticos aplicados

- Medidas de tendencia central (media, mediana)
- Medidas de dispersión (desviación estándar, rango)
- Cuartiles (Q1, Q3) e interpretación de boxplots
- Detección de outliers
- Variación porcentual interanual (YTD)
- Distribuciones de frecuencia mediante histogramas
- Análisis comparativo entre períodos

---

## Estructura del dashboard

El dashboard se compone de seis secciones:

1. **Indicadores clave (KPIs):** TRM actual, variación YTD, mediana del año y volatilidad.
2. **Histórico 1991 — 2026:** evolución del dólar a lo largo de 35 años con máximos y mínimos históricos.
3. **Detalle 2026:** comportamiento diario con identificación del pico y piso del año.
4. **Distribución de valores:** histograma con líneas de media y mediana.
5. **Días arriba vs abajo de la mediana:** representación gráfica del concepto matemático de mediana.
6. **Comparación últimos 5 años:** boxplot anual de 2022 a 2026.

---

## Fuente de datos

Los datos provienen del Banco de la República de Colombia, descargados del portal oficial de Datos Abiertos del Gobierno (datos.gov.co).

- **Período analizado:** 02/12/1991 — 22/05/2026
- **Total de registros:** 8,274 observaciones diarias
- **Variable principal:** TRM (Tasa Representativa del Mercado) en pesos colombianos



- LinkedIn: [linkedin.com/in/luna-almanza](https://www.linkedin.com/in/luna-almanza)
- Portafolio: [lunaalmanza2004-stack.github.io/portafolio-luna](https://lunaalmanza2004-stack.github.io/portafolio-luna/)

---

*Última actualización: 22 de mayo de 2026*
