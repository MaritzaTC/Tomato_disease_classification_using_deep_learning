## 🍅  Tomato disease classification using deep learning
---
**Integrantes:**
- [X] [Ana María Vega Angarita](https://github.com/anavegaa)
- [X] [Johan Sebastian Henao ](https://github.com/MaritzaTC)
- [X] [Maritza Tabarez Cárdenas](https://github.com/JohanSH7)

> [!IMPORTANT]  
> Este proyecto es con fines académicos.

Este proyecto utiliza técnicas de *Deep Learning* para diagnosticar enfermedades en hojas de tomate a partir de imágenes.  
Se desarrolló un modelo de red neuronal convolucional (CNN) capaz de clasificar imágenes en 10 categorías, correspondientes a enfermedades específicas o a hojas saludables.

### 🔍 Arquitecturas utilizadas:
- ResNet50  
- MobileNetV3  
- InceptionV3  
- VGG16  

---

## 🌱 Contexto

Las enfermedades en cultivos de tomate representan una amenaza significativa para la producción agrícola y la seguridad alimentaria.  
Mediante el uso de IA, este proyecto busca ofrecer una herramienta escalable que pueda integrarse en:

- Aplicaciones móviles  
- Sistemas de drones  
- Estaciones inteligentes de monitoreo agrícola  

---

## 🎯 Objetivo

Construir y entrenar un modelo CNN que clasifique correctamente imágenes de hojas de tomate en una de las siguientes clases:

- `Tomato___Bacterial_spot`  
- `Tomato___Early_blight`  
- `Tomato___Late_blight`  
- `Tomato___Leaf_Mold`  
- `Tomato___Septoria_leaf_spot`  
- `Tomato___Spider_mites` (*Two-spotted spider mite*)  
- `Tomato___Target_Spot`  
- `Tomato___Tomato_Yellow_Leaf_Curl_Virus`  
- `Tomato___Tomato_mosaic_virus`  
- `Tomato___healthy`  

---

## 📦 Dataset

- **Fuente:** Kaggle – [Tomato Leaf Disease Detection](https://www.kaggle.com/datasets/kaustubhb999/tomatoleaf/)  
- **Formato:** `.jpg`, resolución 256×256 píxeles  
- **Total de imágenes:** 11,000  
- **Distribución:**
  - Entrenamiento: 10,000 imágenes (1,000 por clase)  
  - Validación: 1,000 imágenes (100 por clase)  
- **Balance:** Dataset completamente balanceado  

---

## ⚙️ Metodología

- **Modelo base:** Redes convolucionales construidas con Keras y TensorFlow  
- **Aumentos de datos:**  
  - Rotaciones  
  - Desplazamientos  
  - Zooms  
  - Contraste/brillo  
  - Flips horizontales  
- **Optimización:**  
  - Función de pérdida: `categorical_crossentropy`  
  - Optimizador: `Adam`  
- **Evaluación del modelo:**  
  - Accuracy  
  - Precision, Recall y F1-Score por clase  
  - Matriz de confusión  
  - Gráficas de evolución de la pérdida y precisión durante el entrenamiento  

---

## 📈 Impacto Esperado

- Reducción de errores humanos en el diagnóstico de enfermedades  
- Aceleración del monitoreo de cultivos  
- Prevención de pérdidas económicas mediante detección temprana  
- Cobertura de enfermedades críticas para la industria del tomate  

---

## 📄 Documentación

El proyecto incluye materiales complementarios que detallan el contexto, los objetivos, la implementación, las métricas y los resultados obtenidos:

- 📘 **Informe técnico**: Documento PDF con la descripción completa del proyecto, metodología y resultados.  
  👉 [Ver documento](ENTREGA1.pdf)

- 📊 **Informe ejecutivo**: Donde se describen los procesos, arquitectura, iteraciones y análisis de resultados brevemente.  
  👉 [Ver informe ejecutivo](INFORME_PROYECTO.PDF)

- 🎥 **Video demostrativo**: Presentación en video del proyecto.   
  👉 [Ver en YouTube](https://www.youtube.com/watch?v=qrI-pqzGsrM)



## 📚 Referencias 
1. [Dataset en Kaggle](https://www.kaggle.com/datasets/kaustubhb999/tomatoleaf/) 
2. [Curso Deep Learning - R. Ramos](https://rramosp.github.io/2021.deeplearning/content/M04.html )