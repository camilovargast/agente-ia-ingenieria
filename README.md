# agente-ia-ingenieria
Este repositorio contiene el código fuente de un agente de IA para ingeniería elaborado en Hermes.

# Asistente de Ingeniería para el Ciclo de Vida del sistema

> El repositorio _______ 

## Planteamiento

- **Nombre del repositorio:** agente-ia-ingenieria, 
- **Área:** Ingeniería de Sistemas y de Software
- **Tema:** Desarrollo de un Asistente de ingeniería para el ciclo de vida del sistema.
- **Síntoma:** Dificultad de gestionar los artefactos de ingeniería durante el ciclo de vida del sistema. Actualmente, al arrancar un proyecto, el ingeniero dedica días a transformar fuentes dispersas (actas, correos, PDFs del cliente, normativa, especificaciones previas) en los primeros artefactos. Cuando usa un chatbot genérico, cada conversación empieza de cero, las respuestas no usan el contexto real del proyecto, los artefactos de distintas fases y fuentes se contradicen entre sí y no quedan trazadas relaciones lógicas y negocio entre ellos.
- **Causa:** La información y requerimientos del problema esta dispersa en varíos documentos y herramientas, lo que dificulta mantener el contexto.
- **Interes:** [AAAA-MM-DD]
- **Consecuencias de no resolverlo:** [AAAA-MM-DD]
- **Beneficios de resolverlo:** [AAAA-MM-DD]
- **Trabajos existentes:** [AAAA-MM-DD]
- **Solución propuesta:** [AAAA-MM-DD]
- **Hipótesis:** Si un proyecto base se genera a partir de un contexto de proyecto persistente, estructurado y validado mediante reglas deterministas de conformidad semántica —como las definidas por SHACL o ShEx—, integrando las directrices de la guía de INCOSE, técnicas de especificación de requisitos basadas en BDD (Behavior-Driven Development) y la gramática de SysML v2, entonces se alcanzará una cobertura de trazabilidad de al menos el 90 % en la cadena **necesidad → requisito → arquitectura → prueba**, se reducirá en al menos un 40 % la cantidad de defectos de calidad por requisito y se disminuirá en al menos un 50 % el tiempo de preparación del proyecto, en comparación con dos enfoques de referencia:

  - (a) el uso del mismo modelo de lenguaje de gran tamaño (LLM) en un entorno de chat aislado, utilizando las mismas fuentes de información; y

  - (b) la elaboración manual del proyecto.

- **Parámetros para corroborar la hipótesis:** Se ropone construir un marco de evaluación con indicadores cuantitativos, criterios de aceptación (cumplimiento) y un referente (protocolo o estandar) de comparación.

  - **Cobertura de trazabilidad**
    - **Objetivo:** ≥ 90 %
      Mide en qué proporción los elementos del proyecto están conectados de forma válida a lo largo de la cadena **necesidad → requisito → arquitectura → prueba**.

  - **Indicadores:**
    - Porcentaje de necesidades vinculadas a los requisitos.
    - Porcentaje de requisitos vinculados a los elementos arquitectónicos.
    - Porcentaje de requisitos con pruebas asociadas.
    - Porcentaje de cadenas completas y verificables de extremo a extremo (Pruebas de Integración).
    - Se mediría la cadena completa, no solo la existencia de enlaces individuales.


- **Calidad de los requisitos**
    - **Objetivo:** reducir defectos ≥ 40 %
Mide los defectos detectados por requisito incumplido o mal especificado.

    - **Indicadores:**
        - Total de requisitos ambiguos o vagos.
        - Total de requisitos no verificables.
        - Total de requisitos incompletos o inconsistentes.
        - Total de duplicidades y contradicciones.
        - Porcentaje de incumplimientos de reglas sintácticas o semánticas.

    - **Tiempo de preparación**
        - **Objetivo:** reducir tiempo ≥ 50 %
Mide el esfuerzo necesario para obtener un proyecto base que cumpla los criterios de aceptación establecidos.

    - **Indicadores:**
        - Tiempo hasta generar el primer proyecto base.
        - Tiempo dedicado a corregir requisitos y modelos.
        - Tiempo de validación y revisión.
        - Tiempo total hasta alcanzar un tiempo definido previamente.
        - Debe contabilizarse el tiempo de intervención humana, incluidas las correcciones, y no solo el tiempo de generación automática.


- **Estándares implicados:** Shacl, ShEx, NCOSE Guide to Writing Requirements v4 – Summary Sheet, SysML v2.


## Objetivo General

Implementar un agente en Hermes para que analice las diferenes fuentes de información suministradas por el ingeniero y enriquesca el conexto a traves de diferentes validaciones para que apartir de este, el agente genere un proyecto base con los artectos solicitados.


## Objetivos Específicos

| ID | Objetivo específico  | Resultado en el repositorio | Criterio de aceptación |objetivo |
| --- | --- | --- | --- | --- |
| OE1 | Analizar implementaciones agenticas similares en el mercado y evaluar su desempeño | [Tipo] | [Prioridad] | Pendiente |
| OE2 | Diseñar la arquitectura para la implementeción del agente  | [Tipo] | [Prioridad] | Pendiente |
| OE3 | Desarrollar los componentes de software adicionales para la entrenamiento del agente | [Tipo] | [Prioridad] | Pendiente |
| OE4 | [Título breve] | [Tipo] | [Prioridad] | Pendiente |
| OE5 | [Título breve] | [Tipo] | [Prioridad] | Pendiente |

**Tipos sugeridos:** Entregable, Funcionalidad, Tarea, Error, Investigación.

**Prioridades:** Alta, Media, Baja.

**Estados:** Pendiente, En curso, Bloqueado, En revisión, Completado, Cancelado.
