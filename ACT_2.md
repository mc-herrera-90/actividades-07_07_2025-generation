<h1 align="center">ACTIVIDAD 2<br/>Anatomía de una aplicación web moderna</h1>


**🎯 Objetivo:**  
Comprender los **componentes principales de una aplicación web moderna**: frontend, backend y base de datos, así como su comunicación entre sí.

---

##  Componentes principales

### 1. Frontend (Cliente)
Es la interfaz que ve y con la que interactúa el usuario.  
Suele estar construida con tecnologías como **HTML, CSS, JavaScript** y frameworks modernos como **React**, **Vue.js** o **Angular**.

### 2. Backend (Servidor)
Es la lógica del sistema. Recibe peticiones del frontend, procesa datos, ejecuta reglas de negocio y responde con información.  
Se construye con lenguajes como **Java (Spring Boot)**, **Node.js**, **Python (Django)**, entre otros.

### 3. Base de datos
Es el sistema que **almacena y organiza la información**. Puede ser relacional (como **MySQL, PostgreSQL**) o NoSQL (como **MongoDB**).

---

## Comunicación entre componentes

A continuación se muestra un diagrama que representa cómo se conectan los tres componentes principales de una aplicación web moderna.

```mermaid
graph TD
    A[👨‍💻 Usuario]
    A --> B[🌐 Frontend (React/Vue)]
    B --> C[🛠️ Backend (API REST - Spring Boot)]
    C --> D[🗄️ Base de datos (MySQL/PostgreSQL)]
```


