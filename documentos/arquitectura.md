# Sin Nudo AI — Fase 2: Diseño del motor de decisión del producto (lógica)

Modelo de decisión:

pregunta → respuesta → puntaje del nudo → nudo dominante → diagnostico → recomendacion

---

## Objetivo

Detectar qué tipo de bloqueo asociado al síndrome del impostor está afectando a la usuaria y entregar como acción una recomendación clara y accionable.

---

## Flujo

Usuario responde 5 preguntas
↓
Se asigna puntaje a cada nudo
↓
Se identifica el nudo dominante
↓
Se genera diagnóstico
↓
Se entrega recomendación

---

## 1. Preguntas del juego — Identificación de patrones

1. ¿Sientes que tus logros se deben más a la suerte que a tu talento?

2. ¿Dudas de tus habilidades incluso cuando tienes experiencia o conocimientos en un área?

3. ¿Has evitado aplicar a oportunidades profesionales porque pensaste que no eras lo suficientemente buena?

4. ¿Sientes que la presión económica limita tu capacidad de buscar oportunidades que valoren tu talento?

5. ¿Has considerado o aceptado oportunidades laborales por necesidad económica aunque no reflejen tu verdadero valor?

---

## 2. Nudos (bloqueos) del síndrome del impostor — Clasificación

Los nudos representan patrones de pensamiento o contexto que pueden estar bloqueando la toma de decisiones profesionales. Cada pregunta del juego ayuda a identificar uno de estos nudos.

---

### 1. Nudo de la desvalorización del logro  
*(Impostor clásico)*

Relacionado con la pregunta:  
¿Sientes que tus logros se deben más a la suerte que a tu talento?

**Descripción**

La persona minimiza sus logros y atribuye su éxito a factores externos como la suerte o circunstancias temporales. Esto reduce la confianza para asumir nuevos retos.

---

### 2. Nudo de la duda constante  
*(Inseguridad profesional)*

Relacionado con la pregunta:  
¿Dudas de tus habilidades incluso cuando tienes experiencia o conocimientos en un área?

**Descripción**

Aunque existen habilidades o experiencia, la percepción de insuficiencia genera inseguridad y dependencia de validación externa.

---

### 3. Nudo de la evitación de oportunidades  
*(Bloqueo de acción)*

Relacionado con la pregunta:  
¿Has evitado aplicar a oportunidades profesionales porque pensaste que no eras lo suficientemente buena?

**Descripción**

El miedo a no ser suficiente lleva a evitar oportunidades antes de intentarlo, limitando el crecimiento profesional.

---

### 4. Nudo de la presión económica  
*(Autonomía limitada)*

Relacionado con la pregunta:  
¿Sientes que la presión económica limita tu capacidad de buscar oportunidades que valoren tu talento?

**Descripción**

La necesidad económica condiciona las decisiones profesionales y reduce la capacidad de elegir oportunidades alineadas con el verdadero potencial.

---

### 5. Nudo de la aceptación por necesidad  
*(Violencia económica silenciosa)*

Relacionado con la pregunta:  
¿Has considerado o aceptado oportunidades laborales por necesidad económica aunque no reflejen tu verdadero valor?

**Descripción**

Las decisiones laborales se toman desde la urgencia económica, lo que puede llevar a aceptar condiciones o roles por debajo de las capacidades reales.

---

## 3. Lógica de clasificación

La clasificación del juego se basa en un modelo simple de puntaje. Cada una de las 5 preguntas está asociada a un nudo específico del síndrome del impostor. La respuesta de la usuaria indica el nivel de presencia de ese nudo.

---

### Escala de respuesta sugerida

Cada pregunta puede responderse con una escala de 4 niveles:

- Nunca = 0 puntos  
- A veces = 1 punto  
- Frecuentemente = 2 puntos  
- Casi siempre = 3 puntos  

---

### Relación entre preguntas y nudos

- Pregunta 1 → Nudo de la desvalorización del logro  
- Pregunta 2 → Nudo de la duda constante  
- Pregunta 3 → Nudo de la evitación de oportunidades  
- Pregunta 4 → Nudo de la presión económica  
- Pregunta 5 → Nudo de la aceptación por necesidad  

---

### Regla de clasificación

1. Cada respuesta suma puntos únicamente al nudo asociado.  
2. Al finalizar, se comparan los puntajes de los 5 nudos.  
3. El nudo con mayor puntaje se considera el nudo principal de la usuaria.  
4. El segundo puntaje más alto puede registrarse como nudo secundario para enriquecer la recomendación final.

---

### Manejo de empates

Si dos nudos tienen el mismo puntaje más alto, se prioriza el nudo con mayor impacto sobre la autonomía económica:

1. Nudo de la aceptación por necesidad  
2. Nudo de la presión económica  
3. Nudo de la evitación de oportunidades  
4. Nudo de la duda constante  
5. Nudo de la desvalorización del logro  

Esto permite que, en caso de empate, el sistema priorice el nudo que tenga mayor impacto estructural en la toma de decisiones profesionales.

---

### Resultado esperado

El sistema entrega:

- nudo principal  
- posible nudo secundario  
- breve interpretación del bloqueo  
- recomendación accionable  

---

## 4. Recomendaciones — Acción

Cada nudo identificado genera una recomendación accionable que busca ayudar a la usuaria a recuperar claridad y avanzar hacia oportunidades alineadas con su potencial.

### Nudo de la desvalorización del logro

Acciones sugeridas:

- Identificar tres logros profesionales reales.  
- Reconocer las habilidades que hicieron posible esos logros.  
- Aplicar a una oportunidad que refleje esas habilidades.

---

### Nudo de la duda constante

Acciones sugeridas:

- Identificar una habilidad clave que ya posees.  
- Buscar una oportunidad donde esa habilidad pueda aplicarse.  
- Tomar una acción pequeña esta semana (aplicar, iniciar conversación, enviar portafolio).

---

### Nudo de la evitación de oportunidades

Acciones sugeridas:

- Identificar una oportunidad que hayas evitado.  
- Revisar objetivamente los requisitos y tus habilidades.  
- Intentar aplicar o explorarla sin esperar perfección.

---

### Nudo de la presión económica

Acciones sugeridas:

- Identificar opciones que permitan generar ingresos mientras se fortalece el desarrollo profesional.  
- Explorar oportunidades de capacitación o transición laboral.  
- Priorizar acciones que aumenten la autonomía económica.

---

### Nudo de la aceptación por necesidad

Acciones sugeridas:

- Reconocer el valor real de tus habilidades.  
- Buscar oportunidades que se acerquen más a ese valor.  
- Diseñar un plan de transición que permita mejorar las condiciones actuales.

  
