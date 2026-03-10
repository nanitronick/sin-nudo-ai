# SIN-NUDO AI by Nana


Un asistente basado en IA diseñado para ayudar a identificar y desafiar el síndrome del impostor, una barrera invisible que limita el desarrollo profesional de muchas mujeres.

A través de un juego breve de preguntas, el sistema analiza patrones de duda o autosabotaje y entrega recomendaciones orientadas al aprendizaje, empoderamiento y apertura de oportunidades profesionales.

El proyecto fue desarrollado durante la hackathon #SheShips en el contexto del 8M, utilizando herramientas de IA y un flujo de orquestación que integra interfaz visual, análisis mediante LLM y una capa inicial de seguridad llamada GuardianAI.

![SIN-NUDO AI](logo/demo.png)

---

## Problema

Muchas mujeres enfrentan el síndrome del impostor: una barrera invisible que las lleva a dudar de sí mismas incluso cuando tienen todo el potencial para lograrlo. Cuando esta duda se combina con el desempleo o la falta de oportunidades, puede generar dependencia económica y limitar la autonomía para tomar decisiones profesionales reales, llevando a aceptar caminos basados en la urgencia del momento y no en el verdadero valor de sus habilidades.

Este contexto se conecta con problemáticas estructurales visibilizadas por el 8M, como las brechas profesionales y la desigualdad económica.

Así, el talento de muchas mujeres queda invisible no por falta de capacidad, sino por no contar con herramientas que las ayuden a reconocerlo y transformarlo en oportunidades.

---

## Solución

SIN-NUDO AI es un proyecto que utiliza IA para desafiar el síndrome del impostor, un fenómeno que limita a muchas personas y contribuye a brechas emocionales y profesionales, alineado con el contexto del 8M.

Funciona como un asistente interactivo que realiza preguntas para identificar patrones de autosabotaje o falta de confianza. A partir de las respuestas, genera un resumen del resultado y recomendaciones que ayudan a abrir caminos de aprendizaje, educación y empoderamiento femenino.

El MVP se presenta como un juego en el frontend que entrega el resultado del análisis. Como siguiente paso, se plantea implementar el backend en n8n y ampliar los controles del asistente Guardian que protege el sistema.

---

## Demo

El MVP incluye una experiencia interactiva breve donde la usuaria responde un test de preguntas diseñado para identificar posibles patrones asociados al síndrome del impostor.

A partir de las respuestas, el sistema genera un resultado que resume el tipo de bloqueo identificado y entrega recomendaciones orientadas al aprendizaje, desarrollo profesional o exploración de oportunidades.

El demo muestra:

- interfaz del juego tipo test  
- ejemplo de respuestas del usuario  
- resultado generado con recomendaciones  

Video demo incluido en la entrega del proyecto.

---

## Tecnologías utilizadas

- v0 → creación de la interfaz visual del MVP  
- n8n → orquestación de flujos del asistente  
- Featherless AI → análisis de respuestas mediante LLM  
- GuardianAI → capa inicial de validación y protección del flujo  
- GitHub → documentación y publicación del proyecto

---

## Arquitectura del MVP

Frontend (entrada usuario)  
v0 → interfaz visual donde la usuaria interactúa con el juego tipo test y envía sus respuestas.

↓

Backend  
n8n workflow → orquestación de los flujos que reciben las respuestas del formulario y gestionan el procesamiento del caso de uso.

↓

Guardian AI (protección)  
Capa inicial que valida el input recibido, revisa posibles patrones maliciosos o anómalos y protege el flujo antes de interactuar con el modelo de IA.

↓

LLM (consulta IA)  
El sistema consulta el modelo de lenguaje para analizar las respuestas del usuario e identificar posibles patrones asociados al síndrome del impostor.

↓

Seguridad  
GuardianAI aplica una validación básica del flujo antes de la llamada al LLM para asegurar el uso adecuado del sistema y evitar abusos.

↓

Salida  
Acción / recomendación → el sistema entrega un resumen del resultado identificado y sugiere recomendaciones que ayudan a desafiar esas barreras y abrir caminos de aprendizaje o desarrollo profesional.

---

## Estado del proyecto

MVP desarrollado como aplicación funcional en frontend durante la hackathon.
LLM Pipelina + Guardrail

Next step:

- implementar el flujo backend en n8n  
- ampliar los controles de seguridad del asistente Guardian  
- realizar pruebas controladas de amenazas en la entrada del sistema

Este es el primer paso de este caso de uso. Sin-Nudo AI busca identificar patrones asociados al síndrome del impostor, que en contextos como el desempleo pueden amplificarse. Esta base permitirá avanzar hacia Renacer AI, enfocado en la siguiente etapa: acompañar el proceso de tomar acción y reconstruir confianza.El objetivo no es reemplazar a profesionales de la salud o áreas asociadas, sino construirse como una IA segura 🔐, ética, legal y sostenible ♻️.

Proyecto:
https://devpost.com/software/sin-nudo-ai

APP MV1:
v0 - Pending publish

App MV2:
https://sin-nudoaibynana.lovable.app/
