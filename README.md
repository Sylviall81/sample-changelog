# Change Log
Todos los cambios notables en este proyecto se documentarán en este archivo.

El formato se basa en [Keep a Changelog](http://keepachangelog.com/)
y este proyecto se adhiere a [Semantic Versioning](http://semver.org/).


## [2.0.0] - 2024-09-15
### Changed
- **Migración del sistema de base de datos de MySQL a PostgreSQL**
  - Se ha completado la migración de todos los datos de MySQL a PostgreSQL.
  - **Consultas SQL:** Todas las consultas SQL en la aplicación han sido revisadas y modificadas para ser compatibles con PostgreSQL.
  - **Configuración del Sistema:** La configuración del entorno se ha actualizado para soportar PostgreSQL.
  - **NOTA:** Este cambio puede requerir ajustes adicionales en entornos personalizados de los clientes y una breve ventana de mantenimiento para la migración de datos.

## [1.1.0] - 2024-07-02
### Added
- **Nueva opción de lista de deseos para el usuario registrado**
  - Se añadió una funcionalidad que permite a los usuarios registrados crear y gestionar una lista de deseos.
  - **Interfaz de Usuario:** Actualizaciones en la interfaz para soportar la nueva lista de deseos.
  - **Backend:** Nuevos endpoints API para gestionar la lista de deseos.

## [1.0.1] - 2024-06-15
### Fixed
- **Corrección de un bug en las notificaciones de re-stock de producto**
  - Se solucionó un problema que causaba el envío duplicado de notificaciones cuando un producto volvía a estar en stock.
  - **Sistema de Notificaciones:** Optimización del código para evitar duplicados.
  - **Test de Regressión:** Se añadieron pruebas adicionales para asegurar que este error no vuelva a ocurrir.
