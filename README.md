<h1 align="center">Miguel Ugarte</h1>

<p align="center">
  Desarrollador junior · Automatización con n8n e IA<br>
  Estudiante de Ingeniería en Computación · Nicaragua
</p>

<p align="center">
  <a href="mailto:miguelugartedev@gmail.com">miguelugartedev@gmail.com</a>
</p>

---

## Sobre mí

Construyo agentes conversacionales y flujos de automatización conectados a bases de datos y APIs. Me importa que lo que entrego funcione bien: pruebo, mido y busco fallos antes de que lleguen al usuario.

Estoy en mi cuarto año de Ingeniería en Computación en la Universidad Nacional de Ingeniería (UNI) y busco mi primera oportunidad profesional en desarrollo o automatización, ya sea en una empresa o como freelance.

---

## Proyecto destacado

### Agente de IA para consulta de eventos

Agente conversacional que responde consultas sobre los eventos de una comunidad, desarrollado de punta a punta para un cliente en Costa Rica (trabajo remoto). Se entrega como un webhook listo para integrarse en los canales del cliente.

**Stack:** n8n · PostgreSQL · OpenRouter

**Qué resolví**

- **Latencia y tokens:** clasifico cada pregunta por categoría y le paso al modelo solo las reglas que necesita, para que el prompt sea corto y preciso.
- **Memoria propia:** diseñé una tabla en PostgreSQL para la memoria de la conversación, porque el nodo por defecto de n8n se quedaba corto.
- **Datos inconsistentes:** la API oficial a veces se contradice (por ejemplo, un precio en un campo y otro distinto en la descripción). El agente detecta esos casos y le indica al usuario que confirme con la organización.
- **Pruebas:** diseñé unas 140 preguntas en 15 categorías (paráfrasis, errores de escritura, otros idiomas, fechas, filtros por precio, preguntas de seguimiento con memoria, límites de seguridad y robustez) y probé las respuestas de la API con Bruno.
- **Revisión humana:** prototipé una validación automática de respuestas, pero la revisión final la sigo haciendo yo, porque es más confiable.

---

## Cómo trabajo

1. Entiendo el problema real antes de automatizar.
2. Construyo la versión más simple que funcione.
3. La pruebo con casos normales y con casos que intentan romperla.
4. Mido latencia y consumo, y optimizo lo que sobra.

---

## Stack

<p>
  <img src="https://img.shields.io/badge/n8n-1F1F1F?style=flat-square&logo=n8n&logoColor=white" alt="n8n" />
  <img src="https://img.shields.io/badge/OpenRouter-1F1F1F?style=flat-square&logoColor=white" alt="OpenRouter" />
  <img src="https://img.shields.io/badge/PostgreSQL-1F1F1F?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/MongoDB-1F1F1F?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/Bruno-1F1F1F?style=flat-square&logo=bruno&logoColor=white" alt="Bruno" />
  <img src="https://img.shields.io/badge/Docker-1F1F1F?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Linux-1F1F1F?style=flat-square&logo=linux&logoColor=white" alt="Linux" />
  <img src="https://img.shields.io/badge/Git-1F1F1F?style=flat-square&logo=git&logoColor=white" alt="Git" />
</p>

**Desarrollo web**

<p>
  <img src="https://img.shields.io/badge/JavaScript-1F1F1F?style=flat-square&logo=javascript&logoColor=white" alt="JavaScript" />
  <img src="https://img.shields.io/badge/TypeScript-1F1F1F?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React-1F1F1F?style=flat-square&logo=react&logoColor=white" alt="React" />
  <img src="https://img.shields.io/badge/Node.js-1F1F1F?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express-1F1F1F?style=flat-square&logo=express&logoColor=white" alt="Express" />
</p>

**Integraciones:** HTTP Request, Google Calendar, Telegram

---

## Explorando

Herramientas que conozco a nivel básico y sigo practicando: **Godot** y **Blender**.

---

## Contacto

Si tienes un proceso que se pueda automatizar o buscas a alguien para tu equipo, escríbeme a [miguelugartedev@gmail.com](mailto:miguelugartedev@gmail.com).
