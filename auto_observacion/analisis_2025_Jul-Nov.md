# Análisis de Práctica y Metodología (Julio-Noviembre 2025)

*Este documento analiza los datos de los logs de práctica (`registros/`) de Julio a Noviembre de 2025 para extraer hallazgos metodológicos y definir los siguientes pasos del proyecto.*

---

### 1. Patrones Generales de Práctica

Se observa una transición de un estudio intensivo y estructurado (registrado en `registros/2025-Jul.md`) a un **"modo de mantenimiento"** entre Agosto y Noviembre (registrado en `registros/2025-Aug.md`, `registros/2025-Sep.md`, `registros/2025-Oct-Nov.md`). Este cambio se correlaciona con el inicio de un proyecto de desarrollo de software, el cual fue utilizado como un nuevo método de inmersión.

Una consecuencia directa de este patrón es la **reducción de un ciclo de feedback correctivo formal**.

---

### 2. Hallazgos y Evaluación de Métodos

#### 2.1. Efectividad de la Práctica Deliberada vs. Inmersión
Se valida la hipótesis de que la **práctica deliberada** (ejercicios estructurados del libro o con IA) es indispensable para la mejora de la estructura gramatical y la corrección de errores. Actividades de inmersión como el "vibecoding", aunque beneficiosas para la familiaridad con el idioma, no garantizan por sí solas la mejora técnica si no se complementan con un análisis consciente.

#### 2.2. Evaluación de Sesiones de Conversación (iTalki)
Las sesiones de conversación demuestran ser altamente efectivas para **mejorar la fluidez, la confianza y la motivación**. Sin embargo, se identifica una limitación: el formato de una hora semanal no es suficiente para una corrección gramatical exhaustiva. Esto confirma que el aprendizaje de un idioma es un **proceso multifactorial** y que un solo método no es suficiente para un dominio completo. La experiencia y guía de un tutor humano se identifica como un recurso invaluable, irremplazable por la IA en el contexto conversacional.

#### 2.3. Evaluación de Aplicaciones de Gamificación (Duolingo)
Se evaluó la aplicación Duolingo. Se concluye que, si bien su sistema de gamificación es efectivo para **mantener la constancia y el contacto diario** con el idioma debido a su baja carga cognitiva, su enfoque pedagógico es superficial. No promueve un entendimiento profundo de la estructura gramatical, funcionando más como un ejercicio de "fill in the blank" que como una herramienta de aprendizaje estructural.

#### 2.4. Desarrollo de un Nuevo Método: "Análisis de Prompts"
Como resultado de la fase de "vibecoding", emergió una nueva técnica de práctica deliberada: el **"Análisis de Prompts"**. Este método consiste en aislar el lenguaje técnico-profesional usado (ej. en prompts para IA), y usar una segunda instancia de IA como herramienta de análisis gramatical y estructural. Esto crea un ciclo de feedback inmediato y altamente contextualizado para mejorar el inglés técnico.

---

### 3. Áreas de Mejora Prioritarias (Basado en Auto-revisión)

Tras una revisión de notas y grabaciones, se ha consolidado la siguiente lista de áreas prioritarias para el próximo ciclo de estudio, organizadas por categoría:

1.  **Gramática Nuclear:**
    -   Consistencia en **Tiempos Verbales**.
    -   Uso correcto de **Artículos**.
    -   Dominio de **Preposiciones**.
    -   **Phrasal Verbs**.

2.  **Habilidades Comunicativas:**
    -   Construcción de oraciones fluidas y coherentes.
    -   Uso de expresiones naturales e idiomáticas.
    -   Combinaciones léxicas apropiadas (collocations).

3.  **Riqueza y Precisión Léxica:**
    -   Selección precisa de **Adjetivos y Adverbios**.
    -   Variedad en el uso de **Conectores**.
    -   Reducción de redundancia.

---

### 4. Plan de Acción: Tipos de Sprints de Práctica

A continuación se presentan dos tipos de planes de acción que pueden ser ejecutados según los objetivos del momento.

---

#### **4.1. Sprint Temático: Enfoque en un Área Específica**

*Este tipo de sprint es ideal para atacar una de las áreas de mejora prioritarias de forma concentrada.*

**Ejemplo de Aplicación: Sprint de Phrasal Verbs (Noviembre 2025)**

-   **Objetivo:** Mejorar el dominio de los "phrasal verbs" a través de un estudio enfocado y asistido por IA, basado en el libro de gramática de Raymond Murphy.
-   **Compromiso:** Dedicar un mínimo de **4 horas semanales** durante Noviembre a esta tarea.
-   **Actividades:**
    1.  **Estudio Estructurado:** Avanzar en las unidades de "phrasal verbs" del libro de referencia.
    2.  **Práctica Asistida por IA:** Para cada grupo de verbos, usar una IA para generar ejercicios adicionales (crear frases, diálogos, etc.).
-   **Registro:** Las actividades se registrarán de forma flexible en el log mensual correspondiente (ej. `registros/2025-Nov.md`).

-   **Métrica de Éxito:** Aprender y dominar al menos **50 phrasal verbs** comunes, con capacidad de usarlos correctamente en contextos variados.

---

#### **4.2. Sprint Análisis de Prompts**

**Compromiso de Práctica:** Realizar sesiones de práctica deliberada enfocadas en este framework un mínimo de **4 veces por semana**, con una duración de 1 a 2 horas por sesión.

**Marco de Trabajo Estructurado:**

1.  **Fase de Detección:**
    -   **Actividad:** Recolectar un lote de muestras de texto propio y usar una IA con la instrucción: "Analiza estos textos y haz una lista de mis errores más frecuentes esta semana, ordenados de mayor a menor frecuencia".
    -   **Resultado:** Un diagnóstico claro y priorizado de los problemas de la semana.

2.  **Fase de Práctica Enfocada:**
    -   **Actividad:** Basado en los errores identificados, generar sesiones de práctica deliberada, dando prioridad a los que aparecen más arriba en la lista.
    -   **Resultado:** Sesiones de estudio altamente relevantes y eficientes.

3.  **Fase de Registro:**
    -   **Actividad:** En el log mensual, documentar el ciclo: la lista de errores, un ejemplo de un error clave y una frase corregida.
    -   **Resultado:** Un registro de progreso que muestra la evolución de los errores.

**Métricas de Éxito:**

1. **Naturalidad (60%):** Puntaje IA semanal 1-10. Objetivo: 4→7/10.

2. **Gramática (40%):** Puntaje IA semanal 1-10. Objetivo: -50% errores.

**Prompt para IA:** "Evalúa estos textos: 1) Naturalidad 1-10, 2) Gramática 1-10, 3) Errores aproximados, 4) 2 sugerencias."