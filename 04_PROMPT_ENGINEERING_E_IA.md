# PROMPT ENGINEERING E IA APLICADA AL MARKETING
*Conocimiento consolidado de: CHAT MARKETING*

---

## 🎯 ESTRUCTURA BÁSICA DE PROMPT GANADOR

**Fórmula maestra**: `[ROL] + [TAREA ESPECÍFICA] + [CONTEXTO RELEVANTE] + [FORMATO DE SALIDA] + [RESTRICCIONES] + [EJEMPLOS SI NECESARIO]`

### EJEMPLO PRÁCTICO - ANÁLISIS DE COMPETENCIA:

```
Actúa como un analista de mercado senior con 15 años de experiencia en [INDUSTRIA].

Analiza los 3 principales competidores de [NUESTRA EMPRESA] en [MERCADO GEOGRÁFICO].

Incluye para cada uno:
1. Propuesta de valor principal
2. Precio promedio y estructura
3. Fortalezas y debilidades identificadas por clientes
4. Estrategia de marketing actual
5. Oportunidades que están dejando pasar

Formato: Tabla comparativa seguida de 3 insights accionables.

Restricciones: Máximo 400 palabras, lenguaje ejecutivo, basado únicamente en información pública verificable.

Ejemplo de insight accionable: "Competidor X deja sin atender el segmento de [DESCRIPCIÓN] que representa [PORCENTAJE]% del mercado."
```

---

## 🔑 PRINCIPIOS CLAVE DE PROMPT ENGINEERING

### 1. ESPECIFICIDAD VENCE A LA AMBIGÜEDAD

❌ **Mal prompt**: "háblame de marketing"

✅ **Buen prompt**: "explica 3 tácticas de email marketing para ecommerce de moda dirigido a mujeres 25-35 en Latinoamérica, con ejemplos de asuntos que generan >25% open rate"

**Por qué funciona**: Delimita industria, audiencia, geografía, métrica de éxito y pide ejemplos concretos.

### 2. CONTEXTO ES REY

Proporciona información de fondo que limite el espacio de posibilidades correctas.

❌ **Sin contexto**: "crea un plan de marketing"

✅ **Con contexto**: "crea un plan de marketing de 90 días para startup de SaaS B2B con presupuesto de $5,000/mes, equipo de 2 personas de marketing, y objetivo de generar 100 leads calificados/mes"

**Por qué funciona**: La IA sabe exactamente con qué restricciones trabajar y puede dar recomendaciones accionables.

### 3. FORMATO DEFINIDO

Especifica si quieres tabla, lista, párrafo, guion, etc.

✅ **Ejemplos de especificación de formato**:
- "Formato: Tabla con columnas: Táctica, Costo estimado, Tiempo de implementación, ROI esperado"
- "Formato: Lista numerada de 10 elementos, cada uno con máximo 2 oraciones"
- "Formato: Guion de video de 60 segundos con timestamps cada 10 segundos"
- "Formato: Email de 150-200 palabras con asunto, saludo, cuerpo y CTA"

### 4. RESTRICCIONES INTELIGENTES

Límites de longitud, tono, fuentes permitidas evitan respuestas genéricas o inútiles.

✅ **Ejemplos de restricciones útiles**:
- "Máximo 400 palabras"
- "Lenguaje ejecutivo, sin jerga técnica"
- "Basado únicamente en información pública verificable"
- "No mencionar competencia por nombre"
- "Incluir al menos 3 ejemplos concretos"
- "Usar tono conversacional, no corporativo"

### 5. EJEMPLOS ANCLA

Cuando el formato es complejo, muestra exactamente qué esperas.

✅ **Ejemplo con ancla**:
```
Crea 5 variaciones de USP para [PRODUCTO].

Sigue este formato exacto:
"[VERBO] + [BENEFICIO] + [PARA QUIÉN] + [RESULTADO MEDIBLE]"

Ejemplo de lo que busco:
"Domina tu ansiedad en 21 días sin medicación"

Ahora crea 5 variaciones para [TU PRODUCTO].
```

