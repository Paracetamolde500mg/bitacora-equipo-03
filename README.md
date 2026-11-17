# Bitácora de Incidentes de Ciberseguridad — Equipo 03

Servicio web RESTful desarrollado en **Python**, **Flask** y **SQLite** para el inventario de activos tecnológicos, registro de incidentes de ciberseguridad y seguimiento de resoluciones técnicas.

---

## Estructura del Proyecto

```text
bitacora-equipo03/
├── main.py                  # Punto de entrada y registro de blueprints
├── db.py                    # Conexión e inicialización de base de datos SQLite
├── schema.sql               # Esquema relacional (tablas activos e incidentes)
├── requirements.txt         # Dependencias del proyecto (Flask)
└── rutas/
    ├── activos.py           # Endpoints CRUD para activos
    ├── incidentes.py        # Endpoints para consulta y registro de incidentes
    └── resoluciones.py      # Endpoint para cierre y resolución de incidentes