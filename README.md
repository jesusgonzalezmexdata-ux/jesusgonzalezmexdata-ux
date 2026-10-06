# Jesús R. L. González

### Data Scientist · Analítica de Operaciones y Calidad · Gestión de Proyectos Técnicos

> **Convierto problemas operativos en preguntas medibles, evidencia y decisiones.**

Mi trayectoria combina experiencia industrial en manufactura, calidad y logística en Alemania con formación y práctica en Ciencia de Datos. Trabajo en la intersección entre **proceso físico, datos y decisión**: primero estructuro el problema, después determino si los datos permiten responderlo y solo entonces elijo la metodología.

Mi enfoque prioriza **trazabilidad, validación, incertidumbre, reproducibilidad y límites explícitos**. No considero terminado un análisis porque el modelo “funcione”; debe poder explicarse qué datos lo respaldan, qué supuestos contiene, dónde falla y qué decisión puede —o no puede— soportar.

---

## Cómo trabajo

`problema → datos → calidad → hipótesis → baseline → modelado → validación → interpretación → impacto → entrega → monitoreo`

| Principio | Cómo lo aplico |
|---|---|
| **Problema antes que algoritmo** | Convierto necesidades operativas en preguntas medibles y criterios de éxito. |
| **Baseline antes que complejidad** | Un modelo complejo debe justificar por qué mejora una alternativa más simple. |
| **Validación antes que narrativa** | Respeto tiempo, grupos, lotes y dependencias para evitar leakage y métricas infladas. |
| **Evidencia antes que promesa** | Distingo impacto observado, estimado, simulado e hipotético. |
| **Reproducibilidad antes que demo** | Código versionado, pruebas, CI, documentación y trazabilidad de transformaciones. |
| **Límites explícitos** | Si los datos no permiten sostener una conclusión, lo declaro. |
| **IA como acelerador** | Puedo apoyarme en herramientas de IA, pero la revisión, validación y responsabilidad del resultado permanecen conmigo. |

---

## Proyectos destacados

### [Predictive Quality · MLOps](https://github.com/jesusgonzalezmexdata-ux/predictive-quality-mlops)

Sistema de soporte a decisiones de calidad industrial con **SECOM + NASA C-MAPSS**.

- Validación temporal para evitar fuga de información.
- Umbrales definidos por costo de error, no por una métrica aislada.
- SHAP con límites explícitos de interpretación.
- Monitoreo de drift, API con FastAPI, dashboard en Streamlit y registro de predicciones.
- Docker, GitHub Actions y pruebas automatizadas.
- El posible ahorro en SECOM **no quedó estadísticamente demostrado** y se publica así.

**Qué demuestra:** modelado, validación rigurosa, incertidumbre, ingeniería de entrega y criterio para no inflar resultados.

---

### [Analítica de Scrap y COPQ](https://github.com/jesusgonzalezmexdata-ux/scrap-copq-analytics)

Caso demostrativo de manufactura construido con **datos sintéticos** para analizar scrap y costo de no calidad.

- Limpieza y validación de datos de planta.
- Pareto por piezas y por costo.
- Cartas p y p′ de Laney.
- GLM binomial y validación fuera de muestra.
- Simulación de palancas operativas y sensibilidad económica.
- SQL, Python, Streamlit y pruebas automatizadas.

**Qué demuestra:** conexión entre calidad, estadística, operación y decisión económica sin presentar una simulación como impacto real observado.

---

### [Predix · Demanda e Inventario](https://github.com/jesusgonzalezmexdata-ux/predix)

Sistema de pronóstico y reposición para retail con **datos sintéticos**.

- Modelado de demanda censurada cuando existe stockout.
- Comparación contra baselines simples.
- Pronóstico fuera de muestra.
- Política de inventario y nivel de servicio por producto.
- Simulación de merma, faltantes y capital inmovilizado.
- Dashboard en Streamlit y pruebas automatizadas.

**Qué demuestra:** forecasting orientado a decisiones, no solo a precisión estadística.

---

### Otros trabajos

- [Steel Plates · Quality BI](https://github.com/jesusgonzalezmexdata-ux/steel-plates-quality-bi) — modelo estrella, ETL, DAX/Power Query, métricas de calidad y validación cruzada Python/SQL. La ejecución final en Power BI Desktop y el `.pbix` todavía deben cerrarse antes de presentarlo como evidencia completa de Power BI.

---

## Áreas en las que estoy construyendo profundidad

**Analítica industrial:** scrap, COPQ, variabilidad de proceso, mantenimiento, calidad de proveedor, trazabilidad y predicción de defectos.

**Data Science:** estadística aplicada, machine learning, forecasting, análisis de errores, validación, interpretabilidad e incertidumbre.

**Ingeniería de entrega:** Streamlit, FastAPI, Docker, CI, testing y pipelines reproducibles.

**Gestión de proyectos técnicos:** alcance, dependencias, prioridades, riesgos, criterios de aceptación, gates y seguimiento de entregables. Mi experiencia de liderazgo es principalmente **funcional y de proyecto en equipos temporales y multidisciplinarios**, no dirección jerárquica permanente de personal.

---

## Stack

**Python · SQL · pandas · NumPy · SciPy · statsmodels · scikit-learn · LightGBM · Streamlit · FastAPI · Docker · GitHub Actions · pytest**

---

## Base industrial

Mi experiencia previa en manufactura, calidad y logística me obliga a hacer una pregunta antes de modelar:

> **¿Qué representa realmente cada registro y qué decisión operacional depende de él?**

Esa conexión entre proceso, dato y criterio es el eje de los proyectos que publico aquí.

---

## Contacto

[LinkedIn — Jesús R. L. González](https://www.linkedin.com/in/jesus-r-l-gonzalez)

---

*Este perfil separa deliberadamente evidencia técnica, simulación e impacto empresarial real. Los resultados de proyectos con datos sintéticos o costos supuestos se identifican explícitamente como tales.*