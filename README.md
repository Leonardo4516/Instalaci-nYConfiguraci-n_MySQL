# Instalación y Configuración de MySQL

## 👤 Información del Estudiante

- **Nombre completo:** Leonardo Andrés Hernández Hernández
- **Sistema Operativo:** Windows

---

## 📋 Proceso de Instalación

A continuación se describen los pasos seguidos para instalar **MySQL Server** y **MySQL Workbench**:

1. **Descarga:** Se descargó el instalador oficial desde el sitio web de MySQL ([dev.mysql.com](https://dev.mysql.com/downloads/)), seleccionando la versión correspondiente al sistema operativo utilizado.
2. **Configuración de usuario y contraseña:** Durante el proceso de instalación se configuró la contraseña del usuario `root`, el cual se utiliza para administrar el servidor.
3. **Finalización:** Se completó la instalación de MySQL Server junto con MySQL Workbench, y se verificó que el servicio del servidor quedara activo.

> *(Reemplaza este texto con el detalle real de tu instalación: complicaciones que tuviste, decisiones de configuración, puerto utilizado, etc.)*

---

## 🖼️ Galería de Evidencias

### Captura 1: Instalador / Descarga completada

### Captura 2: Configuración de la contraseña del usuario root

### Captura 3: MySQL Workbench - Conexión "Local Instance" creada

---

## ✅ Validación del Entorno

Para confirmar que la instalación fue exitosa, se ejecutó la siguiente consulta SQL dentro de una pestaña **Query** en MySQL Workbench:

```sql
-- Consulta de validación de entorno
SELECT VERSION() AS 'Versión de MySQL', 
       CURRENT_USER() AS 'Usuario Actual', 
       NOW() AS 'Fecha y Hora del Servidor';
```

**Resultado de la consulta:**

---

## 📁 Estructura del Repositorio

```
.
├── README.md
└── img/
    ├── captura1.png
    ├── captura2.png
    ├── captura3.png
    └── validacion.png
```
