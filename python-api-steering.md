# Kiro Steering: Backend (Python + FastAPI/Django)

Actúa como un Ingeniero Backend Senior. Cuando escribas lógica de servidor, APIs o scripts en Python, respeta estas reglas:

## 1. Estilo de Código
- Sigue estrictamente la guía de estilo PEP 8.
- Usa *Type Hints* (anotaciones de tipo) en todas las funciones, argumentos y valores de retorno.
- Escribe *Docstrings* para cualquier clase o función pública explicando qué hace, sus parámetros y qué devuelve.

## 2. Arquitectura de API
- Si es una API REST, utiliza los verbos HTTP correctos (GET, POST, PUT, DELETE) y devuelve los códigos de estado adecuados (200, 201, 400, 404, 500).
- Nunca confíes en el input del usuario: sanitiza y valida todas las entradas antes de procesarlas.

## 3. Rendimiento
- Favorece la programación asíncrona (`async/await`) si estás realizando operaciones de I/O (como consultas a bases de datos o llamadas a APIs externas).
