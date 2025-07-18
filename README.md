# Carolina Spa - Sitio Web

## 📋 Descripción

Carolina Spa es un sitio web moderno y elegante para un spa de bienestar. El proyecto presenta una interfaz atractiva con diseño responsivo que incluye:

- **Página de inicio** con slider de imágenes
- **Sección de bienvenida** 
- **Tarjetas informativas** sobre servicios
- **Horarios de atención** en formato tabla
- **Catálogo de productos** con imágenes y precios
- **Navegación completa** con enlaces a redes sociales
- **Diseño responsivo** que se adapta a diferentes dispositivos

## 🛠️ Tecnologías Utilizadas

### Frontend
- **HTML5** - Estructura semántica del sitio
- **SCSS/Sass** - Preprocesador CSS con metodología BEM
- **CSS Grid & Flexbox** - Layouts modernos y responsivos
- **JavaScript** - Interactividad básica

### Herramientas de Desarrollo
- **Gulp** - Automatización de tareas
- **PostCSS** - Post-procesamiento de CSS
- **Autoprefixer** - Compatibilidad entre navegadores
- **CSSNano** - Minificación de CSS
- **Gulp-Imagemin** - Optimización de imágenes
- **Gulp-WebP & Gulp-AVIF** - Conversión a formatos modernos de imagen

### Dependencias Externas
- **Swiper.js** - Slider de imágenes
- **Google Fonts** - Tipografías (Italianno, Lato)

## 📁 Estructura del Proyecto

```
CarolinaSpa-main/
├── src/
│   ├── scss/
│   │   ├── app.scss              # Archivo principal de estilos
│   │   ├── base/                 # Estilos base y variables
│   │   └── ui/                   # Componentes de interfaz
│   │       ├── header/           # Estilos del encabezado
│   │       ├── social/           # Redes sociales
│   │       ├── contenido/        # Contenido principal
│   │       └── footer/           # Pie de página
│   └── img/                      # Imágenes del proyecto
├── build/                        # Archivos compilados (generado)
├── gulpfile.js                   # Configuración de Gulp
├── package.json                  # Dependencias del proyecto
└── index.html                    # Página principal
```

## 🚀 Instalación y Uso

### Prerrequisitos
- Node.js (versión 14 o superior)
- npm (incluido con Node.js)

### Pasos de Instalación

1. **Clonar el repositorio**
   ```bash
   git clone [URL-del-repositorio]
   cd CarolinaSpa-main
   ```

2. **Instalar dependencias**
   ```bash
   npm install
   ```

3. **Ejecutar en modo desarrollo**
   ```bash
   npm run dev
   ```

### Comandos Disponibles

- `npm run dev` - Inicia el servidor de desarrollo con watch mode
- `gulp css` - Compila solo los estilos SCSS
- `gulp imagenes` - Optimiza las imágenes
- `gulp versionWebp` - Convierte imágenes a formato WebP
- `gulp versionAvif` - Convierte imágenes a formato AVIF

## 🎨 Características del Diseño

### Metodología BEM
El proyecto utiliza la metodología BEM (Block Element Modifier) para organizar los estilos CSS de manera modular y mantenible.

### Diseño Responsivo
- **Mobile First** - Diseño optimizado para dispositivos móviles
- **Breakpoints** - Adaptación a tablets y desktop
- **CSS Grid** - Layouts modernos y flexibles

### Optimización de Imágenes
- **Compresión automática** con Gulp-Imagemin
- **Formatos modernos** - WebP y AVIF para mejor rendimiento
- **Optimización de calidad** configurada al 50%

## 📱 Secciones del Sitio

1. **Header** - Logo y enlaces a redes sociales
2. **Navegación** - Menú principal del sitio
3. **Slider** - Carrusel de imágenes promocionales
4. **Bienvenida** - Mensaje de introducción
5. **Cards** - Tarjetas informativas sobre servicios
6. **Horarios** - Tabla con horarios de atención
7. **Productos** - Catálogo de productos del spa
8. **Footer** - Información de contacto y enlaces

## 🔧 Configuración de Gulp

El archivo `gulpfile.js` incluye las siguientes tareas:

- **Compilación de SCSS** a CSS con autoprefixer y minificación
- **Optimización de imágenes** con diferentes formatos
- **Watch mode** para desarrollo en tiempo real
- **Source maps** para debugging

## 📄 Licencia

Este proyecto está bajo la licencia ISC.

## 👨‍💻 Autor

**Juan De la Torre** - [@codigoconjuan](https://github.com/codigoconjuan)

---

*Proyecto desarrollado como parte del curso de desarrollo web moderno con Gulp, SASS y metodología BEM.*
