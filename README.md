# Proyecto Rutas Leaflet

Este proyecto, **Proyecto-Rutas-Leaflet**, es una aplicación web desarrollada con JavaScript, HTML y CSS, diseñada para visualizar rutas y gestionar información de vehículos y conductores usando mapas interactivos con la librería open source [Leaflet.js](https://github.com/Leaflet/Leaflet).

## Características principales

- **Visualización de rutas:** Muestra rutas geográficas sobre un mapa interactivo utilizando Leaflet.
- **Gestión de vehículos y conductores:** Usa archivos JSON para los datos de vehículos (`vehiculos.json`) y conductores (`conductores.json`).
- **Cálculo y visualización de rutas:** Administra rutas específicas mediante `rutas.json`.
- **Componentes modulares:** Código modular en archivos JS independientes para rutas (`ruta.js`), conductores (`conductor.js`), vehículos (`vehiculo.js`) y lógica general (`scripts.js`).
- **Interfaz amigable:** Diseño visual basado en HTML (`index.html`, `mapa.html`) y CSS (`estilos.css`).
- **Asincronía y almacenamiento local:** Carga de datos desde archivos JSON externos para modularidad y flexibilidad.

## Estructura del proyecto

| Archivo / Carpeta        | Descripción                                                                    |
|--------------------------|--------------------------------------------------------------------------------|
| `index.html`             | Página principal de la aplicación                                              |
| `mapa.html`              | Página dedicada al mapa interactivo                                            |
| `conductor.js`           | Lógica para gestionar los conductores                                          |
| `vehiculo.js`            | Lógica para gestión de vehículos                                               |
| `ruta.js`                | Lógica para manipular y visualizar rutas                                       |
| `scripts.js`             | Código general y controlador de la aplicación                                  |
| `vehiculos.json`         | Base de datos local de vehículos                                               |
| `conductores.json`       | Base de datos local de conductores                                             |
| `rutas.json`             | Base de datos local de rutas                                                   |
| `images/`                | Carpeta para imágenes del proyecto                                             |
| `node_modules/`          | Dependencias de Node.js (si aplica)                                            |
| `package.json`           | Declaración de dependencias y scripts (opcional para Node.js)                  |
| `estilos.css`            | Hojas de estilo personalizadas                                                 |
| `server.js`              | Servidor básico para pruebas locales                                           |
| `nbproject/`             | Configuración del proyecto (NetBeans u otros entornos)                         |

## Instalación y ejecución

1. Clona el repositorio:
git clone https://github.com/MajestySuan/Proyecto-Rutas-Leaflet

2. Entra al directorio del proyecto:
cd Proyecto-Rutas-Leaflet

3. Para pruebas en servidor local (opcional, requiere Node.js):
 ```
    npm install
  ```
- Iniciar el servidor
  ```
    node server.js
  ```

4. Abre `index.html` o `mapa.html` en tu navegador para comenzar a usar la aplicación.

## Uso

- Visualiza mapas y rutas cargadas en el sistema.
- Gestiona la información de vehículos y conductores.
- Modifica los archivos JSON para agregar o actualizar datos fácilmente.

## Tecnologías utilizadas

- **HTML5** & **CSS3**
- **JavaScript** (Vanilla)
- **Leaflet.js**
- **Node.js** (opcional, para servidor local)
- **JSON** para almacenamiento y estructuración de datos

## Requisitos

- Navegador moderno compatible con ECMAScript 6
- (Opcional) Node.js para pruebas en servidor local

## Créditos

- Andrés Julián Barreto Puerto 
- Daniel Santiago Suancha 
- Juan David López Marcelo 

Desarrollado como proyecto de gestión y visualización de rutas utilizando mapas interactivos.

---
