# Requerimientos: El Desafío del Enunciado Ambiguo

¡Bienvenidos al práctico de **Especificación de Requerimientos**! Hoy pondremos a prueba los conceptos teóricos vistos en clase transformando un requerimiento mal redactado en especificaciones profesionales de alta calidad.

---

## 🛠️ El Desafío Inicial
Imaginen que forman parte de un equipo de desarrollo y el cliente les entrega el siguiente requerimiento textual para el nuevo sistema de una plataforma de e-learning:

> *"El sistema debe ser súper rápido y permitir que los estudiantes y profesores se registren fácilmente, o actualicen sus datos y reportes en formato .jpg y PDF si quieren, y además y/o mandar correos automáticos si hay espacio en el servidor."*

---

## 📋 Consignas por Fases

### Fase 1: Diagnóstico y Crítica (10 min)
Analizá el enunciado inicial a la luz de la teoría. 
* **Pregunta clave:** ¿Por qué este requerimiento es un "dolor de cabeza" para el equipo de desarrollo y testing?
* **Tarea:** Listá al menos 4 fallas graves basándose en las características deseables de los requerimientos (ambigüedad, falta de completitud, mezclar diseño, inviabilidad, etc.).

---

### Fase 2: La Metamorfosis Tradicional (10 min)
Con base en los errores detectados, reescribí el requerimiento aplicando las buenas prácticas de escritura formal:
* Usá **voz activa** (El sistema debe...).
* Escribí **requerimientos individuales y atómicos** (evitá juntar dos ideas con "y/o").
* Asegurate de que sean **verificables** (cambiá términos subjetivos por métricas objetivas).

---

### Fase 3: Enfoque Ágil - Historias de Usuario (15 min)
Pasá de la funcionalidad principal a un entorno ágil:
1. Redactá una **Historia de Usuario** utilizando la estructura estándar:
   * *Como [rol de usuario]...*
   * *Quiero [funcionalidad]...*
   * *Para [beneficio]...*
2. Validá que cumpla con el modelo **INVEST**.
3. Redactá al menos dos **Criterios de Aceptación** utilizando el formato *Dado / Cuando / Entones* y verificá que cumplan con los criterios **SMART**.

---

### Fase 4: Modelado con Casos de Uso (15 min)
Seleccioná el flujo de registro o actualización de datos y completá una **Plantilla de Casos de Uso**:
* **Nombre descriptivo y Actores** involucrados.
* **Pre y Post condiciones**.
* **Curso Normal:** Tabla detallada de la interacción paso a paso (*Acción del Actor* vs. *Reacción del Sistema*).
* **Curso Alternativo:** ¿Qué sucede si ocurre un error o una validación falla?

---
*¡Mucho éxito en el desafío! Recuerdá que una buena especificación ahorra horas de retrabajo en el desarrollo.*
