# EmotionAI

Proyecto de **Inteligencia Artificial** que detecta emociones en rostros a partir de imágenes o cámara web.  
El sistema cuenta con un **frontend web** y un **backend en Python** que utiliza un modelo de Deep Learning entrenado para clasificar emociones.

---

## Funcionalidades
- Detección de emociones en imágenes o cámara en tiempo real.
- Modelo entrenado con redes neuronales convolucionales.
- Interfaz web simple e intuitiva.
- API en Python para procesar las imágenes y devolver la emoción detectada.

---

## Estructura del proyecto
```
IA/
│── index.html         # Página principal
│── script.js          # Lógica frontend
│── Styles.css         # Estilos de la página
│
├── backend/
│   ├── api.py         # API Flask que conecta con el modelo
│   ├── modelo_emociones.h5  # Modelo entrenado
│   ├── clases.npy     # Clases de emociones
│
└── ejemplos/          # Imágenes de prueba
```

---

## Instalación y uso

### 1. Clonar el repositorio
```bash
git clone https://github.com/tu-usuario/EmotionAI.git
cd EmotionAI/backend
```

### 2. Instalar dependencias
Ejecuta en la terminal:

```bash
pip install flask flask-cors joblib numpy pillow pandas scikit-learn matplotlib
```

### 3. Ejecutar el backend
Dentro de la carpeta `backend`:

```bash
python api.py
```

Esto levantará la API en `http://127.0.0.1:5000/`.

### 4. Abrir la interfaz web
Abre el archivo `index.html` en tu navegador.  
Desde allí podrás subir imágenes o usar la cámara y el sistema detectará la emoción.

---

## Tecnologías utilizadas
- **Python** (Flask, TensorFlow/Keras, scikit-learn, NumPy, Pandas, Pillow, Matplotlib, Joblib)
- **HTML, CSS, JavaScript** (Frontend)
- **Modelo CNN** para clasificación de emociones

---

## Autor
Proyecto desarrollado por Julian Alfonso(https://github.com/JulianAlfonso3845)  
