## Controles de seguridad del MVP

GuardianAI protege el flujo mediante:

- validación por lista blanca de respuestas
- control de longitud de entrada
- detección básica de prompt injection
- construcción segura del input hacia el LLM
- salida solo en texto plano
- control básico de abuso a nivel de frontend y flujo

Para publicación pública por varios días, se recomienda complementar con CAPTCHA o Turnstile y límites adicionales por IP.
