# SIN-NUDO AI by Nana
Proyecto creado durante la hackathon #SheShips en el contexto del 8M. Construyendo tecnología con propósito 💗

![SIN-NUDO AI](logo/demo.png)

## Problema

Muchas mujeres enfrentan el síndrome del impostor: una barrera invisible que las lleva a dudar de sí mismas incluso cuando tienen todo el potencial para lograrlo. Cuando esta duda se combina con el desempleo o la falta de oportunidades, puede generar dependencia económica y limitar la autonomía para tomar decisiones profesionales reales, llevando a aceptar caminos basados en la urgencia del momento y no en el verdadero valor de sus habilidades.

Este contexto se conecta con problemáticas estructurales visibilizadas por el 8M, como las brechas profesionales y la desigualdad económica. 

Así, el talento de muchas mujeres queda invisible no por falta de capacidad, sino por no contar con herramientas que las ayuden a reconocerlo y transformarlo en oportunidades.

---

## Solución

*****The product is a short interactive experience that helps women identify internal blocks related to impostor syndrome and receive an actionable recommendation to move forward professionally.

SIN-NUDO AI es una herramienta educativa que ayuda a identificar bloqueos invisibles como la duda o el síndrome del impostor para transformarlos en apertura de caminos y oportunidades.

A través de un juego tipo test, la aplicación realiza preguntas que permiten identificar patrones de duda, reconocer habilidades y detectar posibles barreras internas.

Con base en estas respuestas, el sistema sugiere acciones concretas, cursos y caminos posibles para activar oportunidades profesionales o económicas, ayudando a que las mujeres transformen sus habilidades en pasos reales hacia su autonomía y desarrollo.

---

## Arquitectura del MVP 

Frontend  
v0 (interfaz visual de la aplicación/Form) - Pending

Backend  
n8n workflow (orquestación de flujos) - OK

Guardian AI (validation) - OK

IA  
Featherless AI (análisis de respuestas) - OK

Seguridad  
GuardianAI capa básica de validación y protección del flujo antes de la llamada al LLM.-OK

--Controles Seguridad
- validación estricta de entradas permitidas
- bloqueo básico de patrones sospechosos
- prevención de doble envío desde el frontend
- salida segura en texto plano
- consumo controlado del modelo para evitar abuso y costos innecesarios


Salida-OK
Acciòn(Recomendaciòn)

---

## Estado del proyecto

En desarrollo de MVP by Nana.

