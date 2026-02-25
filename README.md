# Incidencias reales (Lab 26–35)

Esta sección agrupa incidencias típicas de entorno real: primero se reproduce el fallo, luego se identifica la causa y finalmente se documenta la resolución con evidencias (capturas).

> Objetivo: demostrar troubleshooting y buenas prácticas (no solo despliegue).

---

## Índice de incidencias

| Área | Lab | Incidencia | Qué se valida | Enlace |
|---|---:|---|---|---|
| Redes | 26 | IP Overlap en VNet Peering | Diagnóstico de solapamiento CIDR y corrección de address space | [Abrir Lab 26](zapata-antonio/incidencias/Lab-26-Incidencia-Solapamiento-de-IPs-en-VNet-Peering) |
| Identidad | 27 | MFA Lock-out Recovery (Break-glass) | Recuperación de acceso y re-registro de MFA | [Abrir Lab 27](../Azure-Lab-27-Incidencia-MFA-Lockout-Recovery/) |
| Sistemas | 28 | Extensión disco C: (Windows) | Resize en Azure + extend en el SO | [Abrir Lab 28](../Azure-Lab-28-Incidencia-Extend-OS-Disk/) |
| Storage | 29 | RBAC insuficiente en Blob | Plano de control vs plano de datos (Blob Data Contributor) | [Abrir Lab 29](../Azure-Lab-29-Incidencia-RBAC-Storage/) |
| PaaS | 30 | App Service Slots Rollback | Swap / rollback rápido con slots | [Abrir Lab 30](../Azure-Lab-30-Incidencia-AppService-Slots-Rollback/) |
| Redes | 31 | Puerto bloqueado por NSG | Identificación de regla y validación de conectividad | [Abrir Lab 31](../Azure-Lab-31-Incidencia-NSG-Port-Block/) |
| FinOps | 32 | Auto-shutdown | Control de costes con apagado programado | [Abrir Lab 32](../Azure-Lab-32-FinOps-AutoShutdown/) |
| Gobierno | 33 | Resource Locks (CanNotDelete) | Protección ante borrados accidentales | [Abrir Lab 33](../Azure-Lab-33-Governance-ResourceLocks/) |
| Identidad | 34 | PIM con aprobación | Activación con flujo de aprobación (si hay licencia) | [Abrir Lab 34](../Azure-Lab-34-PIM-Approval/) |
| BCDR | 35 | File Recovery desde Backup | Recuperación puntual sin restaurar VM completa | [Abrir Lab 35](../Azure-Lab-35-AzureBackup-FileRecovery/) |

---

## Nota sobre el entorno de laboratorio
Algunas incidencias dependen de licencias o planes (por ejemplo PIM con aprobación o slots de App Service). Si una práctica no es posible en la suscripción actual, se documenta la limitación y la alternativa recomendada.
