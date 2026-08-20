# Informe Integrado de Gestión IT — Tarea 2

* **Fecha de Emisión:** 15 de julio de 2026 (Fecha de corte del sistema)
* **Realizado por:** Sofi (Analista IT)
* **Responsable:** Danna Valencia
* **Estado General:** ⚠️ GESTIÓN COMPLETADA

---

## 1. Resumen General de la Tarea 2
Esta tarea consistió en la ejecución de una auditoría integral de accesos y licencias, y la resolución de 5 solicitudes (tickets) pendientes. El objetivo central fue asegurar el cumplimiento de las políticas internas de Alegra, eliminar brechas de seguridad críticas, optimizar recursos financieros y formalizar la respuesta a los usuarios finales.

---

## 2. Hallazgos de Auditoría (Punto 1)

Se llevó a cabo una auditoría cruzando datos de `usuarios.csv`, `licencias.csv` y `logins.csv`, resultando en los siguientes hallazgos clasificados por riesgo:

### 🔴 Riesgos Críticos (Acción Inmediata)
* **Jorge Ramírez (Retirado):** Cuentas activas (Google y Salesforce) e inicio de sesión no autorizado posterior al retiro.
* **`dev.externo@alegra.com`:** Acceso activo sin registro en base de datos.
* **`jperez@alegra.com`:** Acceso informal duplicado no registrado.

### 🟡 Riesgos Medios (Ineficiencias)
* **Inactividad > 60 días:** Licencias sin uso detectadas en Juan Pérez y María Fernanda López (violación de **Regla 4**).

### 🟢 Riesgos Bajos (Inconsistencias)
* **Pedro Salazar:** Error de fechas en registro.
* **Cuenta Compartida (`soporte.general@alegra.com`):** Falta de trazabilidad individual.

**Impacto Financiero de Optimización:** Ahorro mensual identificado de **$221.00 USD** ($2,652.00 USD anuales).

---

## 3. Gestión y Resolución de Tickets (Punto 2)

Se evaluaron 5 solicitudes pendientes aplicando las reglas corporativas:

| Ticket ID | Solicitante | Decisión | Justificación |
| :--- | :--- | :--- | :--- |
| **TICKET-001** | Ricardo Molina | 🔵 **Aprobado** | Cuenta con aprobación del líder de área (**Regla 3**). |
| **TICKET-002** | Santiago Vargas | 🟠 **Rechazado** | **Regla 1**: Practicante no recibe acceso administrador. |
| **TICKET-003** | Jorge Ramírez | 🟠 **Rechazado** | **Regla 2**: Ex-empleado no recibe extensión de acceso. |
| **TICKET-004** | Juan Pérez | 🔵 **Aprobado** | Consolidación de cuenta sin costo adicional (**Regla 3**). |
| **TICKET-005** | Laura Gómez | 🔵 **Aprobado** | **Regla 2/5**: Programado offboarding para 2026-07-31. |

---

## 4. Conclusión General de la Tarea
La gestión de esta tarea ha permitido corregir brechas de seguridad críticas de manera inmediata, optimizando los costos de licencias SaaS mediante la depuración de cuentas inactivas o duplicadas. La resolución de los tickets se ha realizado en estricto apego a las reglas de IT, garantizando una comunicación transparente con los usuarios y manteniendo la trazabilidad necesaria. Se recomienda la automatización del proceso de offboarding para prevenir futuras inconsistencias.

---

**Informe elaborado y certificado por:**

* **Sofi (Analista IT)**
* **Responsable:** Danna Valencia
* **Departamento:** Alegra IT Department
