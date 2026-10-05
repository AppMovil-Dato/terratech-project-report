# Cierre de evidencias — TB1 / Sprint 1

Responsable de esta actualización: Bendezú Navarro, Rúbens Fitzgerald (`Lucemz`). Rama `feature/rubens-fitzgerald-tb1-sprint1`, creada desde `origin/develop` `1aa2092`, que incluía `main` `433e395`. Corte: 04/10/2026, America/Lima.

La sección 4.2.1 del README desarrolla los nueve subpuntos exigidos por el entregable. Los pendientes siguientes requieren información o evidencia real del equipo. No se reemplazan por actas, capturas ni resultados inventados.

## Evidencia ya incorporada

| Evidencia | Procedencia y alcance |
| --- | --- |
| Ocho capturas Android | APK Debug, emulador, backend Development y MySQL aislado: login, perfil, parcelas, sensor, indicadores, histórico, detalle y reapertura sin conexión. Directorio `assets/images/cap4/sprint1/` |
| Servicio Cloud Run | Captura proporcionada por Rúbens: servicio, región, dominio y métricas. `cloud-run-service.png`; no muestra revisión/porcentaje de tráfico |
| Backend | 61 casos aprobados; resumen extraído del TRX real, sin salidas que puedan contener datos sensibles. Cobertura histórica: 77.21 % líneas, 45.50 % ramas |
| Android | 32 unitarias de la revisión con dominio publicado; 14 instrumentadas de la validación aislada; build Debug y lint; recorrido Compose y reinicio offline |
| Artemis | Recorrido por clics y texto en emulador; 35 aserciones aprobadas, sin LLM. No equivale a prueba en teléfono físico |
| Despliegue | Estado de revisión Ready y 100 % tráfico filtrado del CLI, GET públicos con curl y comprobación del dominio. Evidencia histórica separada de la comprobación actual |
| Contratos y colaboración | Endpoints, respuestas, commits reales de backend/Android e historial de ramas del informe |

## Qué enviar para terminar el informe

| Pendiente | Información/captura solicitada | Dónde se incorpora |
| --- | --- | --- |
| Acta real de Sprint Planning | Fecha, hora, lugar/plataforma, asistentes reales, objetivo acordado y capacidad/velocidad comprometida. Confirmar la matriz LACX propuesta. Si no hubo reunión, indicar esa situación y registrar el acuerdo real posterior | 4.2.1.1 y 4.2.1.2 |
| Tablero del Sprint | Enlace público o acceso de lectura; captura con Sprint 1, IDs de las ocho HU, tareas, responsables y estados. Incorporar estimaciones en horas y estimación de HU-OFF01 acordadas; no derivarlas de los commits | 2.4.3 y 4.2.1.3 |
| Registro y errores Android | Captura del formulario con confirmación; validación de campos/contraseñas distintas; correo duplicado y credenciales incorrectas. No mostrar contraseñas ni datos personales reales | 4.2.1.5 y 4.2.1.6 |
| Recorrido en teléfono físico | Modelo, versión Android, commit/APK, fecha y resultado. Capturas de perfil guardado, parcela, sensor válido, rechazo de código inválido/ocupado, indicadores fechados con SIMULATED, histórico 7 y 30 días, detalle y aviso desactualizado | 4.2.1.6 |
| Offline físico | Descargar datos conectado; activar modo avión; cerrar completamente y reabrir. Capturar banner offline, fecha/antigüedad y datos conservados. Indicar que no se escriben datos sin red | 4.2.1.6 |
| Video público de ejecución | Enlace accesible sin pedir permisos al evaluador, mostrando registro/login → perfil → parcela → sensor → indicadores → histórico 7/30 → detalle → modo avión y reapertura. Se sugieren 3–5 minutos; esa duración es una propuesta, no un requisito atribuido al curso | 4.2.1.6 |
| Swagger | URL y método visibles; registro 201, duplicado 409, login 200 con token oculto y consulta autorizada 200. Capturar último dato/histórico mostrando unidades y fuente. Evitar JWT y contraseñas en cuerpos/headers | 4.2.1.7 |
| Revisión de Cloud Run | Revision History con `backend-terratech-git-00006-56x`, estado Ready y distribución de tráfico; si cambió, actualizar con la revisión realmente activa. La captura de observabilidad recibida ya está incluida | 4.2.1.8 |
| Build / imagen | Cloud Build con compilación exitosa, commit y hora; Artifact Registry con imagen/tag/digest de esa revisión. No usar el indicador de Build History de la captura recibida como prueba de éxito | 4.2.1.8 |
| Aiven / esquema | Vista de tablas y `__EFMigrationsHistory`, con migraciones Initial y Tb1Journey; si difieren, adjuntar resultado real. Ocultar usuario/contraseña, connection string, certificados privados y datos de cuentas | 4.2.1.8 |
| Colaboración por producto | Capturas GitHub de Contributors/Pulse/Network y PRs del backend, Android e informe, con intervalo del Sprint visible. Incluir Landing Page cuando exista. No atribuir trabajo a integrantes sin respaldo de commits o artefactos | 4.2.1.9 |
| Landing Page | Compañero responsable: repo/rama/commit, URL publicada, pantallas Desktop/Mobile reales, pruebas y evidencia de deploy. Los mockups del capítulo III son diseño, no acreditan publicación | 4.2.1.4–4.2.1.9 |
| Porcentaje funcional TB1 | Acordar con el docente denominador y ponderación de criterios; contrastar la matriz de historias del backend. El 77.21 % de cobertura no acredita el 70 % funcional pedido | Evaluación del hito, 4.2.1.8 |
| Exportación PDF | Regenerar desde el README al completar evidencias; comprobar tablas, nueve apartados, imágenes y enlaces. `informe.pdf` actual es una exportación anterior y no se presenta como actualizada | Entrega final |

## Preparar la demostración sin cambiar el significado de los datos

Las capturas incluidas utilizan un catálogo y lecturas simuladas cargadas explícitamente en Development. El backend Production crea la base/esquema cuando se configura `Database__MigrateOnStartup=true`, pero no crea cuentas, contraseñas, sensores de demostración ni mediciones automáticamente. Los comandos de demostración están bloqueados en Production.

Antes de grabar contra el dominio publicado, comprobar que existan un sensor disponible y lecturas autorizadas para la cuenta de demostración. Si la base está vacía, registrar la ausencia de datos y coordinar un procedimiento revisable de carga; no afirmar que la creación del esquema generó telemetría. No subir credenciales en este repositorio ni en las capturas.

Los resultados de emulador son válidos para el entorno aislado descrito. La actualización de API_URL y las pruebas unitarias no se presentan como un recorrido UI completo contra Production. Las entrevistas/validación con usuarios tienen evidencia propia en 4.3.

## Revisión antes de integrar

- Confirmar que esta rama mantiene los aportes recientes de `develop`.
- Ratificar responsables y datos de planificación, sin inventar horas.
- Reemplazar cada pendiente por evidencia con fecha, entorno y resultado.
- Verificar enlaces públicos, nombres de imágenes y ausencia de secretos.
- Revisar el informe en GitHub y el PDF exportado antes de integrar la rama.
