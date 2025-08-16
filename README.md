# Explorador de Películas 🎬

¡Hola! Esta es una aplicación frontend en React donde puedes buscar películas, ver sus detalles y hasta enviar sugerencias.  

---

## 🔹 Funcionalidades

- Buscar películas por nombre.  
- Mostrar resultados en tarjetas con poster, título y año.  
- Ver detalle de cada película haciendo clic en la tarjeta.  
- Navegar entre secciones de la app (SPA).  
- Enviar sugerencias de películas mediante un formulario.  
- Consumir la [API de OMDb](http://www.omdbapi.com/) para obtener datos reales.  
- Compartir datos entre componentes usando Context API.  

---

## 💻 Cómo correr el proyecto

1. Clonar el repositorio:

```bash
git clone https://github.com/IxchelVe/proyecto-react.git

Entrar a la carpeta del proyecto:

cd proyecto-react


Instalar dependencias:

npm install


Crear un archivo .env en la raíz y agregar tu API key de OMDb:

VITE_OMDB_API_KEY="tu_api_key_aqui"


Correr la app en modo desarrollo:

npm run dev


Abrir en el navegador: normalmente http://localhost:5173/.

📂 Estructura del proyecto
src/
 ├─ componentes/      # Todos los componentes React (Buscador, ListaPeliculas, TarjetaPelicula, etc.)
 ├─ contexto/         # Context API para compartir datos
 ├─ servicios/        # Funciones para consumir la API
 ├─ App.jsx           # Componente principal con rutas
 └─ main.jsx          # Entrada de la app

⚙️ Tecnologías

React

Vite

Context API

React Router DOM

Axios

CSS / Tailwind (según estilo usado)


