# Mi Primera Aplicación Django 🚀

## Descripción del Proyecto

Esta es una aplicación web inicial desarrollada con Django como parte del curso **Python for Artificial Intelligence** en **CIBERTEC - Perú**. El proyecto está diseñado para introducir a los estudiantes en el desarrollo web con Django, sentando las bases para futuras implementaciones de inteligencia artificial.

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

- **Python 3.8+**
- **Django 4.2+**
- **SQLite** (Base de datos por defecto)
- **HTML5/CSS3**
- **Bootstrap** (para estilos responsivos)

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
git clone https://github.com/tu-usuario/mi_primera_aplicacion_django.git
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
├── manage.py
├── requirements.txt
├── mi_proyecto/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── asgi.py
├── mi_app/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── views.py
│   ├── urls.py
│   └── migrations/
├── templates/
│   └── base.html
├── static/
│   ├── css/
│   ├── js/
│   └── img/
└── README.md
```

## 🔧 Funcionalidades Implementadas

- ✅ Configuración inicial de Django
- ✅ Página de inicio con template base
- ✅ Sistema de URLs configurado
- ✅ Modelo de datos básico
- ✅ Panel de administración
- ✅ Vistas básicas (CBV y FBV)
- ✅ Integración con Bootstrap

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

### 4. Templates
- Sistema de herencia de templates
- Context processors
- Template tags y filters

## 🧪 Comandos Útiles

```bash
# Crear nueva aplicación
python manage.py startapp nombre_app

# Hacer migraciones
python manage.py makemigrations

# Aplicar migraciones
python manage.py migrate

# Ejecutar tests
python manage.py test

# Recopilar archivos estáticos
python manage.py collectstatic

# Shell interactivo de Django
python manage.py shell
```

## 🎓 Próximos Pasos

Esta aplicación base será extendida en futuras clases para incluir:

1. **APIs REST** con Django REST Framework
2. **Integración con modelos de ML** usando scikit-learn
3. **Implementación de algoritmos de IA**
4. **Visualización de datos** con Chart.js
5. **Deploy en la nube** (Heroku/AWS)

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

**Profesor:** Carlos Adrian Alarcon 

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