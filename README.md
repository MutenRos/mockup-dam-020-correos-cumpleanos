# 020 -- Correos de cumpleanos

> Proyecto 020 del bloque DAM 1.o - 3.a evaluacion. Esta es **nuestra version**: la del enunciado de Jocarsa **completada y ampliada**.

## Descripcion

Servicio que envia automaticamente correos personalizados de felicitacion en la fecha de cumpleanos.

**Stack tecnologico:** Python Â· SMTP Â· CSV/SQLite Â· cron

**Punto de entrada:** `001-direccion de la hoja de calculo.py` (Python)

## Como ejecutar

```ash
python "001-direccion de la hoja de calculo.py"
```

## Estructura

- [FILE] `001-direccion de la hoja de calculo.py`
- [FILE] `002-consumo de datos.py`
- [FILE] `003-comprobar cumpleaños.py`
- [FILE] `004-enviar correo.py`
- [FILE] `005-correo HTML.py`
- [FILE] `README.md`

## Mejoras respecto a la version original

Plantilla HTML personalizada, scheduler robusto y log de envios.

Cambios transversales aplicados a todas las versiones nuestras:

- Limpieza de archivos temporales y artefactos pesados (node_modules, binarios, .blend recompilables).
- README profesional documentando ejecucion y estructura.
- Publicacion como repositorio independiente y mockup en GitHub Pages para captura de evidencias.

## Enlaces

| Recurso | URL |
|---------|-----|
| Repositorio (codigo) | <https://github.com/MutenRos/dam-020-correos-cumpleanos> |
| Repositorio mockup | <https://github.com/MutenRos/mockup-dam-020-correos-cumpleanos> |
| GitHub Pages (demo) | <https://mutenros.github.io/mockup-dam-020-correos-cumpleanos/> |

## Variantes del proyecto

Este proyecto se entrega en tres carpetas:

| # | Carpeta | Que es |
|---|---------|--------|
| 1 | `1-jocarsa-intacta/` | Version del profesor sin tocar (referencia). |
| 2 | `2-nuestra-version/` | **Esta carpeta**: nuestra version completada y mejorada. |
| 3 | `3-mockup-pages/` | Mockup estatico publicado en GitHub Pages para capturas/grabacion. |

---

_Ultima actualizacion: 2026-05-07_
