# CineHub

## Problema

Los grupos de amigos en Colombia pierden tiempo y planes yendo de un lado a otro en WhatsApp tratando de ponerse de acuerdo sobre qué película ver, en qué cine y a qué hora. La información de las películas (horarios, cine, póster, calificación) se pierde entre los mensajes del chat, y no existe un solo lugar donde proponer un plan y ver quién realmente confirmó asistencia — así que los planes se van desarmando en silencio.

## Justificación de la aplicación web

1. Un grupo de WhatsApp no puede estructurar los datos de una película (póster, calificación, horarios, cine) — es solo texto que se desplaza, y los planes viejos quedan enterrados bajo mensajes nuevos.
2. Una hoja de cálculo no puede mostrar cartelera en tiempo real ni dejar que un amigo responda "Sí / Tal vez / No" a un plan — no tiene una vista interactiva y compartible.
3. Apps existentes como Cine Colombia o Cinemark permiten comprar boletas, pero no ayudan a que el grupo se ponga de acuerdo sobre *qué* película ver y *quién* realmente va a ir.
4. Un link de plan compartible permite que cualquier amigo invitado confirme asistencia con un solo toque, sin necesitar cuenta ni ser agregado a un chat grupal.

## Usuarios objetivo

Estudiantes universitarios y grupos de amigos en Colombia que quieren organizar una salida al cine juntos, pero les cuesta tomar una decisión y conseguir confirmaciones usando solo el chat.

## Historias de usuario

Formato: `As a [user type], I want to [action] so that [benefit].`

- As a user, I want to browse popular movies so that I can decide what to watch.
- As a user, I want to see showtimes and select a cinema, date, and hour so that I can build a plan around a specific screening.
- As a plan creator, I want to share a link to my movie plan so that my friends can see all the details without me repeating them.
- As an invited friend, I want to respond Yes / Maybe / No to a plan so that the organizer knows who is actually coming.

## Roles del equipo

| Integrante | GitHub | Rol |
|---|---|---|
| Samuel | [@samuraidm45-create](https://github.com/samuraidm45-create) | Frontend Developer — construye la interfaz, el `index.html` y la estructura visual de las pantallas de CineHub |
| Samuel David Ortiz Pico | [@samueldavidortizpico-hash](https://github.com/samueldavidortizpico-hash) | Backend Developer — lógica de la aplicación, datos de películas/funciones/planes, integración de funcionalidades |
| Juan Pablo Vanegas | [@juanpablovanegas](https://github.com/juanpablovanegas) | UI/UX & Documentación del Proyecto — wireframes en Figma, experiencia de usuario, y documentación del proyecto |

## MVP

**Debe funcionar:**

- Ver películas
- Ver el detalle de una película
- Ver funciones/horarios
- Seleccionar una función
- Crear un plan
- Mostrar el plan

## Extensión (opcional)

- Compartir el plan mediante un link real
- Sistema de cuentas
- Votación real de asistencia
- Persistencia en base de datos
- Compra de boletas

## Bitácora de IA

Usamos IA (Claude) para ayudar a convertir la conversación de planeación de nuestro equipo en WhatsApp — donde definimos el problema, el MVP y los roles — en el formato estructurado de README que pide esta tarea (planteamiento del problema, justificación de la app web, historias de usuario en el formato `As a [user type], I want to [action] so that [benefit]`).

Qué cambió: la IA organizó nuestras notas informales en las secciones y el formato específico que pide la rúbrica, tradujo el contenido al español (excepto las historias de usuario, que se dejaron en inglés porque la rúbrica exige ese formato literal), y redactó el planteamiento del problema y la justificación de forma más específica (por ejemplo, nombrando alternativas concretas como grupos de WhatsApp y apps de boletería existentes) en lugar de la descripción general que teníamos en el chat.

La idea de fondo, el alcance del MVP y la asignación de roles no cambiaron respecto a lo que el equipo acordó.