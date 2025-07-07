# ✅ ACTIVIDAD 1 – ¿Esto es una web o una app web?

**🎯 Objetivo:**  
Comprender la diferencia entre un **sitio web estático** y una **aplicación web interactiva**, a partir de ejemplos, análisis y reflexión sobre tecnologías web modernas.

---

## 1. Ejemplos de sitios web informativos (estáticos)

1. [Wikipedia](https://www.wikipedia.org)  
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/63/Wikipedia-logo.png" alt="logo" width="100"/>

   ➤ Sitio colaborativo de artículos informativos que no requieren interacción avanzada del usuario.

2. [BBC News](https://www.bbc.com/news)  
    <img src="https://images.icon-icons.com/70/PNG/512/bbc_news_14062.png" alt="logo" width="100"/>

   ➤ Portal de noticias que presenta información actualizada, pero de forma principalmente pasiva.

3. [MDN Web Docs](https://developer.mozilla.org)  
    <img src="https://upload.wikimedia.org/wikipedia/commons/7/70/Firefox_Focus_2021_Icon.png" alt="logo" width="100"/>
  
   ➤ Recurso educativo que ofrece documentación técnica. Aunque tiene buscador, no requiere login ni procesos dinámicos.

---

## 2. Ejemplos de aplicaciones web (interactivas)

1. [Figma](https://www.figma.com)  
    <img src="https://upload.wikimedia.org/wikipedia/commons/3/33/Figma-logo.svg" alt="logo" width="100"/>

   ➤ App colaborativa para diseño de interfaces. Permite edición en tiempo real, autenticación, y guardado dinámico.

2. [Notion](https://www.notion.so)  
    <img src="https://upload.wikimedia.org/wikipedia/commons/4/45/Notion_app_logo.png" alt="logo" width="100"/>  

   ➤ Aplicación de organización personal/empresarial. Guarda contenido en bases de datos y permite personalización.

3. [Canva Web](https://www.canva.com)  
    <img src="https://www.e-monsite.com/medias/images/canva-logo.png" alt="logo" width="100"/>  

   ➤ Plataforma de diseño gráfico online con carga y edición multimedia, integración con APIs y soporte en la nube.

---

## 3. ¿Por qué esta clasificación?

| Tipo              | Características clave                                              |
|-------------------|---------------------------------------------------------------------|
| **Sitios web**    | Contenido mayormente estático, lectura pasiva, sin login ni lógica compleja.|
| **Apps web**      | Requieren backend, manejo de estados, autenticación, lógica de negocio, guardado en tiempo real, etc. |

---

## 4. Reflexión: ¿Qué hace que una app web sea interactiva?

Una aplicación web interactiva:

- [x] Permite **interacción directa** con el contenido  
- [x] Cambia su estado sin recargar la página (SPA, AJAX)  
- [x] Usa lógica en frontend y backend  
- [x] Puede integrarse con servicios externos o APIs  
- [x] Maneja autenticación y roles de usuario  
- [x] Guarda datos en **bases de datos** y los recupera en tiempo real

### 🧪 Tecnologías detrás:

- **Frontend**: JavaScript, React, Vue, Angular  
- **Backend**: Node.js, Spring Boot, Django, Laravel  
- **Bases de datos**: PostgreSQL, MongoDB, Firebase  
- **Otros**: APIs REST, WebSockets, OAuth, JWT, GraphQL

---

## 📊 Diagrama comparativo (Mermaid)

```mermaid
flowchart LR
  A[Usuario] -->|Lee contenido| B[📰 Sitio web informativo]
  A -->|Interactúa, guarda, edita| C[🛠️ Aplicación web]

  B -->|HTML/CSS| D1[Frontend estático]
  C -->|JS + APIs| D2[Frontend dinámico]
  C -->|Petición HTTP| E[Backend + Base de datos]
```