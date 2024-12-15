# Guía del Proyecto: El Club del Trip

## 1. Introducción al Proyecto
El Club del Trip es un blog diseñado para compartir historias, reglas y elementos de un club único y especial. Este proyecto está construido con **HTML**, **CSS** y **JavaScript puro**, organizado de manera modular para facilitar su mantenimiento y escalabilidad.

### Objetivo del Proyecto
Crear un espacio visual atractivo y funcional donde los usuarios puedan explorar contenido y conectar con la esencia del club.

---

## 2. Estructura del Proyecto
El proyecto está organizado en carpetas para mantener la claridad y modularidad:


### Descripción de Carpetas
- **`index.html`**: Archivo principal que estructura la página del blog.
- **`css/`**: Contiene todos los estilos CSS divididos por funcionalidad.
- **`images/`**: Carpeta con todas las imágenes necesarias.
- **`fonts/`**: Fuentes personalizadas utilizadas en el proyecto.
- **`js/`**: Scripts JavaScript para interactividad.
- **`README.md`**: Información y guía para colaboradores.

---

## 3. Estilos y Diseño

### Colores Usados (Variables CSS)
Las variables de color están definidas en `base.css`:

```css
:root {
    --gris-100: #FAF9FA;
    --gris-200: #B59DBA;
    --gris-300: #201720;
    --primario-magenta: #FF00F6;
    --primario-purpura: #5A42BB;
    --primario-celeste: #82D8E0;
    --secundario-rosa: #FF84CE;
    --secundario-verde: #23D779;
    --secundario-azul: #3D7EFD;
    --secundario-amarillo: #E9BA24;
    --gradiente-logo: linear-gradient(
        90deg, 
        hsla(254, 44%, 55%, 1) 0%, 
        hsla(336, 77%, 61%, 1) 20%, 
        hsla(11, 89%, 57%, 1) 40%, 
        hsla(218, 84%, 56%, 1) 60%, 
        hsla(46, 82%, 53%, 1) 80%, 
        hsla(167, 57%, 33%, 1) 100%
    );
    --gradiente-claim: linear-gradient(
        90deg, 
        #7059bf 16%, 
        #e84e8c 32%, 
        #f35432 48%, 
        #3076ed 64%, 
        #e9ba24 80%, 
        #248470 96%
    );
}
body {
    font-family: 'Montserrat', sans-serif;
}
.boton-s {
    font-family: 'Anonymous Pro', monospace;
}
.titulo {
    font-family: 'Montserrat Alternates', sans-serif;
}
.decorativo {
    font-family: 'Bame', serif;
}
.boton-s {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 4px;
    border-radius: 4px;
    background: var(--primario-magenta);
    color: #201720;
    font-family: 'Anonymous Pro', monospace;
    font-size: 16px;
    transition: all 300ms ease-in-out;
}
.image-container {
    position: relative;
    border-radius: 12px;
    overflow: hidden;
}
.image-label {
    position: absolute;
    bottom: 8px;
    right: 8px;
    background: rgba(255, 0, 246, 0.6);
    color: #FFF;
    font-family: 'Anonymous Pro', sans-serif;
    padding: 4px 8px;
    border-radius: 4px;
}
.card-destacada.card-invertida {
    grid-template-columns: 1fr 2fr;
    margin: 0 auto;
    justify-content: center;
}
.card-destacada.card-invertida .imagen {
    order: -1;
}

¡Cópialo y pégalo en tu `README.md`! Si necesitas más ajustes, no dudes en pedírmelo 😊.
