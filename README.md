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

### Fase 5: Verificación de la especificación con IA (15 min)

**1. Elige un modelo y prepara tu requerimiento**

Puedes usar cualquier LLM (como ChatGPT, Claude o Gemini). Para obtener el mejor resultado, entrégale contexto a la IA antes de pedirle la revisión.

**2. Prompts recomendados para usar con la IA**

**Opción A:** Auditoría completa (Estructura INVEST y SMART)
Copia y pega este prompt en tu chat, reemplazando el texto entre corchetes:

Actúa como un Analista de Calidad de Software (QA) y Product Owner senior. Revisa el siguiente requerimiento utilizando los criterios INVEST (Independiente, Negociable, Valorable, Estimable, Pequeño, Testeable) y la metodología SMART para los objetivos.

Identifica:
* Ambigüedades o vacíos de información.
* Criterios de aceptación faltantes o mal redactados (sugiere formato Gherkin: Dado/Cuando/Entonces).
* Propuesta de reescritura mejorada.

Aquí está el requerimiento:
"[Pega tu requerimiento aquí]"

**Opción B:** Transformación rápida a formato User Story + Gherkin
Si tienes una idea muy básica y quieres que la IA la convierta en un requerimiento profesional:

Convierte la siguiente necesidad de usuario en una Historia de Usuario formal con sus respectivos Criterios de Aceptación en formato Gherkin (Dado/Cuando/Entonces). Asegúrate de incluir casos de éxito y de error.

Necesidad:
"[Describe brevemente lo que quieres lograr]"

**3. ¿Qué debe buscar la IA al revisar tus requerimientos?**
Cuando la IA te devuelva el análisis, verifica que haya evaluado los siguientes puntos clave:

* Ausencia de subjetividad: Evita palabras vagas como "rápido", "fácil", "amigable" o "robusto". La IA debe ayudarte a cuantificarlos (ej. “el tiempo de carga debe ser menor a 2 segundos”).
* Criterios de aceptación claros: ¿Cómo sabrá el equipo de pruebas (QA) que la tarea está lista? Deben cubrir el flujo principal y los escenarios alternativos o de error.
* Independencia: Que el requerimiento no dependa excesivamente de otro para poder ser desarrollado (a menos que sea estrictamente necesario).

---

*¡Mucho éxito en el desafío! Recuerdá que una buena especificación ahorra horas de retrabajo en el desarrollo.*
