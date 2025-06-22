# 🧠 Juego Educativo Interactivo

**Juego Educativo Interactivo** es una aplicación web ligera y amigable desarrollada con **Python + Flask**, pensada para niños y niñas en etapa de alfabetización. Presenta letras y números con sonidos en español, fomentando el aprendizaje de forma lúdica, auditiva y visual.

---

## 🌍 Idiomas Disponibles

- 🇧🇷 [Versão em Português](https://github.com/jorgevalega/jogo-educativo)
- 🇪🇸 Español – *Estás aquí*
- 🇺🇸 [English Version](https://github.com/jorgevalega/educational-game)

---

## 🚀 Funcionalidades

- ✅ Visualización de **letras mayúsculas y minúsculas**, organizadas por páginas
- 🔢 Conteo del **0 al 100**, dividido de forma didáctica (0–10, 11–20, ...)
- 🔊 Reproducción de audio para cada letra y número
- 🏅 Retroalimentación positiva con **medalla y sonido de felicitaciones**
- 📱 Interfaz responsiva para uso en celular, tablet o escritorio
- 🔄 Navegación automática entre páginas (sin botones)
- 🎉 Final animado con opción de reinicio

---

## 📸 Capturas de Pantalla

![Juego Educativo](assets/jogo.jpg)
![Medalla y felicitaciones](assets/parabens.jpg)

---

## 🛠️ Instalación

**1. Requisitos previos**  
Asegúrate de tener **Python 3.8 o superior** instalado en tu sistema.

**2. Clona el repositorio**

```bash
git clone https://github.com/jorgevalega/juego-educativo.git
cd juego-educativo
```

**3. Crea y activa un entorno virtual (recomendado)**

```bash
python -m venv venv
source venv/bin/activate       # Linux/macOS
venv\Scripts\activate          # Windows
```
**4. Instala las dependencias**

```bash
pip install -r requirements.txt
```

---

## ▶️ Cómo usar

**1. Ejecuta la aplicación localmente con:**

```bash
python app.py
```

**2. Abre el navegador y accede a:**

```bash
http://localhost:5000
```

**3. Haz clic en las letras o números para escuchar su pronunciación.**
Al completar una página, aparecerá una medalla con sonido de felicitaciones y el juego avanzará automáticamente a la siguiente página.

---

## 📁 Estructura de Carpetas

```bash
juego-educativo/
├── app.py
├── requirements.txt
├── static/
│   └── audio/
│       ├── A.mp3
│       ├── 1.mp3
│       └── felicitaciones.mp3
├── templates/
│   └── index.html
├── assets/
│   ├── juego.jpg
│   └── felicitaciones.jpg
└── README.md
```

---

## 🧾 Dependencias

- `flask` — Framework web ligero y potente para Python
- `gtts` (opcional) — Utilizado para generar los audios MP3 (Google Text-to-Speech)

Todas las dependencias necesarias están listadas en [`requirements.txt`](requirements.txt).

---

## 🧑‍💻 Autor

Desarrollado por [Jorge Valega](https://github.com/jorgevalega) – apasionado por la automatización, la accesibilidad y las herramientas de aprendizaje de idiomas.

---

## 📄 Licencia

Este proyecto está licenciado bajo la [Licencia MIT](LICENSE).
