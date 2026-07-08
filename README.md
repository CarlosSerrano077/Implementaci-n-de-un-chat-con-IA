# FitLab AI Chatbot

FitLab AI Chatbot es un asistente inteligente desarrollado como complemento de la aplicación web **FitLab**, una plataforma enfocada en el entrenamiento físico, la nutrición y el bienestar.

El chatbot permite a los usuarios realizar consultas de manera natural y recibir respuestas generadas mediante un modelo de Inteligencia Artificial alojado en **Hugging Face**, utilizando un backend desarrollado en **Node.js**.

---

##  Características

-  Chat en tiempo real.
-  Integración con modelos de Inteligencia Artificial de Hugging Face.
-  Interfaz moderna inspirada en la aplicación FitLab.
-  Diseño responsive para dispositivos móviles.
-  Opción para limpiar la conversación.
-  Respuestas rápidas y dinámicas.
-  Comunicación mediante API REST.

---

##  Tecnologías utilizadas

### Frontend

- HTML5
- CSS3
- JavaScript
- Font Awesome

### Backend

- Node.js
- Express.js

### Inteligencia Artificial

- Hugging Face Inference API

---

##  Estructura del proyecto

```
FitLab-AI/
│
├── index.html
├── styles.css
├── app.js
├── server.js
├── package.json
├── .env
└── README.md
```

---

##  Instalación

### 1. Clonar el repositorio

```bash
git clone https://github.com/usuario/fitlab-ai.git
```

---

### 2. Entrar al proyecto

```bash
cd fitlab-ai
```

---

### 3. Instalar dependencias

```bash
npm install
```

---

### 4. Configurar las variables de entorno

Crear un archivo **.env**

```env
HF_API_KEY=TU_API_KEY
PORT=3000
```

---

### 5. Ejecutar el servidor

```bash
npm start
```

o

```bash
node server.js
```

---

##  Uso

1. Abrir el navegador.

2. Acceder a:

```
http://localhost:3000
```

3. Escribir una pregunta.

4. El chatbot enviará la solicitud al backend.

5. El backend consultará el modelo de Hugging Face.

6. La respuesta será mostrada en la conversación.

---

##  Funcionamiento

```
Usuario
    │
    ▼
Frontend (HTML + CSS + JS)
    │
    ▼
Backend (Node.js + Express)
    │
    ▼
Hugging Face API
    │
    ▼
Modelo de IA
    │
    ▼
Respuesta
    │
    ▼
Frontend
```

---

##  Objetivo del proyecto

El objetivo principal es proporcionar un asistente virtual que complemente la plataforma FitLab, permitiendo responder dudas relacionadas con:

- Entrenamiento físico
- Rutinas
- Nutrición
- Suplementación
- Hábitos saludables
- Bienestar

Además, el proyecto sirve como ejemplo de integración entre aplicaciones web y servicios de Inteligencia Artificial mediante APIs.

---

##  Seguridad

- La clave de acceso a Hugging Face se almacena mediante variables de entorno.
- El frontend nunca expone las credenciales de la API.
- Toda la comunicación con la IA se realiza desde el servidor.

---
