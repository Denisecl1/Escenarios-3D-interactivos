# 🌲 3D Forest FPS Environment - Three.js

Un ambiente virtual interactivo en 3D ejecutado directamente en el navegador web. Este proyecto implementa controles en primera persona (FPS), físicas de colisión y renderizado de modelos 3D optimizados utilizando la librería WebGL de Three.js.

## ✨ Características Principales

* **🎮 Controles FPS Completos:** Soporte para teclado (WASD) para movimiento, mouse para control de cámara y rotación, y barra espaciadora para salto.
* **🗺️ Renderizado de Modelos Externos:** Carga e integración de un diorama 3D completo en formato `.glb` (GLTF).
* **🧱 Físicas y Colisiones (Octree):** Detección de colisiones precisa entre el jugador (cápsula) y la geometría del terreno para evitar caídas a través del suelo.
* **🚧 Límites de Mapa Personalizados:** Implementación de "paredes invisibles" para delimitar la zona de juego y mantener al jugador dentro del escenario de forma fluida.
* **⚡ Optimización de Rendimiento:** Ajuste de pasos de renderizado por fotograma y desactivación de sombras dinámicas innecesarias para garantizar una experiencia fluida.

## 🚀 Cómo ejecutar este proyecto localmente

Debido a las políticas de seguridad del navegador (CORS) al cargar archivos 3D locales, este proyecto requiere un servidor web local para funcionar.

1. Clona este repositorio:
   ```bash
   git clone [https://github.com/tu-usuario/nombre-del-repo.git](https://github.com/tu-usuario/nombre-del-repo.git)


   Abre la carpeta del proyecto en tu editor de código (ej. Visual Studio Code).

Inicia un servidor local. Si usas VS Code, puedes instalar la extensión Live Server y hacer clic en "Go Live".

¡Disfruta explorando el escenario!

🛠️ Tecnologías Utilizadas
HTML5 / CSS3: Estructura y estilos básicos.

JavaScript (ES6): Lógica del sistema y físicas.

Three.js: Librería principal para el renderizado WebGL.

Complementos: GLTFLoader, Octree, Capsule.

## ✨ Créditos
Desarrollo y Lógica: Diana Denise Campos Lozano - Estudiante de Ingeniería en TIC.

Modelo 3D: Diagrama de bosque descargado desde Sketchfab.

Base FPS: Proyecto inspirado en los ejemplos oficiales de Three.js.
