<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=12314A&height=200&section=header&text=Miguel%20Ugarte&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Desarrollador%20junior%20%C2%B7%20Automatizaci%C3%B3n%20con%20n8n%20e%20IA&descSize=18&descAlignY=60" alt="Miguel Ugarte" />

<div align="center">

<a href="https://github.com/miguelugartedev">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=Poppins&weight=500&size=20&duration=3000&pause=1000&color=E6EDF3&center=true&vCenter=true&width=720&height=40&lines=Agentes+conversacionales+con+memoria+propia;Flujos+de+automatizaci%C3%B3n+con+n8n;Pruebo+y+mido+antes+de+entregar" />
    <source media="(prefers-color-scheme: light)" srcset="https://readme-typing-svg.demolab.com?font=Poppins&weight=500&size=20&duration=3000&pause=1000&color=12314A&center=true&vCenter=true&width=720&height=40&lines=Agentes+conversacionales+con+memoria+propia;Flujos+de+automatizaci%C3%B3n+con+n8n;Pruebo+y+mido+antes+de+entregar" />
    <img alt="Agentes conversacionales con memoria propia, flujos con n8n, pruebo y mido antes de entregar" src="https://readme-typing-svg.demolab.com?font=Poppins&weight=500&size=20&duration=3000&pause=1000&color=12314A&center=true&vCenter=true&width=720&height=40&lines=Agentes+conversacionales+con+memoria+propia;Flujos+de+automatizaci%C3%B3n+con+n8n;Pruebo+y+mido+antes+de+entregar" />
  </picture>
</a>

<br>

![Ubicación](https://img.shields.io/badge/Nicaragua-12314A?style=for-the-badge)
![Formación](https://img.shields.io/badge/Ingenier%C3%ADa_en_Computaci%C3%B3n-UNI-12314A?style=for-the-badge)
![Estado](https://img.shields.io/badge/Abierto_a_oportunidades-12314A?style=for-the-badge)

</div>

---

## Perfil

> Construyo agentes conversacionales y flujos de automatización conectados a bases de datos y APIs. Me importa que lo que entrego funcione bien: **pruebo, mido y busco fallos antes de que lleguen al usuario.**

Estoy en mi cuarto año de Ingeniería en Computación en la Universidad Nacional de Ingeniería (UNI) y busco mi primera oportunidad profesional en desarrollo o automatización, ya sea en una empresa o como freelance.

---

## Proyecto destacado

### Agente de IA para consulta de eventos

Agente conversacional que responde consultas sobre los eventos de una comunidad. Lo desarrollé de punta a punta para un cliente en Costa Rica (trabajo remoto) y se entrega como un webhook listo para integrarse en sus canales.

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![OpenRouter](https://img.shields.io/badge/OpenRouter-6467F2?style=flat-square)
![Bruno](https://img.shields.io/badge/Bruno-E26E40?style=flat-square)

#### Cómo piensa el agente

```mermaid
flowchart LR
    A([Pregunta del usuario]) --> B{Clasificar<br/>categoría}
    B --> C[Reglas exactas<br/>según la categoría]
    C --> D[Prompt corto y preciso]
    M[(Memoria propia<br/>en PostgreSQL)] <--> E
    D --> E[Agente de IA<br/>vía OpenRouter]
    F[(Eventos<br/>API oficial)] --> E
    E --> G{¿Datos<br/>contradictorios?}
    G -- No --> H([Respuesta])
    G -- Sí --> I([Avisa y pide confirmar<br/>con la organización])
```

#### Qué resolví

| Tema | Detalle |
|---|---|
| **Latencia y tokens** | Clasifico cada pregunta por categoría y le paso al modelo solo las reglas que necesita, para que el prompt sea corto y preciso. |
| **Memoria propia** | Diseñé una tabla en PostgreSQL para la memoria de la conversación, porque el nodo por defecto de n8n se quedaba corto. |
| **Datos inconsistentes** | La API oficial a veces se contradice (un precio en un campo y otro distinto en la descripción). El agente lo detecta y le indica al usuario que confirme con la organización. |
| **Pruebas** | Unas 140 preguntas en 15 categorías, y pruebas de las respuestas de la API con Bruno. |
| **Revisión humana** | Prototipé una validación automática de respuestas, pero la revisión final la hago yo, porque es más confiable. |

<details>
<summary><b>Ver las categorías de prueba</b></summary>
<br>

- Básicas, intermedias y avanzadas
- Paráfrasis y jerga con errores de escritura
- Otros idiomas
- Fechas
- Datos del catálogo
- Conteo y filtros por precio
- Preguntas combinadas
- Preguntas de seguimiento (con memoria)
- Conversación libre
- Límites de seguridad
- Trampas y robustez

</details>

---

## Forma de trabajo

| 1 | 2 | 3 | 4 |
|:---:|:---:|:---:|:---:|
| **Entender**<br/>el problema real antes de automatizar | **Construir**<br/>la versión más simple que funcione | **Probar**<br/>con casos normales y con casos que intentan romperla | **Medir**<br/>latencia y consumo, y optimizar lo que sobra |

---

## Stack

<div align="center">

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![OpenRouter](https://img.shields.io/badge/OpenRouter-6467F2?style=for-the-badge)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Fedora](https://img.shields.io/badge/Fedora-51A2DA?style=for-the-badge&logo=fedora&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Bruno](https://img.shields.io/badge/Bruno-E26E40?style=for-the-badge)

**Desarrollo web**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-404040?style=for-the-badge&logo=express&logoColor=white)

**Integraciones**

![Google Calendar](https://img.shields.io/badge/Google_Calendar-4285F4?style=for-the-badge&logo=googlecalendar&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)
![HTTP](https://img.shields.io/badge/HTTP_Request-404040?style=for-the-badge)

</div>

---

## Explorando

Herramientas que conozco a nivel básico y sigo practicando.

![Godot](https://img.shields.io/badge/Godot-478CBF?style=for-the-badge&logo=godotengine&logoColor=white)
![Blender](https://img.shields.io/badge/Blender-E87D0D?style=for-the-badge&logo=blender&logoColor=white)

---

## Actividad

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/miguelugartedev/miguelugartedev/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/miguelugartedev/miguelugartedev/output/github-snake.svg" />
    <img alt="Gráfica de contribuciones animada" src="https://raw.githubusercontent.com/miguelugartedev/miguelugartedev/output/github-snake.svg" />
  </picture>
</div>

---

## Contacto

Si tienes un proceso que se pueda automatizar o buscas a alguien para tu equipo, escríbeme.

<div align="center">

<a href="mailto:miguelugartedev@gmail.com">
  <img src="https://img.shields.io/badge/miguelugartedev%40gmail.com-12314A?style=for-the-badge&logo=gmail&logoColor=white" alt="Correo" />
</a>

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=12314A&height=100&section=footer" alt="" />
