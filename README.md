# **TFM: Detección y Análisis de Huellas de Tortugas utilizando Deep Learning**

### **Descripción del Proyecto**
Este proyecto forma parte del Trabajo Final de Máster en Ciencia de Datos y tiene como objetivo principal desarrollar un sistema automatizado basado en modelos de aprendizaje profundo para detectar y analizar huellas de tortugas marinas en imágenes capturadas en su entorno natural.

El proyecto utiliza modelos avanzados como YOLOv8 para la detección y U-Net para la segmentación, con el fin de optimizar procesos manuales y contribuir a iniciativas de conservación marina. Debido a restricciones de confidencialidad, no se incluye el dataset en este repositorio.

---

### **Características Principales**
- **Detección en tiempo real:** Implementación del modelo YOLOv8 para análisis rápido y eficiente.
- **Segmentación precisa:** Uso de U-Net para generar máscaras detalladas de las huellas.
- **Adaptación a condiciones adversas:** Procesamiento de imágenes diurnas, nocturnas y con variabilidad de texturas.
- **Conservación marina:** Herramientas orientadas a facilitar la monitorización de patrones migratorios y áreas críticas de anidación.

---

### **Tecnologías Utilizadas**
- **Lenguaje:** Python
- **Frameworks de Deep Learning:** PyTorch, TensorFlow
- **Modelos:** YOLOv8 y U-Net
- **Herramientas adicionales:** OpenCV, LabelMe (para anotaciones manuales)

---

### **Estructura del Proyecto**
📂 TFM-Tortugas 
├── 📂 code # Scripts para el entrenamiento, validación y visualización 
└── 📂 document # Documentación del TFM (informe, presentación)


### **Licencia**
Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.

### **Notas Finales**
Si deseas replicar los experimentos, necesitarás:
- Dataset: El dataset no se encuentra disponible en este repositorio por restricciones de confidencialidad.
- Entorno: GPUs recomendadas para el entrenamiento de los modelos.