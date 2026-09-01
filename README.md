# Actualizaciones de las herramientas contables

Este repositorio es **publico a proposito**.  Los programas lo consultan sin
credenciales para saber si hay una version nueva; si fuera privado cada
consulta responderia 404 y el cliente creeria estar al dia mientras corre una
version vieja.  Ya paso una vez.

Aqui no hay codigo fuente ni datos de ningun cliente: solo binarios de
actualizacion y un numero de version por herramienta.

| Herramienta | Archivo de version | Codigo fuente |
|---|---|---|
| ContaYa / SiigoYa | Seccion **Releases** | privado |
| Pruebas de causacion | `pruebas-causacion/version.json` | privado |

## Como se publica una version nueva

1. Subir el `.exe` o el `.zip` a **Releases**.
2. Editar el `version.json` de la herramienta: subir `version`, apuntar `url`
   a la release y escribir en `notas` que cambio, en una frase que le sirva a
   quien lo va a leer.

El programa **avisa, no instala**.  Muestra el aviso y la persona decide.
