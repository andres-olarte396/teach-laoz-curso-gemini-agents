# CRONOGRAMA DETALLADO: Automatización con Agentes en Google Gemini

## RESUMEN TEMPORAL

- **Duración Total**: 16 Semanas (4 meses)
- **Carga Semanal**: 6-7 horas
- **Formato**: Estudio teórico (30%) + Práctica guiada (40%) + Proyectos (30%)

---

## CALENDARIO SEMANAL

### MES 1: FUNDAMENTOS Y API

#### Semana 1: Nivelación y Setup

- **Contenido**: Módulo 0 - Fundamentos de IA Generativa
- **Temas**: Transformers, LLMs, Familia Gemini
- **Actividad Clave**: Configurar GCP y obtener API Key
- **Entregable**: Primer script funcional con llamada a Gemini

#### Semana 2: Dominio de la API (Parte 1)

- **Contenido**: Módulo 1 - Temas 1.1 y 1.2
- **Temas**: Generación de texto, parámetros, multimodalidad
- **Actividad Clave**: Experimentar con temperature, top-p, top-k
- **Entregable**: Notebook con análisis de imágenes

#### Semana 3: Dominio de la API (Parte 2)

- **Contenido**: Módulo 1 - Tema 1.3 + Inicio Módulo 2
- **Temas**: Conversaciones multi-turno, System Instructions
- **Actividad Clave**: Implementar chatbot con contexto persistente
- **Entregable**: Chatbot básico funcional

#### Semana 4: Ingeniería de Prompts

- **Contenido**: Módulo 2 - Temas 2.1 y 2.2
- **Temas**: Zero/Few-shot, CoT, Self-Consistency
- **Actividad Clave**: Comparar efectividad de diferentes técnicas
- **Entregable**: Biblioteca de prompts con métricas

---

### MES 2: AGENTES Y HERRAMIENTAS

#### Semana 5: Prompts para Agentes + Function Calling Básico

- **Contenido**: Módulo 2 - Tema 2.3 + Módulo 3 - Tema 3.1
- **Temas**: Prompts de planificación, JSON Schema para funciones
- **Actividad Clave**: Implementar primera función invocable
- **Entregable**: Agente con una herramienta funcional

#### Semana 6: Herramientas Avanzadas

- **Contenido**: Módulo 3 - Temas 3.2 y 3.3
- **Temas**: Diseño de tools, APIs externas, manejo de errores
- **Actividad Clave**: Crear toolkit de 3+ herramientas
- **Entregable**: Suite de herramientas integradas

#### Semana 7: Arquitectura de Agentes

- **Contenido**: Módulo 4 - Temas 4.1 y 4.2
- **Temas**: ReAct, Bucle O-T-A, Planificación
- **Actividad Clave**: Construir agente con ciclo completo
- **Entregable**: Agente ReAct funcional

#### Semana 8: Agentes Prácticos

- **Contenido**: Módulo 4 - Tema 4.3
- **Temas**: Agentes de investigación, análisis, automatización
- **Actividad Clave**: Implementar agente de caso de uso real
- **Entregable**: **EVALUACIÓN SUMATIVA 1** - Agente completo
- **Checkpoint**: Revisión de progreso Mes 2

---

### MES 3: MEMORIA, RAG Y MULTI-AGENTE

#### Semana 9: Sistemas de Memoria

- **Contenido**: Módulo 5 completo
- **Temas**: Memoria corto/largo plazo, Vector stores, Grafos
- **Actividad Clave**: Implementar memoria persistente
- **Entregable**: Agente con memoria que recuerda sesiones

#### Semana 10: RAG Fundamentos

- **Contenido**: Módulo 6 - Temas 6.1 y 6.2
- **Temas**: Embeddings, Vector DB, Hybrid Search
- **Actividad Clave**: Construir pipeline de indexación
- **Entregable**: Sistema RAG básico funcional

#### Semana 11: RAG en Producción

- **Contenido**: Módulo 6 - Tema 6.3
- **Temas**: Chunking, Evaluación, Actualización
- **Actividad Clave**: Medir y optimizar calidad de retrieval
- **Entregable**: **EVALUACIÓN SUMATIVA 2** - Sistema RAG completo

