<h1 align="center">ACTIVIDAD 3<br/>Explorando las herramientas de desarrollo</h1>


**🎯 Objetivo:**  
Familiarizarse con las **DevTools del navegador** para inspeccionar sitios web, analizar solicitudes, errores y estructuras HTML.

---

## ¿Cómo abrir las DevTools?

| Sistema operativo | Atajo para abrir DevTools           |
|-------------------|-------------------------------------|
| Windows|<kbd>F12</kbd> o <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>I</kbd>|
| Linux| <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>I</kbd>|
| macOS| <kbd>Cmd</kbd> + <kbd>Option</kbd> + <kbd>I</kbd>|

---

## 🛠️ DevTools

## 🔍 Pestañas principales a explorar

### 1. **Elementos (Elements)**
Permite ver y editar el HTML y CSS de cualquier elemento de la página.

<img src="https://developer.chrome.com/static/docs/devtools/overview/image/elements-panel-546127ed29eac.png?hl=es-419" alt="DevTools - Elements" width="600"/>


### 2. **Consola (Console)**
Muestra mensajes del navegador, errores de JavaScript y permite escribir comandos directamente.

<img src="https://developer.chrome.com/static/docs/devtools/console/api/image/a-subset-columns-a-tabl-d09038277395f.png" alt="DevTools - Console" width="600"/>


### 3. **Red (Network)**
Muestra todas las solicitudes HTTP/HTTPS que hace la página (APIs, imágenes, fuentes, etc.).

<img src="https://developer.chrome.com/static/docs/devtools/network/reference/image/the-total-size-transferr-144f510ae1e9c.png?hl=es-419" alt="DevTools - Network" width="600"/>


### 4. **Almacenamiento (Storage / Application)**
Permite ver cookies, Local Storage, Session Storage, IndexedDB y más.

<img src="https://developer.chrome.com/static/docs/devtools/storage/localstorage/image/viewing-value-the-selec-54e9bd2e4128c.png" alt="DevTools - Storage" width="600"/>

---

## 👨‍💻 Ejercicio práctico

1. Abrir el navegador y visitá una web pública, por ejemplo: [https://www.google.com](https://www.google.com)

2. Usá las DevTools para inspeccionar lo siguiente:
   - ✅ Una **solicitud HTTP** en la pestaña Network (por ejemplo: `/search`)
   - ✅ Un **error en consola**, si aparece (puede ser una advertencia o error de script)
   - ✅ El **HTML de un elemento**, como el campo de búsqueda

3. Tomá capturas de pantalla y guardalas para compartirlas o incluirlas en tu entrega.

### Screenshot

![Petición HTTP](screenshot/solicitud_http.png)  
*Figura: Solicitud HTTP en la pestaña Network.*

![Error en la consola](screenshot/mensajes-de-la-consola.png)  
*Figura: Vista de la consola mostrando errores y advertencia.*


![Examinando elementos](screenshot/mensajes-de-la-consola.png)  
*Figura: Examinando elementos.*

---

## Diagrama conceptual

```mermaid
flowchart TD
    A["🌐 Página Web"]
    A --> B["🧰 DevTools"]
    B --> C["🔎 Elementos"]
    B --> D["💬 Consola"]
    B --> E["🌐 Red (Network)"]
    B --> F["🗄️ Almacenamiento"]
```