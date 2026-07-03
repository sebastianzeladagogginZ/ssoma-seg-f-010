# Sistema SSOMA · SEG-F-010

Herramienta digital de inspección de recursos y medios (RM 050-2013-TR) de OPTICAL NETWORKS S.A.C.

## Estructura

| Ruta | Herramienta | Usuarios |
|---|---|---|
| `/formulario/` | Auto-inspección de campo SEG-F-010 | Cuadrillas y técnicos |
| `/panel/` | Panel SSOMA de levantamiento de observaciones | Jefes de área y equipo SSOMA |

## Notas

- Sitio 100% estático (GitHub Pages). El backend corre en Google Apps Script
  y guarda los datos en Google Sheets + Drive.
- El acceso al panel se valida **en el servidor**; los usuarios listados en el
  código son ficticios (modo demostración).
- Para actualizar: editar los archivos y hacer commit — GitHub Pages
  republica automáticamente en 1-2 minutos.
