# Huellas de Esperanza — Actividad DSI Unidad 2

Prototipo estructural HTML5 para control de rescate y adopción animal.

## Archivos
- `index.html`: panel principal y resumen.
- `reportar.html`: formulario de ingreso con categoría, urgencia y descripción.
- `rescates.html`: tabla con datos ficticios de demostración.
- `assets/img/`: carpeta reservada para recursos gráficos.
- `evidencias/`: capturas ilustrativas incluidas en el informe.

## Ejecución
Abra `index.html` con un navegador moderno. No requiere servidor, dependencias, CSS ni JavaScript.

## Alcance
Es un prototipo de maquetación. El formulario utiliza envío GET de demostración y no almacena datos; la tabla contiene registros ficticios estáticos. Para producción se requerirían backend, base de datos, autenticación, controles de privacidad y validación del lado del servidor.

## Gitflow solicitado
```bash
git init
git add .
git commit -m "chore: estructura inicial del proyecto"
git branch -M main
git checkout -b develop
git checkout -b feature/maquetacion-html
# realizar cambios y guardar
git add .
git commit -m "feat: crear estructura HTML5 de rescate y adopcion"
git checkout develop
git merge --no-ff feature/maquetacion-html
```
Después, vincule el repositorio remoto de GitHub y publique las ramas. No se incluye URL porque el repositorio debe crearse desde la cuenta del estudiante.

## Validación
Validar cada archivo con https://validator.w3.org/nu/ (opción de carga de archivo). El paquete incluye revisión estructural local, pero no afirma una validación remota de W3C. Adjunte la captura real del resultado cuando realice ese paso.
