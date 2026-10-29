# Guía de uso de Claude AI

Esta guía sirve como base para crear mejores prompts y flujos de trabajo con Claude AI.

## 1. Principios de prompting efectivo

### Ser claro y específico

En lugar de pedir algo vago como:

```text
Ayúdame con este proyecto
```

usa:

```text
Eres un ingeniero de software senior. Revisa este repositorio y dime:
1. qué hace cada módulo principal,
2. qué riesgos de mantenimiento ves,
3. qué mejoras harías en orden de prioridad.
Entrega la respuesta en formato de tabla con columnas: módulo, función, riesgo, recomendación.
```

### Dar contexto útil

Incluye:
- objetivo final
- restricciones del proyecto
- público objetivo
- formato deseado
- nivel de detalle requerido

### Definir el formato de salida

Pide explícitamente el formato:
- lista
- tabla
- markdown
- JSON
- bullets
- plan paso a paso

## 2. Patrones de prompt útiles

### Patrón 1: Rol + contexto + tarea + formato

```text
Rol: Eres un analista de producto senior.
Contexto: Estamos lanzando una nueva funcionalidad para usuarios no técnicos.
Tarea: Identifica los riesgos principales y sugiere una estrategia de comunicación.
Formato: entrega 5 puntos con impacto, riesgo y mitigación.
```

### Patrón 2: Comparación y evaluación

```text
Compara estas dos soluciones para [problema]. Evalúa:
- coste de implementación,
- complejidad,
- mantenimiento,
- experiencia del usuario,
- riesgos.
Entregame un resumen ejecutivo con recomendación final.
```

### Patrón 3: Refinamiento iterativo

```text
Primero haz una propuesta inicial. Luego mejora la respuesta considerando:
- mayor claridad,
- mejor estructura,
- menos ambigüedad,
- enfoque práctico.
```

## 3. Checklist antes de enviar un prompt

- ¿He definido claramente el objetivo?
- ¿He dado suficiente contexto?
- ¿He especificado el formato de salida?
- ¿He indicado restricciones o limitaciones?
- ¿He pedido una acción concreta?

## 4. Ejemplos por caso de uso

### Desarrollo de software

```text
Eres un ingeniero senior. Revisa este código y encuentra bugs potenciales, riesgos de seguridad y oportunidades de mejora. Hazlo en formato de análisis técnico con severidad y recomendaciones concretas.
```

### Investigación documental

```text
Resume esta documentación enfocándote en:
- objetivos del proyecto,
- requisitos clave,
- dependencias,
- riesgos.
Entrega un resumen ejecutivo de 8 a 12 líneas.
```

### Redacción y comunicación

```text
Escribe un mensaje claro para un cliente sobre [tema]. Debe ser profesional, directo y de máximo 150 palabras. Incluye un tono amigable y una propuesta clara de siguiente paso.
```

## 5. Mejora continua

Guarda tus prompts buenos y analiza:
- qué dio mejor resultado,
- qué información faltaba,
- qué formato funcionó mejor,
- cómo puedes hacer la siguiente solicitud más precisa.

## 6. Plantilla reutilizable

```text
Rol: [persona o experto]
Objetivo: [qué quieres lograr]
Contexto: [qué información relevante tienes]
Restricciones: [limitaciones, estilo, reglas]
Tarea: [acción exacta]
Formato de salida: [tabla, lista, JSON, etc.]
Criterio de calidad: [qué hace una buena respuesta]
```

## 7. Consejo final

La diferencia entre un prompt promedio y uno excelente suele estar en la claridad, el contexto y el formato pedido. Cuanto más preciso sea el prompt, mejor será la respuesta y menor la necesidad de reformular.
