# Manual de validación de contraseñas para el sistema de rol de pagos

Este manual tiene como finalidad establecer reglas para validar que las contraseñas utilizadas en el sistema de rol de pagos sean robustas y seguras.

El sistema de rol de pagos maneja información sensible del personal, como sueldos, horas extras, bonificaciones, atrasos, IESS, comisiones, alimentación e impuesto a la renta. Por esta razón, el acceso debe estar protegido mediante contraseñas seguras.

## Reglas para validar una contraseña robusta

Una contraseña segura debe cumplir con las siguientes condiciones:

- Tener mínimo 8 caracteres.
- Incluir al menos una letra mayúscula.
- Incluir al menos una letra minúscula.
- Incluir al menos un número.
- Incluir al menos un carácter especial.
- No usar nombres de empleados.
- No usar fechas de nacimiento.
- No usar palabras como admin, password o 123456.
- No repetir contraseñas anteriores.
- No compartir la contraseña con otros usuarios.

## Ejemplos de contraseñas no permitidas

- 123456
- admin
- password
- soledad123
- rolpagos2026

## Ejemplos de contraseñas más seguras

- R0lP@gos2026*
- Su3ldo#Seguro
- Acc3so!Nomina
## Error detectado en la versión v1.3

Durante la revisión del sistema se detectó que la aplicación permitía registrar contraseñas débiles como:

- 123456
- admin
- password

Este error representa un riesgo para la seguridad, porque facilita accesos no autorizados al sistema y puede permitir que un atacante adivine credenciales fácilmente.
## Acción correctiva aplicada

Para corregir el error, se establece que el sistema debe rechazar contraseñas débiles y aplicar reglas mínimas de seguridad.

Una contraseña robusta debe cumplir con longitud mínima, uso de mayúsculas, minúsculas, números y caracteres especiales.

Con esta corrección se reduce el riesgo de accesos no autorizados y se mejora la seguridad del proceso de autenticación.