---

## 📋 12 PROMPTS EJECUTIVOS LISTOS PARA USAR (CHAT MARKETING)

### 1. ANÁLISIS CULTURAL (HOFSTEDE)

```
Según la teoría de Geert Hofstede, analiza las dimensiones culturales de [PAÍS] y proporciona sus índices.

Cruza esta información con la categoría [CATEGORÍA] para insights relevantes.

Formato: Tabla con las 6 dimensiones, índice de cada una, y recomendación específica de marketing para esa dimensión en ese mercado.
```

### 2. DEFINICIÓN DE CATEGORÍA DE NEGOCIO

```
Define la categoría de negocio para [PRODUCTO/SERVICIO].

Analiza:
1. Qué tipo de producto es
2. En qué industria opera
3. Competidores principales
4. Mercado objetivo (segmentación)
5. Estrategia de marketing actual

Incluye también: ¿En qué categoría DEBERÍA estar este producto para diferenciarse de competencia?
```

### 3. GENERADOR DE USP

```
Desarrolla la USP para [PRODUCTO] como experto en marketing estratégico.

Considera: beneficio único, diferenciación de competencia, resultado específico.

Responde en máximo 144 caracteres.

Crea 5 variaciones para poder elegir la más potente.
```

### 4. BUYER PERSONA ENRIQUECIDO

```
Basado en esta información básica [INSERTAR INFO], crea un buyer persona detallado incluyendo:

- Nombre ficticio y foto descriptiva
- Personalidad (3-5 rasgos clave)
- Necesidades funcionales vs emocionales
- Valores principales (no negociables)
- Canales de comunicación preferidos
- Comportamiento online (redes, frecuencia)
- Proceso de compra típico
- Miedos existenciales vs superficiales
- Deseos profundos (categorías: evolutivo, conductual, emocional, existencial)

Formato: Perfil narrativo de 500-700 palabras que pueda ser usado directamente por equipo de marketing.
```

### 5. ANÁLISIS DE MIEDOS Y DESEOS

```
Dame una lista de los miedos articulados y profundos principales frente a [PRODUCTO].

Clasifica cada uno en: Lógico (superficial) / Psicológico (social) / Existencial (profundo).

Luego dame soluciones específicas para cada miedo.

Repite el proceso para deseos: superficiales, emocionales, existenciales.

Formato: Dos tablas separadas (miedos y deseos) con columnas: Nivel, Descripción, Cómo nuestro producto lo aborda.
```

### 6. JOBS TO BE DONE

```
Usando el marco Jobs to be Done, dame 10 trabajos posibles que los clientes quieren realizar contratando [PRODUCTO/SERVICIO].

Selecciona 3 que generen diferenciación real frente a competencia.

Diseña soluciones específicas para esos 3 jobs.

Para cada solución, incluye: qué cambiar en producto/servicio, cómo comunicarlo, métrica de éxito.
```

### 7. CÓDIGO SÍMBOLICO (RAPAILLE)

```
Basado en la teoría de Clotaire Rapaille, dame una lista de hipótesis sobre las "improntas" emocionales subconscientes posibles para [CONCEPTO/CATEGORÍA].

Identifica el código cultural probable en [PAÍS/MERCADO].

Incluye:
- Experiencias infantiles universales relacionadas
- Emociones asociadas
- Símbolos contemporáneos que activan esas emociones
- Recomendación de cómo aplicar en comunicación de marca
```

### 8. ARQUETIPO DE MARCA

```
Basado en la teoría de arquetipos de Jung y ejemplos como Natura (Cuidador), Mercado Libre (Libertador), determina qué arquetipo representa mejor a [MARCA] y por qué.

Incluye:
- Arquetipo principal y por qué
- Arquetipo secundario (si aplica)
- Cómo debe manifestarse en: tono de voz, visuales, mensajes clave, comportamiento en redes
- 3 marcas de referencia que usan este arquetipo exitosamente
- Errores comunes a evitar con este arquetipo
```

