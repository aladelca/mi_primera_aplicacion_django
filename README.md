# Reviews App - Mi Primera Aplicación Django 🚀

## Descripción del Proyecto

Esta es una aplicación web de **gestión de reseñas** desarrollada con Django como parte del curso **Python for Artificial Intelligence** en **CIBERTEC - Perú**. La aplicación permite a los usuarios crear, visualizar y gestionar reseñas de manera intuitiva, con un diseño moderno y minimalista que utiliza negro como color principal.

### 🌟 Características Principales
- **Crear reseñas**: Los usuarios pueden escribir y guardar sus opiniones
- **Visualizar reseñas**: Lista elegante de todas las reseñas con diseño tipo tarjeta
- **Diseño responsivo**: Optimizado para dispositivos móviles y escritorio
- **Interfaz moderna**: Tema negro con gradientes y efectos visuales atractivos
- **Navegación intuitiva**: Enlaces claros entre las diferentes secciones

## 📚 Curso: Python for Artificial Intelligence
**Institución:** CIBERTEC - Perú  
**Nivel:** Intermedio

## 🎯 Objetivos de Aprendizaje

- Comprender los conceptos fundamentales de Django
- Configurar un entorno de desarrollo con Django
- Crear modelos, vistas y templates básicos
- Implementar el patrón MVT (Model-View-Template)
- Preparar el entorno para futuras implementaciones de IA

## 🛠️ Tecnologías Utilizadas

- **Python 3.9+**
- **Django 4.2+**
- **SQLite** (Base de datos por defecto)
- **HTML5/CSS3** (Diseño personalizado)
- **CSS Grid & Flexbox** (Layout responsivo)
- **Gradientes CSS** (Efectos visuales modernos)

## 📋 Requisitos Previos

Antes de comenzar, asegúrate de tener instalado:

```bash
# Verificar versión de Python
python --version

# Verificar pip
pip --version
```

## 🚀 Instalación y Configuración

### 1. Clonar el repositorio
```bash
git clone https://github.com/aladelca/mi_primera_aplicacion_django.git
cd mi_primera_aplicacion_django
```

### 2. Crear entorno virtual
```bash
# Crear entorno virtual
python -m venv venv_django

# Activar entorno virtual
# En macOS/Linux:
source venv_django/bin/activate
# En Windows:
venv_django\Scripts\activate
```

### 3. Instalar dependencias
```bash
pip install django
pip install -r requirements.txt  # (cuando esté disponible)
```

### 4. Configurar la aplicación
```bash
# Navegar al directorio del proyecto Django
cd lab1

# Realizar migraciones
python manage.py makemigrations
python manage.py migrate

# Crear superusuario (opcional)
python manage.py createsuperuser

# Ejecutar servidor de desarrollo
python manage.py runserver
```

### 5. Acceder a la aplicación
Abre tu navegador y visita: `http://127.0.0.1:8000/`

## 📁 Estructura del Proyecto

```
mi_primera_aplicacion_django/
├── README.md
├── LICENSE
├── lab1/                          # Proyecto Django principal
│   ├── manage.py
│   ├── db.sqlite3                 # Base de datos SQLite
│   ├── lab1/                      # Configuración del proyecto
│   │   ├── __init__.py
│   │   ├── settings.py
│   │   ├── urls.py
│   │   ├── wsgi.py
│   │   └── asgi.py
│   └── reviews/                   # Aplicación de reseñas
│       ├── __init__.py
│       ├── admin.py               # Configuración del admin
│       ├── apps.py
│       ├── models.py              # Modelo Review
│       ├── views.py               # Vistas de la aplicación
│       ├── urls.py                # URLs de la app
│       ├── forms.py               # Formularios Django
│       ├── tests.py
│       ├── migrations/            # Migraciones de BD
│       └── templates/             # Templates HTML
│           ├── index.html         # Página de inicio
│           ├── add_review.html    # Formulario nueva reseña
│           └── list_review.html   # Lista de reseñas
```

## 🔧 Funcionalidades Implementadas

### ✅ **Sistema de Reseñas Completo**
- **Página de inicio**: Diseño elegante con navegación principal
- **Crear reseñas**: Formulario intuitivo para agregar nuevas reseñas
- **Listar reseñas**: Vista de todas las reseñas en formato de tarjetas
- **Modelo de datos**: Estructura simple pero efectiva para almacenar reseñas

### ✅ **Diseño y UX**
- **Tema negro moderno**: Gradientes y efectos visuales atractivos
- **Diseño responsivo**: Optimizado para móviles, tablets y escritorio
- **Navegación intuitiva**: Enlaces claros entre secciones
- **Efectos interactivos**: Hover states y transiciones suaves
- **Tipografía moderna**: Uso de la fuente Inter para mejor legibilidad

