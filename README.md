# Sistema de Gestión de Incidencias Tecnológicas

Aplicación web desarrollada en PHP y MySQL para la gestión, control y seguimiento de incidencias tecnológicas en laboratorios de computación, correspondiente a la evaluación práctica de Programación Avanzada (ISB-32).

## Requisitos Previos
- Servidor local compatible con PHP y MySQL, como XAMPP.

## Instalación y Configuración

1. **Clonar o descargar el repositorio**:
   - Ubique la carpeta del proyecto dentro del directorio `htdocs` del servidor local (`C:/xampp/htdocs/gestor-incidencias`).

2. **Configurar la Base de Datos**:
   - Acceda a phpMyAdmin desde XAMPP.
   - Cree una base de datos denominada `gestor_incidencias`.
   - Importe el archivo `gestor_incidencias.sql` incluido en el repositorio.

3. **Verificar la Conexión**:
   - El archivo `conexion.php` se encuentra configurado para una conexión local estándar (`host: localhost`, usuario: `root`, sin contraseña).

4. **Ejecutar la Aplicación**:
   - Ingrese al navegador web y acceda a la ruta:
     `http://localhost/gestor-incidencias/index.php`

## Credenciales de Acceso Administrativo
- **Usuario**: `admin`
- **Contraseña**: `12345`
-
