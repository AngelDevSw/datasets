# Datasets

## 📋 Descripción

Este repositorio contiene una colección de datasets (conjuntos de datos) organizados para proyectos de análisis de datos, machine learning y ciencia de datos. Los datasets están gestionados utilizando Git LFS (Large File Storage) para manejar eficientemente archivos de gran tamaño.

## 🎯 Propósito

El objetivo de este repositorio es:

- Centralizar datasets útiles para diversos proyectos
- Facilitar el acceso y versionado de conjuntos de datos
- Proporcionar una estructura organizada para almacenar y compartir datos
- Utilizar Git LFS para gestionar archivos grandes de manera eficiente

## 📁 Estructura del Repositorio

```
datasets/
├── README.md           # Este archivo
└── [datasets]          # Carpetas con conjuntos de datos organizados por categoría
```

## 🚀 Uso

### Clonar el Repositorio

Para clonar este repositorio con Git LFS:

```bash
git lfs install
git clone https://github.com/AngelDevSw/datasets.git
cd datasets
```

### Agregar Nuevos Datasets

1. Crea una carpeta con un nombre descriptivo para tu dataset
2. Incluye un archivo README en la carpeta explicando el contenido y la licencia
3. Si los archivos son grandes (>50MB), asegúrate de que Git LFS esté configurado
4. Haz commit y push de los cambios

```bash
git add .
git commit -m "Añadir dataset: [nombre descriptivo]"
git push
```

## 📊 Tipos de Datos

Este repositorio puede contener diversos tipos de datasets:

- Datos tabulares (CSV, Excel, etc.)
- Imágenes
- Texto y documentos
- Audio
- Video
- Datos JSON/XML
- Bases de datos

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Si deseas agregar un nuevo dataset:

1. Asegúrate de que tienes los derechos necesarios para compartir los datos
2. Incluye documentación clara sobre el origen y uso de los datos
3. Organiza los archivos de manera lógica
4. Crea un pull request con una descripción detallada

## ⚙️ Configuración de Git LFS

Para trabajar con archivos grandes, asegúrate de tener Git LFS instalado:

```bash
# Instalar Git LFS
git lfs install

# Rastrear tipos de archivos específicos (ejemplos)
git lfs track "*.csv"
git lfs track "*.jpg"
git lfs track "*.png"
git lfs track "*.zip"
git lfs track "*.parquet"
```

## 📝 Licencia

Por favor, verifica la licencia de cada dataset individual antes de utilizarlo. Los datos pueden estar sujetos a diferentes términos de uso. Cada dataset debe incluir información sobre su licencia en su respectivo archivo README o archivo LICENSE.

## 📧 Contacto

Para preguntas o sugerencias, por favor abre un issue en este repositorio.

---

**Nota**: Este repositorio está en desarrollo activo. La estructura y organización pueden cambiar con el tiempo.