### 9. METÁFORA DE COMUNICACIÓN (ZALTMAN)

```
Basado en las 7 metáforas de Gerald Zaltman (Equilibrio, Transformación, Viaje, Contenedor, Conexión, Recurso, Control), ¿cuál es la más adecuada para [PRODUCTO] y por qué?

Crea 5 mensajes publicitarios usando esa metáfora para [PÚBLICO OBJETIVO].

Formato:
1. Explicación de por qué esta metáfora (100-150 palabras)
2. Los 5 mensajes con formato: [Medio] - [Mensaje exacto] - [Por qué funciona con esta metáfora]
```

### 10. SECUENCIA DE EMAIL MARKETING (5 EMAILS)

```
Escribe una secuencia de 5 correos electrónicos para [MODELO DE NEGOCIO].

Requisitos:
- Enfoque educativo (no venta directa)
- Contenido de alta calidad
- Ejemplos de vida real
- Actividades prácticas sencillas
- 1 llamado a la acción al final de cada email
- Estilo conversacional y motivador

Para cada email incluye:
- Asunto (crear 3 variaciones para A/B testing)
- Cuerpo del email (150-250 palabras)
- CTA específico
- Día recomendado de envío (día 1, 3, 7, 14, 30)
```

### 11. IDEAS DE CONTENIDO PARA REDES SOCIALES

```
Crea 10 ideas de contenido para [PLATAFORMA/RED] sobre [TEMA].

Estructura la tabla con:
- N°
- Idea de contenido (descripción clara)
- Formato (imagen/carrusel/video/reel/story)
- Etapa del funnel (descubrimiento/consideración/decisión)
- Red social específica
- Hook/gancho (primera frase que captura atención)
- CTA recomendado

Asegúrate de que las ideas sean variadas: educativas, inspiracionales, de entretenimiento, de venta suave.
```

### 12. ARTÍCULO SEO OPTIMIZADO

```
Ayúdame a escribir un artículo SEO sobre [TEMA/KEYWORD].

Palabra clave principal: [KEYWORD]

Indica la etapa del buyer journey (descubrimiento/consideración/decisión).

Propón 5 títulos H1.

Estructura con H2 y H3 optimizados.

Mínimo [X] palabras.

Incluye también:
- Meta descripción (150-160 caracteres)
- 3-5 keywords secundarias relacionadas
- Sugerencia de imagen principal y alt text
- 2-3 enlaces internos sugeridos (a qué páginas enlazaría)
- 1-2 enlaces externos de autoridad (qué fuentes citar)
```

---

## 🧠 PRINCIPIOS AVANZADOS DE PROMPT ENGINEERING

### TÉCNICA DE "CHAIN OF THOUGHT" (CADENA DE PENSAMIENTO)

Para problemas complejos, pide a la IA que piense paso a paso:

```
Resuelve este problema de marketing: [DESCRIBIR PROBLEMA]

Piensa paso a paso:
1. Primero, identifica el problema central
2. Luego, analiza las causas raíz
3. Después, genera 3 posibles soluciones
4. Finalmente, recomienda la mejor solución con justificación

Muestra tu razonamiento para cada paso antes de dar la respuesta final.
```

### TÉCNICA DE "FEW-SHOT LEARNING" (APRENDIZAJE CON POCOS EJEMPLOS)

Proporciona ejemplos de lo que quieres antes de pedir la tarea:

```
Voy a darte ejemplos de USPs efectivas:

Ejemplo 1: "Domina tu ansiedad en 21 días sin medicación"
- Verbo: Domina
- Beneficio: ansiedad controlada
- Para quién: tú implícito
- Resultado: 21 días (medible)

Ejemplo 2: "Ahorra 10 horas/semana en tareas administrativas"
- Verbo: Ahorra
- Beneficio: tiempo recuperado
- Para quién: emprendedores implícito
- Resultado: 10 horas/semana (medible)

Ahora crea 5 USPs siguiendo este mismo patrón para [TU PRODUCTO].
```

