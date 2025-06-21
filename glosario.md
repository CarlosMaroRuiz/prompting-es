# Glosario

## L

### LLM (Large Language Model)
**Large Language Model** - Modelo de Lenguaje Grande. Sistema de inteligencia artificial entrenado para entender y generar texto humano de manera natural. Es una red neuronal entrenada con enormes cantidades de texto que aprendió a predecir qué palabra viene después en cualquier contexto. Con esa habilidad simple, desarrolló capacidades complejas como escribir, programar, explicar, traducir y conversar.

**Características:**
- Procesó millones de textos para aprender patrones del lenguaje
- Disponible 24/7 sin cansarse
- Puede cometer errores o generar información incorrecta
- Funciona mediante predicción de texto avanzada

## P

### Prompt
Instrucción o mensaje que se le da a un LLM para obtener una respuesta específica. Es la entrada de texto que guía al modelo hacia el resultado deseado.

### Prompt Engineering (Ingeniería Rápida)
Disciplina emergente centrada en diseñar, optimizar y refinar instrucciones (prompts) para hacer buen uso de LLMs con el fin de obtener respuestas más precisas, seguras y adaptadas a necesidades específicas.

**Beneficios:**
- ✅ Mejorar habilidades existentes del LLM
- 🚀 Aumentar conocimiento sin reentrenar
- 🔍 Descubrir capacidades ocultas
- 🎯 Optimizar calidad de salidas

## F

### Few-shot Learning
Técnica básica de prompt engineering que consiste en proporcionar ejemplos de entrada/salida para demostrar el formato y estilo deseado al modelo.

**Estructura:**
```
[Instrucción general]
Ejemplo 1:
Input: [entrada 1]
Output: [salida deseada 1]

Ejemplo 2:
Input: [entrada 2]
Output: [salida deseada 2]

Input: [nueva entrada]
Output:
```

## C

### Contextualización
Técnica básica de prompt engineering que establece un rol o escenario para guiar la perspectiva del modelo.

**Estructura:** "Como [rol/especialista], [acción] [contexto]"

## T

### ToT (Tree of Thoughts - Árbol de Pensamientos)
Técnica avanzada de razonamiento donde el modelo explora múltiples caminos de solución simultáneamente, estructurando el proceso como un árbol de posibilidades.

**Proceso:**
1. **Ramificación:** Genera múltiples opciones/soluciones en cada nodo
2. **Evaluación:** Califica cada rama con métricas específicas
3. **Poda:** Elimina ramas no viables basándose en evaluaciones
4. **Selección:** Elige el mejor camino mediante análisis comparativo

## S

### Self-Consistency (Autoconsistencia)
Técnica donde el modelo genera múltiples líneas de razonamiento, evalúa cada camino independientemente y selecciona la respuesta más consistente entre variantes.

**Beneficios:**
- Reduce errores en problemas complejos
- Minimiza sesgos en decisiones técnicas
- Combina perspectivas complementarias
- Detecta contradicciones internas

## R

### RAG (Generación Aumentada de Recuperación)
Técnica de prompting donde se incluye información específica en el prompt para que el AI genere respuestas más precisas y verificables.

**Fórmula:** Información relevante + Instrucciones claras + Pregunta = Respuesta fundamentada

**Estructura básica:**
```
# INFORMACIÓN BASE
[Datos, documentos o código relevante]

# INSTRUCCIONES
- Usa solo la información proporcionada
- Cita las fuentes
- Si falta info, dilo claramente

# PREGUNTA
[Tu consulta específica]
```

## I

### Instrucciones Explícitas
Comandos directos que especifican acciones concretas usando verbos imperativos.

**Estructura:** "[Verbo imperativo] [objeto] [parámetros]"

**Ejemplos:**
- "Resume este texto en 3 oraciones máximas"
- "Compara X e Y usando tabla de dos columnas"
- "Clasifica este sentimiento: positivo, neutral o negativo"

## E

### Especificación de Formato
Técnica que indica cómo estructurar la respuesta del modelo.

**Estructura:** "[Instrucción] usando formato [tipo] con [elementos]"

**Ejemplos:**
- "Responde en JSON con claves: resumen, ventajas, desventajas"
- "Genera lista numerada con emojis para cada punto"
- "Organiza en secciones con encabezados ##"

## L

### Limitación de Alcance
Técnica que restringe longitud, profundidad o aspectos de la respuesta.

**Estructura:** "[Instrucción] [restricción] [parámetros]"

**Ejemplos:**
- "Explica en máximo 100 palabras"
- "Enumera solo 3 ventajas principales"
- "Responde con metáfora simple"