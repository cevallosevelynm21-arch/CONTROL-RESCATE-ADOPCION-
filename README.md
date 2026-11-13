# Sistema de Control de Rescate y Adopción

Proyecto académico de maquetación con HTML5 semántico.

## Archivos
- `index.html`: página principal.
- `reportar.html`: formulario de registro con validación HTML nativa.
- `rescates.html`: tabla demostrativa de reportes y descripción de estados.

## Ejecución
Descarga el proyecto y abre `index.html` en un navegador. Los tres archivos deben permanecer en la misma carpeta para que funcionen los enlaces.

## Validación W3C
Valida individualmente los tres archivos en https://validator.w3.org/ y corrige cualquier error o advertencia pertinente antes de tomar las capturas.

## Git y GitHub
Ejemplo de flujo solicitado:
```bash
git init
git add .
git commit -m "chore: estructura inicial del proyecto"
git branch -M develop
git switch -c feature/maquetacion-html
git add index.html reportar.html rescates.html README.md
git commit -m "feat: crear maquetacion semantica HTML5"
git push -u origin feature/maquetacion-html
```
Crea un Pull Request desde `feature/maquetacion-html` hacia `develop` en GitHub y realiza la integración cuando hayas revisado los cambios. Añade el remoto `origin` con la URL real de tu repositorio antes de ejecutar `git push`.

## Nota
Los registros de `rescates.html` son datos ficticios de demostración. El formulario utiliza `action="#"` y no almacena ni envía datos a un servidor; demuestra estructura y validación del lado del navegador.
