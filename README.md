# Amigo Secreto
Esta es una aplicación web interactiva diseñada para elegir un "Amigo Secreto". El proyecto pone a prueba algunas habilidades en lógica de programación y DOM, permitiéndote agregar amigos a una lista y, mediante un sorteo aleatorio, elegir a uno de ellos.

## Características

- **Agregar Amigos:** Ingresa el nombre de tus amigos y añádelos a la lista.
- **Actualización Dinámica:** La lista se actualiza cada vez que se añade un nuevo nombre.
- **Sorteo Aleatorio:** Se realiza un sorteo para elegir de forma aleatoria un "amigo secreto" de la lista.

## Tecnologías Utilizadas

- **HTML5:** Estructura y semántica de la página.
- **CSS3:** Estilos y diseño visual, utilizando variables CSS para una fácil personalización.
- **JavaScript:** Lógica de la aplicación, manipulación del DOM y manejo de eventos.

## Estructura del Proyecto

```
├── index.html         # Archivo principal HTML de la aplicación
├── style.css          # Estilos y diseño visual de la aplicación
├── app.js             # Lógica en JavaScript para agregar amigos y sortear
└── assets/            # Recursos gráficos (imágenes e íconos)
```

### Descripción de Archivos

- **index.html:**  
  Define la estructura básica del sitio, incluye las secciones principales y enlaza los recursos CSS y JavaScript. Además, se integra la tipografía desde Google Fonts para mejorar la estética visual.

- **style.css:**  
  Contiene las reglas de estilo, utiliza variables CSS para definir la paleta de colores, tipografía y estilos para botones, listas y secciones. La estructura CSS está organizada para lograr un diseño responsivo y moderno.

- **app.js:**  
  Implementa la lógica del sorteo. Se encarga de:  
  - **agregarAmigo():** Valida y agrega nuevos amigos a la lista.
  - **actualizarLista():** Actualiza dinámicamente el listado de nombres en el DOM.
  - **sortearAmigo():** Selecciona al azar un amigo de la lista para realizar el sorteo.

### Ejemplo
![image](https://github.com/user-attachments/assets/96eebef1-ded9-4513-a542-9dc49d3f6acd)

## Instalación y Uso

1. **Clonar el Repositorio:**

   ```bash
   git clone https://github.com/tu_usuario/amigo-secreto.git
   ```

2. **Abrir el Proyecto:**

   Abre el archivo `index.html` en tu navegador preferido.

3. **Uso de la Aplicación:**

   - Escribe el nombre de un amigo en el campo de texto.
   - Haz clic en el botón **"Añadir"** para agregar el nombre a la lista.
   - Una vez agregados todos los amigos, haz clic en **"Sortear amigo"** para elegir al azar un "amigo secreto".
