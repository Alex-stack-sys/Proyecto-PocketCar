1. Instalar y Configurar MySQL Workbench
Si aún no tienes MySQL Workbench instalado:

Descarga MySQL desde el sitio oficial: MySQL Community Downloads.
Instala MySQL Server y MySQL Workbench (ambos suelen venir juntos en el paquete).
Configura un usuario administrativo (por defecto es root) y define una contraseña segura.

2. Abrir MySQL Workbench y Conectarse
Inicia MySQL Workbench.
Haz clic en tu conexión (por ejemplo, Local instance MySQL).
Si no tienes una conexión configurada, selecciona New Connection y usa tus credenciales de MySQL Server.

4. Crear una Nueva Base de Datos
Abre una nueva ventana de consulta:
En la barra superior, haz clic en File > New Query Tab o usa el atajo Ctrl + T (Windows) o Cmd + T (Mac).
Ejecuta el siguiente comando para crear una base de datos:

CREATE DATABASE PocketCarDB;
Selecciona la base de datos para trabajar con ella:


USE PocketCarDB;

5. Crear las Tablas
Copia el código para crear las tablas, pero solo lo que no esta comentado.
Pega el código en la ventana de consulta de MySQL Workbench.
Haz clic en el ícono de "rayito" (Execute) o presiona Ctrl + Enter (Windows) o Cmd + Enter (Mac) para ejecutarlo.
Repite este proceso para todas las tablas que necesitas crear.

