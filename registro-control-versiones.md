# Registro de control de versiones del sistema de rol de pagos

| Versión | Ambiente | Cambio realizado | Responsable | Estado |
|---|---|---|---|---|
| v1.0 | Desarrollo | Creación inicial del sistema de rol de pagos | Soledad Argüello | Estable |
| v1.1 | Desarrollo | Creación login inicial | Soledad Argüello | Estable |
| v1.2 | Desarrollo | Manual de validación de contraseñas | Soledad Argüello | Estable |
| v1.3 | Certificación | Se detecta error: contraseñas débiles permitidas | Soledad Argüello | Con error |
| v1.2 | Certificación | Retorno a versión anterior estable | Soledad Argüello | Restaurada |
| v1.4 | Producción | Corrección final de validación de contraseñas | Soledad Argüello | Estable |

## Ambientes simulados

| Ambiente | Configuración | Fecha simulada |
|---|---|---|
| Desarrollo | Creación login inicial | ene-26 |
| Desarrollo | Manual validación contraseñas | ene-26 |
| Certificación | Error contraseñas débiles | feb-26 |
| Certificación | Retorno versión anterior v1.2 | mar-26 |
| Producción | Corrección final v1.4 | dic-26 |

## Recuperación de versión anterior

En la versión v1.3 se detectó un error de seguridad relacionado con contraseñas débiles. Como medida de control, se tomó como referencia la versión anterior estable v1.2. Luego se corrigió la validación de contraseñas y se generó la versión v1.4 para producción.
