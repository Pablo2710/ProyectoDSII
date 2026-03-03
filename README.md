# Proyecto: Blindaje Financiero - Detección Inteligente de Fraude
**Estudiante:** Pablo Martinez  
**Curso:** Data Science II  
**Entrega:** Primera Entrega - Obtención de insights y narrativa

## 1. Abstracto: Motivación y Audiencia
En el ecosistema Fintech actual, la seguridad transaccional es el pilar de la confianza del usuario. Este proyecto surge ante la necesidad de evolucionar de reglas estáticas a modelos de Machine Learning capaces de identificar patrones conductuales complejos. El objetivo es mitigar pérdidas económicas y proteger la integridad de la plataforma.

**Audiencia:** Directores de Riesgo (CRO), Seguridad Informática (InfoSec) y Gerencia de Producto.

## 2. Preguntas e Hipótesis
* **Pregunta Principal:** ¿Qué indicadores de comportamiento diferencian el fraude de una transacción legítima?
* **H1 (Monto):** El monto por sí solo no es el predictor más fuerte, sino su desviación respecto al historial del usuario.
* **H2 (Velocidad):** Las transacciones fraudulentas presentan una frecuencia (velocity_score) superior a la media.
* **H3 (Geografía):** Los puntajes de anomalía geográfica son críticos para detectar accesos no autorizados.
