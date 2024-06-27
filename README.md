<p align="center">
  <a href="https://tesjo.edomex.gob.mx">
    <img src="https://github.com/Cobain21Jose/METODOS-NUMERICOS---Simulaci-n-de-Evoluci-n-Clim-tica-Modelo-de-Temperatura-y-Humedad-Relativa/blob/main/tesjo.png" alt="Logo de Ing en Sistemas Computacionales - Tesjo">
  </a>
</p>

# Ing en Sistemas Computacionales - Tesjo

**Alumna:** Estefania Lovera Cruz  
**Grupo:** IC-0202  
**Profesor:** Juan Alberto Antonio Velázquez

# Blog en Django

Este proyecto es un blog desarrollado con Django. Fue realizado por la alumna Estefanía Lovera Cruz del grupo IC-0202 bajo la supervisión del profesor Juan Alberto Antonio Velázquez.

## Tabla de Contenidos

1. [Activar el Entorno Virtual de Django](#activar-el-entorno-virtual-de-django)
2. [Estructura del Proyecto](#estructura-del-proyecto)
3. [Configuración del Proyecto](#configuración-del-proyecto)
4. [Ejecutar el Servidor](#ejecutar-el-servidor)
5. [Detalles del Diseño](#detalles-del-diseño)

## Activar el Entorno Virtual de Django

Para activar el entorno virtual, sigue los siguientes pasos:

1. Crea una carpeta para tu proyecto Django.
2. Navega a la carpeta creada desde el terminal (cmd) y asegúrate de que `django` y `python` estén instalados.
3. Ejecuta el siguiente comando para iniciar el servidor:
    ```bash
   python manage.py runserver

 4. Abre el enlace proporcionado (http://127.0.0.1:8000/) en tu navegador para verificar que el servidor esté funcionando correctamente.
    ```bash
    http://127.0.0.1:8000/

## Activar el Entorno Virtual de Django

## Estructura del Proyecto
La estructura básica del proyecto Django incluye varios archivos y carpetas predeterminadas. Aquí te mostramos cómo se ve una estructura típica:
   ```bash
    myproject/
    manage.py
    myproject/
        __init__.py
        settings.py
        urls.py
        wsgi.py
    app/
        __init__.py
        admin.py
        apps.py
        models.py
        tests.py
        views.py
        migrations/
```

## Ejecutar el Servidor

Para ejecutar el servidor de desarrollo de Django, sigue estos pasos:

1. Asegúrate de que el entorno virtual esté activado. Si no lo está, actívalo con el siguiente comando:
    ```bash
    .\env\Scripts\Activate
    ```

2. Navega al directorio del proyecto Django (donde se encuentra `manage.py`).

3. Ejecuta el siguiente comando para iniciar el servidor de desarrollo:
    ```bash
    python manage.py runserver
    ```

4. Abre el navegador y visita la siguiente dirección para ver el proyecto en funcionamiento:
    ```bash
    http://127.0.0.1:8000/
    ```

Si todo está configurado correctamente, deberías ver la página de inicio predeterminada de Django.

## Detalles del Diseño

El proyecto incluye varias secciones diseñadas con HTML y CSS. A continuación se muestran algunos ejemplos del código utilizado para el diseño del sitio:

### Ejemplo de HTML

```html
<!DOCTYPE html>
<html>
<head>
    <title>Blog de Django</title>
    <link rel="stylesheet" type="text/css" href="{% static 'css/style.css' %}">
</head>
<body>
    <header>
        <h1>Bienvenido a mi Blog</h1>
    </header>
    <nav>
        <ul>
            <li><a href="/">Inicio</a></li>
            <li><a href="/about/">Sobre mí</a></li>
            <li><a href="/projects/">Proyectos</a></li>
            <li><a href="/contact/">Contacto</a></li>
        </ul>
    </nav>
    <main>
        {% block content %}
        {% endblock %}
    </main>
    <footer>
        <p>&copy; 2024 Blog de Django. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
```
## Ejemplo de CSS
```html
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: #fff;
    padding: 1em 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 10px;
}

nav ul li a {
    text-decoration: none;
    color: #333;
}

main {
    padding: 2em;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1em 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}
```



        



