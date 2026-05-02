# FUNO11 — Análisis Financiero y Administración de Riesgos

**Área:** Administración de Riesgos  
**Periodo:** Enero – Abril 2026  
**Herramientas:** Python · Excel · Matplotlib  
**Datos:** BMV · Banxico · GBM

---

## Objetivo

Analizar el comportamiento financiero del instrumento FUNO11 (Fibra Uno)
durante el primer trimestre de 2026, aplicando métricas cuantitativas de
riesgo y rendimiento para evaluar su viabilidad dentro de un portafolio
de inversión.

---

## Hallazgos Clave

| Métrica            | Resultado | Interpretación                          |
|--------------------|-----------|------------------------------------------|
| Volatilidad (σ)    | 1.8%      | Baja — activo defensivo                 |
| Sharpe Ratio       | 0.62      | Rendimiento aceptable ajustado por riesgo|
| VaR (95%)          | -2.9%     | Pérdida máxima diaria esperada           |
| CVaR               | -4.5%     | Pérdida en escenarios extremos           |
| Maximum Drawdown   | -10.5%    | Caída máxima del periodo — moderada      |

> **Conclusión:** FUNO11 es un instrumento adecuado para estrategias
> defensivas. Ofrece mayor rendimiento que CETES con un riesgo controlado
> y comportamiento de reversión a la media.

---

## Visualizaciones

| Gráfica | Vista previa |
|---------|-------------|
| Precio histórico | ![precio](visualizaciones/01_precio_historico.png) |
| Rendimientos semanales | ![rendimientos](visualizaciones/02_rendimientos_semanales.png) |
| Distribución de rendimientos + VaR | ![var](visualizaciones/03_distribucion_rendimientos.png) |
| Simulación Monte Carlo | ![montecarlo](visualizaciones/04_simulacion_monte_carlo.png) |
| Comparación vs CETES | ![cetes](visualizaciones/05_comparacion_cetes.png) |

---

## Metodología Aplicada

1. Obtención de precios históricos (BMV / Yahoo Finance)
2. Cálculo de rendimientos logarítmicos
3. Medición de volatilidad (desviación estándar)
4. Sharpe Ratio vs tasa libre de riesgo (CETES)
5. Value at Risk (VaR) y CVaR al 95%
6. Maximum Drawdown
7. Simulación Monte Carlo (múltiples escenarios)

---

## Contenido del Repositorio

| Carpeta | Descripción |
|---------|-------------|
| `/reporte` | Documento académico completo en PDF |
| `/datos` | Precios históricos de FUNO11 en CSV |
| `/analisis` | Notebook de Python con todos los cálculos |
| `/visualizaciones` | Gráficas exportadas del análisis |

---

## Referencias

- [Fibra Uno — BMV](https://www.bmv.com.mx)
- [Banxico — Tasas CETES](https://www.banxico.org.mx)
- Markowitz, H. (1952). Portfolio Selection.
- Sharpe, W. F. (1966). Mutual Fund Performance.

---

© 2026 Nayelli Romero López · Ingeniería Financiera · UPT  
*Portafolio académico — uso exclusivo como evidencia profesional.*
