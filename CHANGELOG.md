# 1.0.0 (2025-06-19)


### chore

* **ci:** Integra semantic-release para automatizar releases ([95b4112](https://github.com/teimas/test-terco/commit/95b4112dc9c7b5f46214d089f7572259ff8ddf8d))


### Features

* **ui, docs:** Añade proyecto web 'Pink Paradise' y documentación ([0b506dd](https://github.com/teimas/test-terco/commit/0b506dd1c11b89c4ef40db59d409b751d38e3d2b))


### BREAKING CHANGES

* **ci:** El endpoint /api/users ha sido eliminado.`
   - Fusiona el Pull Request.
   - **Verificación:** Confirma que el workflow crea una nueva release de tipo 'major' (ej: de v1.1.0 a v2.0.0). Asegúrate de que las notas de la release destacan claramente el breaking change.

Security: Se ha añadido el archivo `debug.log` al repositorio. Los archivos de log pueden contener información sensible como variables de entorno, tokens de sesión, rutas de archivos del sistema o datos de usuario que se estaban depurando. Versionar este archivo expone esta información a todos los que tienen acceso al repositorio, representando un riesgo de fuga de información. Se recomienda encarecidamente eliminar el archivo `debug.log` del historial de Git y añadir `*.log` a `.gitignore` para prevenir futuras inclusiones accidentales.

Migraciones Lentas: N/A

Partes a Ejecutar: N/A

JIRA TASKS: N/A
