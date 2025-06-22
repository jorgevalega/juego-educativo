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

**3. Crie e ative um ambiente virtual (recomendado)**

```bash
python -m venv venv
source venv/bin/activate       # Linux/macOS
venv\Scripts\activate          # Windows
```
**4. Instale as dependências**

```bash
pip install -r requirements.txt
```

---

## ▶️ Como usar

**1. Execute a aplicação localmente com:**

```bash
python app.py
```

**2. Abra o navegador e acesse:**

```bash
http://localhost:5000
```

**3. Toque nas letras ou números para ouvir sua pronúncia.**
Ao completar uma página, uma medalha aparece com som de parabéns e a aplicação avança automaticamente para a próxima página.

---

## 📁 Estrutura de Pastas

```bash
jogo-educativo/
├── app.py
├── requirements.txt
├── static/
│   └── audio/
│       ├── A.mp3
│       ├── 1.mp3
│       └── parabens.mp3
├── templates/
│   └── index.html
├── assets/
│   ├── jogo.jpg
│   └── parabens.jpg
└── README.md
```

---

## 🧾 Dependências

- `flask` — Framework web leve e poderoso para Python
- `gtts` (opcional) — Utilizado para gerar os áudios em MP3 (Text-to-Speech do Google)

Todas as dependências necessárias estão listadas em [`requirements.txt`](requirements.txt).

---

## 🧑‍💻 Autor

Desenvolvido por [Jorge Valega](https://github.com/jorgevalega) – apaixonado por automação, acessibilidade e ferramentas de aprendizado de idiomas.

---

## 📄 Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).
