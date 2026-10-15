# Jesús R. L. González

### Data Scientist · Analítica de Operaciones y Calidad · Gestión de Proyectos Técnicos

> **Convierto problemas operativos en preguntas medibles, evidencia y decisiones.**
>
> *I turn operational problems into measurable questions, evidence and decisions.*

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

| Proyecto | Pregunta de negocio | Resultado | Datos | Stack |
|---|---|---|---|---|
| [APS Failure Intelligence](https://github.com/jesusgonzalezmexdata-ux/aps-failure-intelligence) | ¿Qué camiones Scania mando a revisar el sistema de aire? | Coste oficial 11,540 frente a 187,500 sin triaje (**−94 %**), 95.7 % de fallas detectadas; test oficial evaluado una sola vez | Reales, públicos | LightGBM · DuckDB SQL · FastAPI · Docker · Streamlit |
| [Mantenimiento por condición (C-MAPSS)](https://github.com/jesusgonzalezmexdata-ux/predictive-maintenance-survival-cmapss) | ¿Qué motores intervengo ahora y cuánto ahorro frente a reemplazar por edad? | **−40 %** de coste frente a reemplazo por edad; C-index 0.85 (IC95 0.80–0.89) | Simulados (NASA) | Supervivencia (Weibull AFT, Cox) · Streamlit · Docker |
| [Steel Plates · Quality MLOps](https://github.com/jesusgonzalezmexdata-ux/steel-plates-quality-mlops) | ¿Qué defecto tiene cada placa y cuándo conviene la revisión manual? | Modelo congelado con holdout consumido una vez; la revisión manual compensa si la razón de costes está entre 3.1 y 53 (con un revisor perfecto) | Reales, públicos | scikit-learn · dbt · DuckDB · ONNX · Power BI |
| [Predictive Quality · MLOps](https://github.com/jesusgonzalezmexdata-ux/predictive-quality-mlops) | ¿Qué lotes de semiconductores retengo? | Ordena mejor que el azar, pero el ahorro **no es significativo** (IC95 −22k a +20k MXN) y se publica así | Reales, públicos | FastAPI · SHAP · drift · Streamlit |
| [Scrap y COPQ](https://github.com/jesusgonzalezmexdata-ux/scrap-copq-analytics) | ¿Dónde se va el dinero de la no calidad en una planta de autopartes? | Palancas por 1.23 M MXN/año (14.5 % del COPQ) | Sintéticos | SQL · GLM binomial · SPC · Streamlit |
| [Predix](https://github.com/jesusgonzalezmexdata-ux/predix) | ¿Cuánto pedir cada lunes y jueves en una tienda de abarrotes? | **−46 %** en coste de reponer mal y −30 % de inventario | Sintéticos | Binomial negativa censurada · simulación · Streamlit |

**Qué tienen en común:** baseline antes que modelo, validación sin fuga de información, umbrales elegidos por costo de error, incertidumbre visible y límites declarados.

**Otros trabajos:** [Steel Plates · Quality BI](https://github.com/jesusgonzalezmexdata-ux/steel-plates-quality-bi): modelo estrella, DAX/Power Query y reglas de acción ISO 9001. El `.pbix` está pendiente de validar en Power BI Desktop.

---

## Áreas en las que estoy construyendo profundidad

**Analítica industrial:** scrap, COPQ, variabilidad de proceso, mantenimiento, calidad de proveedor, trazabilidad y predicción de defectos.

**Data Science:** estadística aplicada, machine learning, forecasting, análisis de errores, validación, interpretabilidad e incertidumbre.

**Ingeniería de entrega:** Streamlit, FastAPI, Docker, CI, testing y pipelines reproducibles.

**Gestión de proyectos técnicos:** alcance, dependencias, prioridades, riesgos, criterios de aceptación, gates y seguimiento de entregables. Mi experiencia de liderazgo es principalmente **funcional y de proyecto en equipos temporales y multidisciplinarios**, no dirección jerárquica permanente de personal.

---

## Stack

**Python · SQL · DuckDB · dbt · pandas · NumPy · SciPy · statsmodels · scikit-learn · LightGBM · análisis de supervivencia · Power BI (DAX, M) · Streamlit · FastAPI · ONNX · Docker · GitHub Actions · pytest**

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