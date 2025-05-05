# 🌿 Plant Village Transfer Learning (V4)

Este repositorio contiene un proyecto de transferencia de aprendizaje para clasificar imágenes de hojas de plantas sanas y enfermas utilizando TensorFlow, MobileNetV2, y exportación a TensorFlow Lite (TFLite).

---

## 📂 Contenido del repositorio

```
├── README.md
├── TL_planet_village_V4.ipynb        # Notebook principal (listo para Colab)
├── tl_planet_village_v4.py           # Script Python equivalente al notebook
├── requirements.txt                  # Dependencias Python (pip)
├── requirements.yml                  # Dependencias Conda/YAML
```

---

## 🚀 Proyecto en vivo

La segunda parte de este proyecto consiste en un despliegue web usando Flask, donde:
✅ Se sirve una página web que usa la cámara en tiempo real
✅ El modelo en formato `.tflite` se usa para hacer predicciones en vivo

* **Repositorio Flask + Render deploy:**
  🔗 [https://github.com/AngelBReal/plant\_village](https://github.com/AngelBReal/plant_village)

* **Página desplegada en Render:**
  🌐 [https://plant-village-elnk.onrender.com](https://plant-village-elnk.onrender.com)

---

## 🧪 Cómo usar este repositorio

1️⃣ **Ejecuta el notebook en Google Colab**

* Abre `TL_planet_village_V4.ipynb` en Google Colab.
* Ejecuta todas las celdas para entrenar el modelo, evaluar resultados, y exportar a TFLite:

  * `plant_leaves_classifier_expert.keras`
  * `plant_leaves_classifier_expert.tflite`

---

2️⃣ **Instala dependencias localmente**

Si prefieres trabajar localmente:

```bash
# Usando pip
pip install -r requirements.txt

# O usando conda
conda env create -f requirements.yml
conda activate plant-village
```

---

3️⃣ **Corre el script Python (opcional)**

```bash
python tl_planet_village_v4.py
```

---

## 📸 Segunda parte: Deploy Flask + Cámara en vivo

El repositorio separado contiene el código para levantar una aplicación Flask que:

* Usa la cámara local (o del dispositivo) para capturar video.
* Corre inferencia usando el modelo `.tflite`.
* Muestra las predicciones directamente en el navegador.

Revisa los detalles y código aquí:
🔗 [https://github.com/AngelBReal/plant\_village](https://github.com/AngelBReal/plant_village)

Y prueba la versión desplegada aquí:
🌐 [https://plant-village-elnk.onrender.com](https://plant-village-elnk.onrender.com)

---



