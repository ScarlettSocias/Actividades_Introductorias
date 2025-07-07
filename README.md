# �� Actividades Introductorias – Bootcamp Web

Este README contiene 5 actividades diseñadas para introducir a los estudiantes al mundo del desarrollo web, partiendo desde los fundamentos de redes hasta las tecnologías modernas del stack completo.

---

## ✅ ACTIVIDAD 1 – ¿Esto es una web o una app web?

**�� Objetivo:** Comprender la diferencia entre un sitio web estático y una aplicación web interactiva.

**�� Instrucciones:**
## 1. Ejemplos de sitios web informativos:

- **Wikipedia** (enciclopedia libre)
- **CNN en Español** (portal de noticias)
- **Medium** (blogs y artículos)

## 2. Ejemplos de aplicaciones web:

- **Gmail** (cliente de correo interactivo)
- **Trello** (organización de tareas en tiempo real)
- **Spotify Web** (reproductor de música en línea)

## 3. Justificación:

Los sitios web informativos solo muestran contenido y no requieren que el usuario interactúe más allá de navegar o leer.

Las aplicaciones web permiten interacción directa, como enviar correos, mover tareas o reproducir música. Reaccionan en tiempo real y requieren una lógica de backend.

## 4. Reflexión:

Una aplicación web es interactiva porque responde a las acciones del usuario sin tener que recargar toda la página. Puede guardar datos, procesarlos y mostrarlos dinámicamente.

**Tecnologías detrás:** HTML, CSS, JavaScript (frontend), frameworks como React o Vue, y backend como Node.js, bases de datos como MongoDB o MySQL, y servidores web como Express o Apache.
---

## ✅ ACTIVIDAD 2 – Anatomía de una aplicación web moderna

**�� Objetivo:** Comprender los componentes principales de una app web (frontend, backend, base de datos).

**�� Instrucciones:**
## 1. Conceptos:

- **Frontend:** Parte visual de la app. Lo que ve el usuario (HTML, CSS, JS)
- **Backend:** Lógica detrás del sitio. Maneja peticiones, seguridad y conexión con la base de datos
- **Base de datos:** Guarda la información persistente (usuarios, tareas, mensajes, etc.)
  
2. Realiza un diagrama simple que muestre cómo se comunican entre sí.
3. diagrama:
graph TD
A[Usuario] --> B[Frontend]
B --> C[Backend]
C --> D[Base de datos]
https://www.mermaidchart.com/app/projects/911306ec-a315-415d-8c62-04ead153093f/diagrams/f03cfcfc-6bed-4d33-a750-89364b1c681a/version/v0.1/edit
---

## ✅ ACTIVIDAD 3 – Explorando las herramientas de desarrollo

**�� Objetivo:** Familiarizarse con las DevTools del navegador.

**�� Instrucciones:**
1. Investiga cómo abrir DevTools en tu sistema operativo:
   - **Opera:** `Ctrl + Shift + C`
2. Explora las siguientes pestañas:
   - Elementos
   - Consola
   - Red (Network)
   - Almacenamiento (Storage)
3. Abre una web (ej: google.com), inspecciona y captura:
   - Una solicitud HTTP
   - ![image](https://github.com/user-attachments/assets/4252c18b-c6b9-496a-b5c0-fe588e4f489b)
   - Un error en consola (si aparece)
   - ![image](https://github.com/user-attachments/assets/dec26763-2b05-4cfe-96f1-ab1ff6825145)
   - El HTML de un elemento
   - ![image](https://github.com/user-attachments/assets/7607431b-1c84-4e70-b0e7-7772a7985725)
---

## ✅ ACTIVIDAD 4 – Soy nuevo y aprendí Java… ¿y ahora qué con HTML, CSS y JS?

**�� Objetivo:** Dar una primera mirada sencilla a HTML, CSS y JavaScript.

**�� Instrucciones:**
## 1. ¿Qué hace cada tecnología?

- **HTML (HyperText Markup Language):** estructura el contenido (títulos, párrafos, botones)
- **CSS (Cascading Style Sheets):** da estilos visuales (colores, fuentes, tamaños)
- **JavaScript:** permite interacción (eventos, animaciones, peticiones, validaciones)

## 2. Java vs JavaScript:

| Característica | Java | JavaScript |
|----------------|------|------------|
| Tipo | Lenguaje compilado | Lenguaje interpretado |
| Entorno | General (apps, backend) | Web (navegadores, frontend) |
| Sintaxis | Similar en algunas cosas | Pero son tecnologías distintas |
| Uso | Backend, apps móviles/escritorio | Frontend dinámico de sitios web |

## 3. Mini README personal:

### Tecnologías Web: HTML, CSS y JavaScript

Estas tres tecnologías son la base del desarrollo web:

- **HTML:** define la estructura del contenido. Ejemplo:
  ```html
  <h1>Hola Mundo</h1>
  <p>Este es mi primer sitio web</p>
  ```

- **CSS:** da estilo a los elementos. Ejemplo:
  ```css
  h1 {
    color: blue;
    font-size: 32px;
  }
  ```

- **JavaScript:** agrega interacción. Ejemplo:
  ```javascript
  document.querySelector("h1").onclick = () => alert("¡Hola desde JS!");
  ```
