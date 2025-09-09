# Actividad 1: Introducción DevOps / DevSecOps
**Autor:** Ortega Turpo Junior  
**Fecha:** 09/09/2025  
**Tiempo total invertido:** 3h

**Entorno usado:**
Windows 11, navegador Firefox, DevTools para HTTP/TLS.

## 4.1 DevOps vs. cascada tradicional
![Comparativo](Imagenes/CASCADA_VS_DEVOPS.png)
 
- **DevOps** 
  - Feedback continuo, integración y pruebas cercanas al código en CI/CD.
  - Lanzamientos frecuentes y de bajo tamaño, facilitando reversión rápida y menor impacto.
  - Reducción de riesgo por detección temprana y promoción gradual.  
- **Cascada** 
  - Integración y validación tardías, acumulando defectos y retrabajos.
  - Lotes grandes y largos tiempos de espera entre fases, elevando la incertidumbre.

**Fuente(s):** `FUENTES.md`.

#### 4.2 Ciclo tradicional de dos pasos y silos

- **Grandes lotes**
  - **Acumulación de cambios:** cuando se juntan semanas o meses de trabajo, cada release se transforma en un paquete voluminoso y difícil de manejar.
  - **Handoffs costosos:** los traspasos entre equipos se encarecen porque el código se desalineó del estado real de producción, demandando pruebas extra y resolución de conflictos.
  - **Integración tardía = riesgo creciente:** mientras más se posterga integrar, más sube el costo; los defectos emergen cuando ya existen múltiples dependencias, amplificando el impacto.

- **Colas de defectos**
  - **Acumulación en backlog:** Los errores se apilan como tickets en lugar de corregirse en el mismo flujo donde nacen.
  - **Handoffs costosos:** Desarrollo pierde contexto con el tiempo y operación solo percibe síntomas en producción, dificultando el diagnóstico.
