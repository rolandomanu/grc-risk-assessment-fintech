1. Política de Control de Acceso
Versión: 1.0

Estatus: Borrador para Proyecto Fintech

Objetivo
Establecer los controles necesarios para asegurar que el acceso a los activos de información de la Fintech esté limitado a usuarios autorizados, basándose en el principio de mínimo privilegio.

Lineamientos Principales
Identificación Única: Cada usuario debe tener una cuenta individual e intransferible. Se prohíben las cuentas compartidas.

Autenticación Fuerte (MFA): Es obligatorio el uso de Autenticación Multi-Factor para acceder a la consola de AWS, bases de datos PCI y redes VPN.

Control de Acceso Basado en Roles (RBAC): Los permisos se asignarán según el perfil laboral (ej. Desarrollador, Auditor, Administrador).

Revisiones de Acceso: El equipo de GRC realizará revisiones de privilegios cada 90 días para dar de baja accesos innecesarios.

Mapeo de Controles: ISO 27001:2022 (A.5.15, A.8.5) | SOC 2 (CC6.1)

2. Política de Gestión de Vulnerabilidades
Versión: 1.0

Estatus: Borrador para Proyecto Fintech

Objetivo
Definir el proceso para identificar, evaluar y remediar debilidades técnicas en la infraestructura y aplicaciones para prevenir incidentes de seguridad.

Lineamientos Principales
Escaneo de Activos: Se realizarán análisis de vulnerabilidades mensuales en servidores y bases de datos, y trimestrales en aplicaciones web.

Clasificación de Severidad: Se utilizará el sistema CVSS (Common Vulnerability Scoring System) para priorizar hallazgos.

Plazos de Remediación:

Crítica (9.0-10.0): Máximo 48 horas.

Alta (7.0-8.9): Máximo 15 días.

Media (4.0-6.9): Máximo 30 días.

Gestión de Parches: Los sistemas deben actualizarse siguiendo el proceso de gestión de cambios para evitar interrupciones en el servicio.

Mapeo de Controles: ISO 27001:2022 (A.8.8) | NIST CSF (ID.RA-1)