### ✅ **Desarrollo Django**
- **Configuración inicial** de Django correctamente implementada
- **Modelo Review** con campo de texto para reseñas
- **Formularios Django** para manejo de datos
- **Sistema de URLs** configurado con nombres descriptivos
- **Templates con diseño personalizado** sin dependencias externas
- **Vistas basadas en funciones** (FBV) bien estructuradas

## 📖 Conceptos Clave Aprendidos

### 1. Patrón MVT (Model-View-Template)
- **Model:** Definición de la estructura de datos
- **View:** Lógica de negocio y procesamiento
- **Template:** Presentación y interfaz de usuario

### 2. ORM de Django
- Mapeo objeto-relacional
- Migraciones automáticas
- Consultas con QuerySets

### 3. Sistema de URLs
- Configuración de rutas
- Parámetros en URLs
- Namespaces y names

### 4. Templates y Diseño Responsivo
- Sistema de templates personalizados sin frameworks externos
- CSS moderno con gradientes y efectos visuales
- Media queries para diferentes dispositivos
- Diseño mobile-first

### 5. Gestión de Formularios
- Formularios Django integrados
- Validación automática de datos
- Manejo de errores y redirecciones

## 🎨 Características del Diseño

### **Tema Visual**
- **Paleta de colores**: Negro como color principal con gradientes (`#1a1a1a` a `#2d2d2d`)
- **Tipografía**: Inter font para mejor legibilidad y modernidad
- **Efectos visuales**: Sombras, hover states y transiciones suaves

### **Responsividad**
- **Mobile-first**: Diseño optimizado primero para móviles
- **Breakpoints**: 
  - Móvil: ≤ 480px
  - Tablet: 481px - 768px  
  - Escritorio: > 768px
- **Elementos adaptativos**: Botones, tipografía y espaciado que se ajustan automáticamente

### **Experiencia de Usuario**
- **Navegación intuitiva**: Enlaces claros y bien organizados
- **Estados interactivos**: Efectos hover en botones y tarjetas
- **Feedback visual**: Indicadores de focus en formularios
- **Loading states**: Transiciones suaves entre páginas

## 🧪 Comandos Útiles

```bash
# Navegar al directorio del proyecto
cd lab1

# Crear nueva aplicación
python manage.py startapp nombre_app

# Hacer migraciones
python manage.py makemigrations

# Aplicar migraciones
python manage.py migrate

# Ejecutar tests
python manage.py test

# Shell interactivo de Django
python manage.py shell

# Acceder al panel de administración
# Primero crear superusuario: python manage.py createsuperuser
# Luego visitar: http://127.0.0.1:8000/admin/
```

## 🎓 Próximos Pasos

Esta aplicación de reseñas será extendida en futuras clases para incluir:

1. **Sistema de usuarios** y autenticación
2. **APIs REST** para operaciones CRUD de reseñas
3. **Análisis de sentimientos** de las reseñas usando NLP
4. **Integración con modelos de ML** para clasificación de reseñas
5. **Dashboard de analytics** con visualización de datos
6. **Sistema de puntuación** y ratings
7. **Deploy en la nube** (Heroku/AWS/Docker)

## 📚 Recursos de Estudio

- [Documentación oficial de Django](https://docs.djangoproject.com/)
- [Django Girls Tutorial](https://tutorial.djangogirls.org/es/)
- [Real Python - Django Tutorials](https://realpython.com/tutorials/django/)
- [MDN Django Tutorial](https://developer.mozilla.org/es/docs/Learn/Server-side/Django)

## 🤝 Contribuciones

Este proyecto es parte del material educativo de CIBERTEC. Los estudiantes pueden:

1. Fork el proyecto
2. Crear una rama para sus mejoras
3. Enviar pull requests con nuevas funcionalidades
4. Reportar issues y sugerencias

## 👨‍🏫 Instructor

**Profesor:** Carlos Adrian Alarcon Delgado
**Institución:** CIBERTEC - Perú  
**Curso:** Python for Artificial Intelligence

**LinkedIn:** [Ver mi perfil](https://www.linkedin.com/in/carlos-adrian-alarcon-delgado/)

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 🆘 Soporte

Si tienes preguntas o necesitas ayuda:

1. Revisa la documentación oficial de Django
2. Consulta los issues del repositorio
3. Pregunta en las clases presenciales
4. Envía un email al instructor

---

**CIBERTEC - Python for Artificial Intelligence**  
*Construyendo el futuro con tecnología* 🇵🇪