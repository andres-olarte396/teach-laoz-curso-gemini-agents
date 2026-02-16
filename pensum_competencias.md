# PENSUM DE COMPETENCIAS: Automatización con Agentes en Google Gemini

## PERFIL DE EGRESO

Al finalizar este curso, el estudiante será capaz de:

1. **Diseñar arquitecturas de agentes** que resuelvan problemas complejos de automatización utilizando Google Gemini como motor de razonamiento.

2. **Implementar sistemas multi-agente** con capacidades de colaboración, orquestación jerárquica y comunicación estructurada.

3. **Integrar agentes con fuentes de conocimiento externas** mediante RAG, Function Calling y herramientas personalizadas.

4. **Construir memoria persistente** que permita a los agentes mantener contexto a largo plazo y aprender de experiencias previas.

5. **Desplegar agentes en ambientes productivos** con garantías de seguridad, escalabilidad y observabilidad.

6. **Evaluar y optimizar** el rendimiento de sistemas basados en agentes mediante métricas cuantitativas y testing riguroso.

---

## MATRIZ DE COMPETENCIAS POR MÓDULO

| Módulo        | Competencia Específica (Saber Hacer)                                                                                          | Resultado de Aprendizaje (Evidencia)                                                                              |
| :------------ | :---------------------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------- |
| **Módulo 0**  | Configurar entorno de desarrollo para Gemini y ejecutar llamadas básicas a la API.                                            | Proyecto GCP configurado con primera llamada exitosa a Gemini documentada.                                        |
| **Módulo 1**  | Dominar todas las capacidades de la API de Gemini incluyendo generación de texto, multimodalidad y gestión de conversaciones. | Notebook con ejemplos de generación con diferentes parámetros, análisis de imágenes y conversaciones multi-turno. |
| **Módulo 2**  | Diseñar prompts avanzados utilizando técnicas de Chain of Thought, Tree of Thoughts y prompting para agentes.                 | Biblioteca de prompts reutilizables con documentación de casos de uso y métricas de efectividad.                  |
| **Módulo 3**  | Implementar Function Calling para conectar agentes con APIs externas y herramientas personalizadas.                           | Set de herramientas funcionales (búsqueda web, base de datos, ejecución de código) integradas con Gemini.         |
| **Módulo 4**  | Construir agentes con ciclo completo de percepción-razonamiento-acción y capacidades de planificación.                        | Tres agentes funcionales: investigación web, análisis de datos y automatización de tareas.                        |
| **Módulo 5**  | Implementar sistemas de memoria (corto plazo, episódica, semántica) para agentes con persistencia.                            | Agente con memoria vectorial que recuerda interacciones pasadas y mejora sus respuestas.                          |
| **Módulo 6**  | Construir pipelines RAG completos con indexación, retrieval híbrido y evaluación de calidad.                                  | Sistema RAG funcional sobre corpus de documentos con métricas de retrieval >80% precision.                        |
| **Módulo 7**  | Diseñar y orquestar sistemas multi-agente con patrones de colaboración y comunicación estructurada.                           | Sistema de 3+ agentes colaborando en tarea compleja usando LangGraph o CrewAI.                                    |
| **Módulo 8**  | Implementar agentes autónomos con capacidades de auto-generación de tareas y meta-cognición.                                  | Agente autónomo que completa objetivo abierto con mínima supervisión humana.                                      |
| **Módulo 9**  | Evaluar agentes mediante métricas de task completion, eficiencia y calidad de razonamiento.                                   | Suite de tests con >80% coverage y reporte de métricas de rendimiento.                                            |
| **Módulo 10** | Desplegar agentes como servicios productivos con seguridad, monitoreo y manejo de errores.                                    | API REST desplegada con logging, métricas y protección contra prompt injection.                                   |
| **Módulo 11** | Integrar todos los conceptos en un sistema multi-agente completo para automatización empresarial.                             | Sistema funcional con demo, documentación, tests y métricas de rendimiento.                                       |

---

## COMPETENCIAS TRANSVERSALES

| Competencia               | Descripción                                                                           | Módulos donde se desarrolla |
| :------------------------ | :------------------------------------------------------------------------------------ | :-------------------------- |
| **Pensamiento Sistémico** | Capacidad de diseñar sistemas complejos considerando interacciones entre componentes. | 4, 5, 7, 8, 11              |
| **Debugging de IA**       | Habilidad para diagnosticar y resolver problemas en sistemas basados en LLMs.         | 3, 4, 6, 9                  |
| **Diseño de APIs**        | Competencia en diseño de interfaces claras para herramientas y agentes.               | 3, 10                       |
| **Evaluación Crítica**    | Capacidad de medir y juzgar la calidad de outputs de sistemas de IA.                  | 2, 6, 9                     |
| **Seguridad en IA**       | Conocimiento de vulnerabilidades y mitigaciones en sistemas de agentes.               | 10                          |

---

## NIVELES DE DOMINIO

### Nivel 1: Fundacional (Módulos 0-2)

El estudiante comprende los fundamentos de IA generativa, configura su entorno y domina las técnicas básicas de prompting.

**Indicadores de logro**:

- Ejecuta llamadas a la API de Gemini con diferentes parámetros
- Diseña prompts efectivos para tareas específicas
- Explica el funcionamiento de transformers y generación de texto

### Nivel 2: Intermedio (Módulos 3-6)

El estudiante construye agentes funcionales con herramientas, memoria y acceso a conocimiento externo.

**Indicadores de logro**:

- Implementa Function Calling con múltiples herramientas
- Construye agentes con ciclo ReAct completo
- Integra sistemas RAG con evaluación de calidad

### Nivel 3: Avanzado (Módulos 7-10)

El estudiante diseña sistemas multi-agente complejos y los despliega en producción.

**Indicadores de logro**:

- Orquesta múltiples agentes con patrones de colaboración
- Implementa agentes autónomos con meta-cognición
- Despliega sistemas con seguridad y observabilidad

### Nivel 4: Experto (Módulo 11)

El estudiante integra todas las competencias en un proyecto completo de nivel profesional.

**Indicadores de logro**:

- Diseña arquitectura de sistema multi-agente completo
- Entrega proyecto funcional con documentación profesional
- Demuestra capacidad de toma de decisiones arquitectónicas

---

## MAPA DE PROGRESIÓN DE HABILIDADES

```
Nivel 1                    Nivel 2                    Nivel 3                    Nivel 4
┌─────────────┐           ┌─────────────┐           ┌─────────────┐           ┌─────────────┐
│ API Básica  │ ────────► │ Agentes     │ ────────► │ Multi-      │ ────────► │ Sistema     │
│ Prompting   │           │ Herramientas│           │ Agente      │           │ Completo    │
│             │           │ Memoria     │           │ Producción  │           │             │
└─────────────┘           └─────────────┘           └─────────────┘           └─────────────┘
   Módulos 0-2              Módulos 3-6              Módulos 7-10              Módulo 11
```

---

## CRITERIOS DE CERTIFICACIÓN

Para obtener la certificación del curso, el estudiante debe:

1. **Completar todos los ejercicios prácticos** de los módulos 0-10 con calificación mínima de 70%.

2. **Aprobar las evaluaciones sumativas** de los módulos 4, 6 y 10 con calificación mínima de 75%.

3. **Entregar el proyecto integrador final** (Módulo 11) cumpliendo:
   - Todos los requisitos funcionales especificados
   - Tests con coverage mínimo de 80%
   - Documentación completa de arquitectura
   - Demo funcional

4. **Demostrar competencias transversales** mediante la calidad del código, documentación y presentación del proyecto.