#### Semana 12: Sistemas Multi-Agente

- **Contenido**: Módulo 7 - Temas 7.1 y 7.2
- **Temas**: Supervisor-Worker, Comunicación, Conflictos
- **Actividad Clave**: Diseñar arquitectura multi-agente
- **Entregable**: Diagrama de arquitectura + prototipo

---

### MES 4: PRODUCCIÓN Y PROYECTO FINAL

#### Semana 13: Orquestación y Autonomía

- **Contenido**: Módulo 7 - Tema 7.3 + Módulo 8
- **Temas**: LangGraph, CrewAI, Agentes autónomos
- **Actividad Clave**: Implementar sistema con framework
- **Entregable**: Sistema multi-agente con 3+ agentes

#### Semana 14: Testing y Producción

- **Contenido**: Módulos 9 y 10
- **Temas**: Métricas, Testing, Seguridad, Monitoreo
- **Actividad Clave**: Preparar agente para producción
- **Entregable**: **EVALUACIÓN SUMATIVA 3** - API desplegada con monitoreo

#### Semana 15: Proyecto Integrador (Desarrollo)

- **Contenido**: Módulo 11 - Temas 11.1 y 11.2
- **Temas**: Diseño de arquitectura, Implementación
- **Actividad Clave**: Desarrollo intensivo del proyecto
- **Entregable**: Código funcional + tests

#### Semana 16: Proyecto Integrador (Entrega)

- **Contenido**: Módulo 11 - Tema 11.3
- **Temas**: Documentación, Demo, Presentación
- **Actividad Clave**: Preparar y presentar proyecto
- **Entregable**: **PROYECTO FINAL COMPLETO**
- **Checkpoint**: Evaluación final y retrospectiva

---

## HITOS Y ENTREGABLES CLAVE

| Semana | Hito                                 | Tipo         |  Peso   |
| :----: | :----------------------------------- | :----------- | :-----: |
|   1    | Setup completo + Primera llamada     | Formativo    |    -    |
|   4    | Biblioteca de prompts                | Formativo    |   10%   |
|   8    | **Agente completo con herramientas** | **Sumativo** | **20%** |
|   11   | **Sistema RAG funcional**            | **Sumativo** | **20%** |
|   14   | **API en producción**                | **Sumativo** | **15%** |
|   16   | **Proyecto integrador final**        | **Sumativo** | **35%** |

---

## DISTRIBUCIÓN SEMANAL RECOMENDADA

```
Lunes-Martes:    Estudio teórico (2h)
                 - Lectura del material
                 - Videos explicativos
                 - Revisión de documentación API

Miércoles-Jueves: Práctica guiada (2.5h)
                  - Ejercicios del módulo
                  - Implementación paso a paso
                  - Debugging y experimentación

Viernes-Domingo:  Proyecto/Entregable (2h)
                  - Trabajo en entregable semanal
                  - Integración de conceptos
                  - Revisión y refinamiento
```

---

## RUTAS ALTERNATIVAS

### Ruta Acelerada (12 semanas)

Para estudiantes con experiencia previa en LLMs:

- Comprimir Módulos 0-2 en 2 semanas
- Omitir Módulo 8 (Agentes Autónomos)
- Reducir tiempo de práctica guiada

### Ruta Extendida (20 semanas)

Para estudiantes que necesitan más práctica:

- Agregar semana adicional por cada módulo técnico (3-7)
- Incluir sesiones de mentoría
- Expandir proyecto final a 4 semanas

---

## RECURSOS DE SOPORTE POR SEMANA

| Semana | Oficinas Horas  |  Foro Activo  | Material Extra |
| :----: | :-------------: | :-----------: | :------------: |
|  1-4   | Miércoles 18:00 | General + API |  Docs Gemini   |
|  5-8   | Miércoles 18:00 |    Agentes    |  Papers ReAct  |
|  9-12  | Miércoles 18:00 |  RAG + Multi  | LangChain Docs |
| 13-16  | Martes + Jueves |   Proyecto    | Mentorías 1:1  |
