# 🎮 CS:GO Estadísticas de Partida


## Descripción

Este proyecto es una aplicación web interactiva que predice la supervivencia de un jugador en una ronda de CS:GO usando Machine Learning. Incluye un frontend visual moderno inspirado en la estética de CS:GO y una consola tipo terminal que simula el análisis de una partida.

- **Framework Backend:** FastAPI
- **Frontend:** HTML + CSS + JS (Jinja2)
- **Modelo ML:** RandomForestClassifier (scikit-learn)
- **Tema:** Edición Morada (Purple Edition)

---

## 🚀 Instalación y Ejecución

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/tuusuario/csgo-prediccion-morada.git
   cd csgo-prediccion-morada
   ```

2. **Crea y activa un entorno virtual (opcional pero recomendado):**
   ```bash
   python -m venv venv
   venv\Scripts\activate  # En Windows
   # source venv/bin/activate  # En Linux/Mac
   ```

3. **Instala las dependencias:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Entrena el modelo (solo la primera vez o si cambias los datos):**
   - Coloca tu archivo de datos CSV en la ruta indicada en `model/model.py`.
   - Ejecuta:
     ```bash
     python model/model.py
     ```

5. **Inicia el servidor:**
   ```bash
   python -m uvicorn main:app --reload
   ```

6. **Abre tu navegador en:**
   [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## 🖼️ Imágenes de Ejemplo

### Formulario de Predicción
![Formulario](images/formulario_csgo.png)

### Resultado de la Predicción
![Resultado](images/resultado_csgo.png)

### Consola de Análisis (Simulación)
![Consola](images/terminal_csgo.png)

---


## 📦 Estructura del Proyecto

```
modelos-master/
├── main.py                # Backend FastAPI
├── model/model.py         # Script de entrenamiento ML
├── checkpoints/model.pkl  # Modelo entrenado
├── templates/
│   ├── index.html         # Formulario
│   └── result.html        # Resultados
├── images/                # Imágenes para el README
├── requirements.txt       # Dependencias
└── readme.md              # Este archivo
```

---

## ✨ Créditos y Licencia

- Inspirado en CS:GO y la comunidad de Machine Learning.
- UI y diseño: Edición Morada por [Tu Nombre].
- Licencia: MIT

---

¿Te gustaría contribuir o tienes sugerencias? ¡Abre un issue o un pull request!
