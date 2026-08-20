# Playbook: Offboarding de usuario — IT Alegra

**Estado:** Aprobado y Activo
**Responsables:** Sofi (Analista IT) y Danna Valencia (Líder IT)

## Objetivo
Garantizar la desvinculación segura, completa y documentada de cualquier colaborador de la organización, cumpliendo estrictamente con las Reglas de IT de Alegra (suspensión inmediata, transferencia de activos y documentación obligatoria).

## Flujo de Trabajo (Día del Retiro)

### 1. Recepción y Validación
* Confirmar con People Ops: nombre, correo, área y fecha efectiva del retiro.
* Identificar todas las herramientas asignadas al usuario cruzando `data/usuarios.csv` y `data/licencias.csv`.

### 2. Ejecución Técnica
1. **Google Workspace:** Suspender la cuenta de usuario de inmediato en la consola de administración.
2. **Revocación de Licencias SaaS:** Acceder a las consolas de Salesforce, Figma, GitHub, etc., y revocar o cancelar las licencias activas para evitar cobros adicionales.
3. **Transferencia de Activos:** Transferir la propiedad de todos los archivos y carpetas del Google Drive corporativo del usuario saliente a su líder de área o a la cuenta designada por People Ops.
4. **Actualización de Datos:** Marcar el estado del usuario como "retirado" y registrar la fecha de retiro en `data/usuarios.csv`.

### 3. Checklist de Verificación
- [ ] Cuenta de Google Workspace suspendida.
- [ ] Acceso a Salesforce revocado.
- [ ] Acceso a Figma revocado.
- [ ] Acceso a GitHub revocado.
- [ ] Archivos de Drive transferidos (verificar con el líder de área).
- [ ] Estado del usuario actualizado en `data/usuarios.csv`.

### 4. Protocolo de Evidencias (Regla 5)
Toda acción debe ser documentada. Al finalizar, crear un archivo en `evidencia/offboarding-[usuario].md` que incluya:
* Nombre del usuario y fecha de ejecución.
* Checklist marcado (pasos 1 al 4).
* Capturas de pantalla o logs de los cambios realizados.
* Firma de los responsables de la ejecución.

---

## Procedimiento Reusable (Prompt para Sammy)

Para delegar este proceso al sub-agente **Sammy**, utiliza el siguiente prompt:

> "Eres Sammy, asistente técnico de IT en Alegra. Ejecuta el 'Playbook de Offboarding' para el usuario: `[email_usuario]`. 
> 1. Suspende su cuenta de Google Workspace.
> 2. Revoca todas sus licencias en `licencias.csv`.
> 3. Confirma la transferencia de archivos de Drive según el ticket asociado.
> 4. Actualiza `usuarios.csv`.
> 5. Genera el informe de evidencia firmado en `evidencia/offboarding-[usuario].md` siguiendo el protocolo de la Regla 5.
> Debes aplicar estrictamente las Reglas de IT de Alegra."

---

**Playbook elaborado y validado por:**

* **Sofi (Analista IT)**
* **Responsable:** Danna Valencia
