# Asistente de Ingeniería para el Ciclo de Vida del sistema

El repositorio **agente-ia-ingenieria** contiene el desarrollo de un asistente basado en inteligencia artificial generativa para apoyar al ingeniero informático durante distintas fases del ciclo de vida del software. El asistente mantiene un contexto persistente del proyecto y permite generar y revisar artefactos de análisis de necesidades, requisitos, arquitectura, diseño, verificación y validación. Asimismo, proporciona trazabilidad entre los artefactos y se integra con herramientas de desarrollo para apoyar la continuidad y coherencia del trabajo.

## Planteamiento

- **Nombre del repositorio:** agente-ia-ingenieria, 
- **Área:** Ingeniería de Sistemas y de Software
- **Tema:** Desarrollo de un asistente de inteligencia artificial generativadel software.
- **Síntoma:** Dificultad de gestionar los artefactos de ingeniería durante el ciclo de vida del sistema. Actualmente, al arrancar un proyecto, el ingeniero dedica días a transformar fuentes dispersas (actas, correos, PDFs del cliente, normativa, especificaciones previas) en los primeros artefactos. Cuando usa un chatbot genérico, cada conversación empieza de cero, las respuestas no usan el contexto real del proyecto, los artefactos de distintas fases y fuentes se contradicen entre sí y no quedan trazadas relaciones lógicas y negocio entre ellos.
- **Causa:** La información y requerimientos del problema esta dispersa en varíos documentos y herramientas, lo que dificulta mantener el contexto.
- **Interes:** [AAAA-MM-DD]
- **Consecuencias de no resolverlo:** 
    - No se ofrecería un planteamiento rápido del proyecto de software porque el ingeniero tendría que proporcionarle el contexto a la IA manualmente.
    - Pérdida del contexto relacionado con los avances del ingeniero cuando este decida cambiar de agente.
    - Falta de consistencia en las respuestas de la IA durante las diferentes etapas del proyecto.
- **Beneficios de resolverlo:** 
    - Reduce significativamente el tiempo empleado por parte de un ingeniero en la creación de artefactos y validaciones.
    - El **agente-ia-ingenieria** acompañará al ingeniero durante las diferentes etapas del proyecto, aprendiendo del contexto adicional proporcionado y almacenándolo en su memoria para consultas posteriores.
- **Trabajos existentes:** [AAAA-MM-DD]
- **Solución propuesta:** [AAAA-MM-DD]
- **Hipótesis:** [Si se implementa un agente de IA generativa en Hermes capaz de analizar diferentes fuentes de información, mantener el contexto del proyecto y generar artefactos de ingeniería, entonces se reducirá al menos un X% el tiempo necesario para crear los artefactos iniciales y se mejorará su consistencia y trazabilidad, en comparación con el uso de un chatbot genérico sin contexto persistente.]
- **Parámetros para corroborar la hipótesis:** [Tiempo de generación: reducción de al menos un X% del tiempo necesario para generar los artefactos iniciales.Consistencia de la información: al menos un X% de coherencia entre los artefactos generados y las fuentes originales.]
- **Estándares implicados:** [ISO/IEC/IEEE 15288: procesos del ciclo de vida de sistemas.ISO/IEC/IEEE 29148: definición, análisis y calidad de requisitos.]


## Objetivo General

Implementar un agente en Hermes para que analice las diferenes fuentes de información suministradas por el ingeniero y enriquesca el conexto a traves de diferentes validaciones para que apartir de este, el agente generará un proyecto base con los artectos solicitados.


## Objetivos Específicos

| ID | Objetivo específico  | Resultado en el repositorio | Criterio de aceptación |objetivo |
| --- | --- | --- | --- | --- |
| OE1 | Analizar implementaciones agenticas similares en el mercado y evaluar su desempeño | [Tipo] | [Prioridad] | Pendiente |
| OE2 | Diseñar la arquitectura para la implementeción del agente  | [Tipo] | [Prioridad] | Pendiente |
| OE3 | Desarrollar los componentes de software adicionales para la entrenamiento del agente | [Componentes de software implementados e integrados en Hermes para el procesamiento de fuentes de información y enriquecimiento del contexto del proyecto.] | [Los componentes permiten procesar al menos 3 tipos de fuentes (PDF, TXT y DOCX), almacenar el contexto del proyecto] | Hipótesis: el uso de un agente con contexto persistente permite reducir el tiempo de generación de artefactos y mejorar su consistencia y trazabilidad. Parámetros: tiempo de generación, consistencia de la información y persistencia del contexto. |
| OE4 | [Título breve] | [Tipo] | [Prioridad] | Pendiente |
| OE5 | [Título breve] | [Tipo] | [Prioridad] | Pendiente |

**Tipos sugeridos:** Entregable, Funcionalidad, Tarea, Error, Investigación.

**Prioridades:** Alta, Media, Baja.

**Estados:** Pendiente, En curso, Bloqueado, En revisión, Completado, Cancelado.
