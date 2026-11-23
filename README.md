# Práctica T03 — Informe THD: HBX Group (Hotelbeds)

Informe técnico sobre las **tecnologías habilitadoras digitales (THD)** presentes en **HBX Group**, empresa TIC (*TravelTech*) con sede en Palma (Islas Baleares).

**Módulo:** 1º DAW - DIGI · **Integrantes:** Manel y Sergi

## Entrega

- 📄 **Informe final en PDF:** [`Informe_THD_HBX_Group.pdf`](Informe_THD_HBX_Group.pdf)
- 📝 **Informe completo en Markdown:** [`informe-thd-hbx-group.md`](informe-thd-hbx-group.md)

## Estructura del repositorio

```
├── README.md
├── informe-thd-hbx-group.md        # Informe completo (unión de las secciones)
├── Informe_THD_HBX_Group.pdf       # Versión final exportada a PDF
├── img/
│   └── esquema-it-ot.svg           # Esquema de integración IT-OT
└── secciones/
    ├── 01-portada-datos-resumen.md          # Sergi
    ├── 02-thd-cloud-bigdata.md              # Sergi
    ├── 03-thd-ia-ciberseguridad-iot.md      # Manel
    └── 04-esquema-conclusiones-fuentes.md   # Manel
```

## Reparto del trabajo y ramas

| Integrante | Rama | Partes del informe |
|---|---|---|
| Sergi | `sergi` | Portada, datos de la empresa, resumen ejecutivo, THD 1 (cloud) y THD 2 (Big Data) |
| Manel | `manel` | THD 3 (IA), THD 4 (ciberseguridad), THD 5 (IoT), THD no utilizadas, esquema IT-OT, conclusiones y fuentes |
| Ambos | `entrega-final` | Unión de las secciones en un único documento y exportación a PDF (rama nueva creada tras fusionar las anteriores en `main`) |

Flujo seguido:

1. Se crea el repositorio con la rama `main`.
2. Cada integrante crea su rama de trabajo desde `main` y sube sus secciones.
3. Cada rama se fusiona (*merge*) en `main` mediante una *pull request*.
4. Para los cambios posteriores a la fusión (unir el informe y generar el PDF) se crea una rama nueva, `entrega-final`, que también se fusiona en `main`.
