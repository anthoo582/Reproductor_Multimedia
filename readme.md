# 🎵 Super Reproductor Multimedia

**Versión:** 2.0.0  
**Autor:** By Anthony Lopez  
**GitHub:** [@anthoo582](https://github.com/anthoo582)

---

## 📖 Descripción

Super Reproductor Multimedia es una aplicación de escritorio moderna y completa desarrollada con PySide6 (Qt) que permite reproducir y visualizar una amplia variedad de contenido multimedia. Desde videos y música hasta imágenes y documentos PDF, todo en una sola interfaz elegante y funcional.

## ✨ Características Principales

### 🎬 Reproducción Multimedia
- **Videos**: Soporte para formatos modernos, legacy, profesionales y de disco
- **Audio**: Reproducción de archivos de audio con visualización de carátulas
- **Imágenes**: Visor de imágenes con zoom profesional (hasta 8x) y navegación fluida
- **PDFs**: Visor nativo de PDFs con zoom vectorial y navegación por páginas

### 🎨 Interfaz de Usuario
- **3 Temas**: Oscuro, Claro y Púrpura
- **Diseño Glassmorphism**: Efectos de vidrio modernos y elegantes
- **Pantalla Completa**: Modo fullscreen con controles estilo YouTube para videos
- **Caché de Imágenes**: Sistema LRU para carga optimizada de imágenes

### 🎮 Controles Avanzados
- **Velocidad de Reproducción**: 0.25x a 3.0x
- **Zoom Inteligente**: Zoom con rueda del mouse centrado en cursor
- **Navegación por Teclado**: Atajos completos para todas las funciones
- **Drag & Drop**: Arrastra archivos directamente a la aplicación
- **Reproducción Aleatoria**: Modo shuffle y repetición

### 📁 Gestión de Archivos
- **Lista de Reproducción**: Gestión completa de archivos multimedia
- **Carga Automática**: Carga todos los archivos compatibles de la carpeta
- **Metadatos de Audio**: Extracción automática de carátulas de archivos de audio

## 📋 Formatos Soportados

### 🎬 Video
- **Modernos**: MP4, MKV, MOV, AVI, WebM, MPEG, MPG, M4V, 3GP, 3G2
- **Legacy**: WMV, ASF, RM, RMVB, FLV, F4V, VOB, OGV, DivX, Xvid
- **Profesionales**: MTS, M2TS, TS, MXF, GXF, LXF, DV, DVC, CINE
- **Disco**: VOB, IFO, BUP, ISO, DAT, M2TS, MTS, CLPI, BDMV, MPLS

### 🎵 Audio
- **Lossy**: MP3, AAC, M4A, OGG, Opus, WMA, AC3, DTS, AMR, RA, GSM
- **Lossless**: FLAC, WAV, AIFF, AIF, ALAC, APE, WV, TTA, DSF, DFF
- **MIDI**: MID, MIDI, KAR, MOD, XM, S3M, IT
- **Disco**: AC3, EAC3, TrueHD, DTS, DTSHD, LPCM, PCM

### 🖼️ Imágenes
- **Comunes**: JPG, JPEG, PNG, WebP, AVIF, HEIC, HEIF, BMP, TIFF, TIF, GIF, JFIF
- **RAW**: RAW, DNG, NEF, CR2, CR3, ARW, ORF, RW2, SR2, SRF, RAF, PEF
- **Técnicas**: EXR, HDR, PFM, PPM, PGM, PBM, FITS, DDS, TGA, ICO, CUR
- **Vectoriales**: SVG, AI, EPS, CDR, WMF, EMF

### 📄 Documentos
- **PDF**: Soporte nativo con zoom vectorial (requiere PySide6-Addons)

### 📝 Subtítulos
- SRT, ASS, SSA, VTT, SUB, IDX, SUP, TTML, XML

### 📡 Streaming
- M3U, M3U8, PLS, DASH, MPD, ISM, ISMV

## 🔧 Requisitos

### Dependencias Principales
```bash
PySide6>=6.0.0
```

### Dependencias Opcionales
```bash
# Para soporte nativo de PDFs
PySide6-Addons>=6.0.0

# Para extracción de metadatos y carátulas de audio
mutagen>=1.45.0
```

## 📦 Instalación

### 1. Clonar o descargar el repositorio
```bash
git clone https://github.com/anthoo582/super-reproductor-multimedia.git
cd super-reproductor-multimedia
```

### 2. Instalar dependencias
```bash
pip install PySide6
```

### 3. Instalar dependencias opcionales (recomendado)
```bash
# Para soporte de PDFs
pip install PySide6-Addons

# Para metadatos de audio
pip install mutagen
```

### 4. Ejecutar la aplicación
```bash
python "reprdoductro de musica.py"
```

O desde la línea de comandos con archivos:
```bash
python "reprdoductro de musica.py" archivo1.mp4 archivo2.jpg
```

## 🎮 Uso

### Interfaz Principal

1. **Agregar Archivos**: Haz clic en "+ Agregar" o usa `Ctrl+O`
2. **Reproducir**: Doble clic en un archivo de la lista o usa los controles
3. **Pantalla Completa**: Presiona `F` o haz clic en el botón ⛶
4. **Navegar**: Usa las flechas del teclado o los botones de navegación

### Modo Pantalla Completa

- **Videos**: Controles estilo YouTube que se ocultan automáticamente
- **Imágenes/PDFs**: Controles de zoom y navegación en la parte inferior
- **Audio**: Visualización de carátula o icono de música

## ⌨️ Atajos de Teclado

### Reproducción
- `Espacio` - Play/Pause
- `Flecha Derecha` - Avanzar 10 segundos (video/audio) o Siguiente (imagen/PDF)
- `Flecha Izquierda` - Retroceder 10 segundos (video/audio) o Anterior (imagen/PDF)
- `Ctrl + →` - Siguiente archivo
- `Ctrl + ←` - Archivo anterior

### Volumen
- `Flecha Arriba` - Subir volumen (+5%)
- `Flecha Abajo` - Bajar volumen (-5%)
- `M` - Silenciar/Desilenciar

### Zoom (Imágenes/PDFs)
- `+` o `=` - Acercar
- `-` - Alejar
- `0` - Resetear zoom / Ajustar a ventana
- `Rueda del Mouse` - Zoom centrado en cursor

### Navegación
- `F` - Pantalla completa del contenido
- `R` - Activar/Desactivar repetición
- `S` - Activar/Desactivar reproducción aleatoria
- `Esc` - Salir de pantalla completa

### Archivos
- `Ctrl + O` - Abrir archivos
- `Drag & Drop` - Arrastrar archivos a la ventana

## 🎨 Temas

La aplicación incluye 3 temas predefinidos:

1. **Oscuro** (por defecto): Esquema de colores oscuro con acentos rojos
2. **Claro**: Tema claro con acentos azules
3. **Púrpura**: Tema oscuro con acentos púrpuras

Cambia el tema desde el selector en la barra superior.

## 🖼️ Características Especiales

### Visor de Imágenes
- Zoom hasta 8x con renderizado de alta calidad
- Navegación fluida con teclado o mouse
- Caché LRU para carga optimizada
- Soporte para formatos RAW y técnicos

### Visor de PDFs
- Zoom vectorial nativo (sin pixelación)
- Navegación por páginas
- Modo multi-página
- Requiere PySide6-Addons

### Reproductor de Video
- Controles estilo YouTube en pantalla completa
- Barra de progreso interactiva
- Control de velocidad de reproducción
- Sincronización de controles entre ventana principal y fullscreen

### Reproductor de Audio
- Extracción automática de carátulas (MP3, FLAC, M4A)
- Visualización de metadatos
- Control completo de reproducción

## 🐛 Solución de Problemas

### PDFs no se muestran
Instala PySide6-Addons:
```bash
pip install PySide6-Addons
```

### No se muestran carátulas de audio
Instala mutagen:
```bash
pip install mutagen
```

### Problemas de rendimiento con imágenes grandes
El sistema de caché LRU optimiza automáticamente la carga. Las imágenes se redimensionan a un máximo de 4096px por dimensión.

## 📝 Notas

- La aplicación carga automáticamente todos los archivos compatibles de la carpeta del archivo seleccionado
- Los formatos RAW de imagen pueden requerir codecs adicionales del sistema
- Algunos formatos de video legacy pueden no funcionar dependiendo de los codecs instalados en el sistema

## 👨‍💻 Autor

**Anthony Lopez**  
GitHub: [@anthoo582](https://github.com/anthoo582)

## 📄 Licencia

Este proyecto es de código abierto. Siéntete libre de usarlo, modificarlo y distribuirlo.

## 🙏 Contribuciones

Las contribuciones son bienvenidas. Si encuentras algún bug o tienes una sugerencia, no dudes en abrir un issue o enviar un pull request.

---

**¡Disfruta de tu experiencia multimedia!** 🎬🎵🖼️
