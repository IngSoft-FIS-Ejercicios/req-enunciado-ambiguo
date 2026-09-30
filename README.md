# Requerimientos: El Desafío del Enunciado Ambiguo

¡Bienvenidos al práctico de **Especificación de Requerimientos**! Hoy pondremos a prueba los conceptos teóricos vistos en clase transformando un requerimiento mal redactado en especificaciones profesionales de alta calidad.

---

## 🛠️ El Desafío Inicial
Imaginen que forman parte de un equipo de desarrollo y el cliente les entrega el siguiente requerimiento textual para el nuevo sistema de una plataforma de e-learning:

> *"El sistema debe ser súper rápido y permitir que los estudiantes y profesores se registren fácilmente, o actualicen sus datos y reportes en formato .jpg y PDF si quieren, y además y/o mandar correos automáticos si hay espacio en el servidor."*

---

## 📋 Consignas por Fases

### Fase 1: Diagnóstico y Crítica (10 min)
En equipo, analicen el enunciado inicial a la luz de la teoría. 
* **Pregunta clave:** ¿Por qué este requerimiento es un "dolor de cabeza" para el equipo de desarrollo y testing?
* **Tarea:** Listen al menos 4 fallas graves basándose en las características deseables de los requerimientos (ambigüedad, falta de completitud, mezclar diseño, inviabilidad, etc.).

---

### Fase 2: La Metamorfosis Tradicional (10 min)
Con base en los errores detectados, reescriban el requerimiento aplicando las buenas prácticas de escritura formal:
* Usen **voz activa** (El sistema debe...).
* Escriban **requerimientos individuales y atómicos** (eviten juntar dos ideas con "y/o").
* Asegúrense de que sean **verificables** (cambien términos subjetivos por métricas objetivas).

---

### Fase 3: Enfoque Ágil - Historias de Usuario (15 min)
Migren la funcionalidad principal a un entorno ágil:
1. Redacten una **Historia de Usuario** utilizando la estructura estándar:
   * *Como [rol de usuario]...*
   * *Quiero [funcionalidad]...*
   * *Para [beneficio]...*
2. Validen que cumpla con el modelo **INVEST**.
3. Redacten al menos dos **Criterios de Aceptación** utilizando el formato *Dado / Cuando / Entones* y verifiquen que cumplan con los criterios **SMART**.

---

### Fase 4: Modelado con Casos de Uso (15 min)
Seleccionen el flujo de registro o actualización de datos y completen una **Plantilla de Casos de Uso**:
* **Nombre descriptivo y Actores** involucrados.
* **Pre y Post condiciones**.
* **Curso Normal:** Tabla detallada de la interacción paso a paso (*Acción del Actor* vs. *Reacción del Sistema*).
* **Curso Alternativo:** ¿Qué sucede si ocurre un error o una validación falla?

---
*¡Mucho éxito en el desafío! Recuerden que una buena especificación ahorra horas de retrabajo en el desarrollo.*