### TÉCNICA DE "ROLE PLAYING" (JUEGO DE ROLES)

Asigna un rol específico para obtener respuestas más especializadas:

```
Actúa como [ROL ESPECÍFICO] con [X] años de experiencia en [INDUSTRIA/ESPECIALIDAD].

Tu tarea es: [DESCRIPCIÓN DE TAREA]

Piensa y responde como lo haría ese experto, usando su lenguaje, prioridades y marco mental.

Si hay múltiples perspectivas posibles, menciónalas y explica cuál recomendarías y por qué.
```

### TÉCNICA DE "ITERATIVE REFINEMENT" (REFINAMIENTO ITERATIVO)

No te quedes con la primera respuesta, itera:

```
[Prompt inicial] → [Respuesta de IA]

"Buena respuesta, pero ahora:
- Hazla más específica para [AUDIENCIA]
- Agrega 2 ejemplos concretos
- Reduce a 200 palabras
- Usa tono más [TONO DESEADO]

Reescribe con estos ajustes."
```

---

## ⚠️ ERRORES COMUNES EN PROMPT ENGINEERING

### 1. DEMASIADO VAGO
❌ "Escribe sobre marketing"
✅ "Escribe un artículo de 800 palabras sobre 5 tácticas de email marketing para ecommerce de moda, con ejemplos de asuntos que generan >25% open rate"

### 2. DEMASIADAS INSTRUCCIONES A LA VEZ
❌ Prompt de 500 palabras con 20 requerimientos diferentes
✅ Divide en múltiples prompts secuenciales, cada uno enfocado en un aspecto

### 3. NO DAR CONTEXTO SUFICIENTE
❌ "Crea un plan de marketing"
✅ "Crea un plan de marketing de 90 días para startup de SaaS B2B con presupuesto de $5,000/mes, equipo de 2 personas, objetivo de 100 leads calificados/mes"

### 4. NO ESPECIFICAR FORMATO
❌ "Dame ideas de contenido"
✅ "Dame 10 ideas de contenido en formato tabla con columnas: Idea, Formato, Plataforma, Etapa del funnel, Hook, CTA"

### 5. NO ITERAR
❌ Aceptar la primera respuesta aunque no sea perfecta
✅ "Buena respuesta, ahora ajusta X, Y, Z para que sea más [CRITERIO]"

---

## 📈 MÉTRICAS DE CALIDAD DE PROMPTS

| Métrica | Cómo medir | Benchmark |
|---------|------------|-----------|
| **Tasa de utilidad** | % de respuestas que son directamente usables sin edición mayor | >70% |
| **Tasa de iteración** | Promedio de iteraciones necesarias para obtener respuesta satisfactoria | 1-3 |
| **Tiempo ahorrado** | Tiempo que tomaría hacer la tarea manualmente vs. con IA + revisión | 50-80% de ahorro |
| **Consistencia** | % de respuestas que mantienen calidad y formato a través de múltiples ejecuciones | >85% |
| **Especificidad** | % de respuestas que abordan exactamente lo pedido sin divagación | >90% |

---

## 💡 FRASES CLAVE SOBRE PROMPT ENGINEERING

- **"Un prompt bien escrito es como un brief creativo para un empleado: cuanto más claro seas, mejor será el resultado."**

- **"La IA no lee tu mente, lee tu prompt. Si es vago, la respuesta será vaga."**

- **"No preguntes 'qué puedes hacer', pregunta 'cómo harías X específico con Y restricciones'."**

- **"El mejor prompt es el que podrías darle a un freelancer inteligente que no conoce tu negocio y obtener exactamente lo que necesitas."**

- **"Iterar no es fallar, es refinar. La primera respuesta rara vez es la mejor."**

---

*Fecha de consolidación: 2026-03-16*
*Fuente: CHAT MARKETING (Módulo #4: Prompt Engineering + Prompts Ejecutivos)*
*Propósito: Base de conocimiento para agente VPS sin acceso al PC principal*
