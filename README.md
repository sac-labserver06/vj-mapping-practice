# 🎨 VJ Mapping & Practice | Visuals, Arena Projects & OBS Automation

![Status](https://img.shields.io/badge/Status-Active_Repository-success)
![Focus](https://img.shields.io/badge/Focus-VJing_|_Python_|_Mapping-blueviolet)

Repositorio dedicado a la experimentación visual, proyectos base para **Resolume Arena**, plantillas de calibración de mapeo, scripts de automatización en Python para OBS Studio y recursos gráficos optimizados para eventos en vivo.

---

## 📂 Contenido del Repositorio

- [🎛️ Proyectos Base de Resolume Arena](#️-proyectos-base-de-resolume-arena)
- [📐 Plantillas de Mapeo de Prueba](#-plantillas-de-mapeo-de-prueba)
- [🐍 Scripts de Python para OBS Studio](#-scripts-de-python-para-obs-studio)
- [🎬 Fondos & Loops para Eventos](#-fondos--loops-para-eventos)

---

## 🎛️ Proyectos Base de Resolume Arena

Estructuras de composición preparadas para eventos en vivo, optimizadas para rendimiento en GPU y flujos multicapa.

| Proyecto / Archivo | Descripción | Formato / Versión |
| :--- | :--- | :--- |
| **`Base-Composition-FullHD.avc`** | Composición limpia con 4 capas principales, efectos de color globales y mapeo MIDI genérico configurado. | Resolume Arena 7+ |
| **`Advanced-Mapping-Rig.avc`** | Estructura avanzada utilizando *Advanced Output* para pantallas LED con recortes irregulares y salidas secundarias. | Resolume Arena 7+ |

> **💡 Consejo Pro:** Asegúrate de transcodificar todos tus clips visuales al códec **DXV3** de Resolume para garantizar reproducción fluida a 60 FPS sin sobrecargar el procesador.

---

## 📐 Plantillas de Mapeo de Prueba

Recursos esenciales para realizar pruebas de geometría, alineación de proyectores y calibración de pantallas LED antes de que comience el show.

* **`Test-Card-UV-Grid.png`**: Cuadrícula de prueba de alta resolución con patrones geométricos y colores primarios/secundarios para calibración de escala y distorsión trapezoidal (Keystone).
* **`Color-Bars-Calibration.mp4`**: Loop de prueba de barras de color y escala de grises para verificar niveles de brillo y contraste en proyectores y paneles LED.

---

## 🐍 Scripts de Python para OBS Studio

Automatizaciones y herramientas de control desarrolladas en Python para potenciar las capacidades de OBS Studio en transmisiones en vivo.

* **`obs-auto-switcher/`**: Script en Python utilizando `obs-websocket-py` para cambiar automáticamente entre escenas de fuentes NDI según eventos de temporizador o disparadores externos.
* **`stream-health-logger.py`**: Utilidad ligera para monitorear la tasa de cuadros perdidos (dropped frames) y la estabilidad de la conexión durante streams prolongados, guardando registros locales en CSV.

---

## 🎬 Fondos & Loops para Eventos

En esta sección comparto recursos visuales libres de derechos y de producción propia optimizados para VJs.

* **Estructura de resoluciones recomendadas:**
  * **Pantallas LED (Custom):** Diseñadas según la relación de aspecto del procesador (ej. NovaStar).
  * **Proyección Estándar:** 1920x1080 (Full HD) a 30 o 60 FPS.
* Puedes encontrar una selección de loops de prueba y fondos abstractos en la carpeta `/loops-preview/` de este repositorio.

---

<div align="center">
  <sub>Desarrollado y mantenido por <a href="https://sac-av-web.netlify.app/">SAC.VJ Producciones</a></sub>
</div>
