# 📖 [HU-XXX] Título descriptivo de la Historia de Usuario

## 👤 Historia de Usuario

* **Como** [tipo de usuario / rol]
* **Quiero** [acción, funcionalidad o comportamiento deseado]
* **Para** [beneficio, valor de negocio u objetivo esperado]

---

## 📌 Contexto y Descripción

*Breve resumen explicativo que aporte contexto adicional sobre el problema o la necesidad que esta historia busca resolver.*

---

## 🎨 Diseños / UX / UI (Si aplica)

* **Figma / Wireframes:** [Enlace al diseño en Figma / Zeplin / Miro]
* **Notas de UI/UX:** *(Ejemplo: Comportamiento de responsive, estados de carga, manejo de errores visuales)*

---

## ✅ Criterios de Aceptación

*Definición clara de las condiciones que deben cumplirse para dar por aceptada la historia. Pueden usarse escenarios tipo Dado/Cuando/Entonces (BDD) o una lista de verificación.*

### Escenario 1: [Nombre del escenario principal - Camino feliz]
* **Dado que** [contexto inicial o estado del usuario]
* **Cuando** [el usuario realiza una acción]
* **Entonces** [resultado o respuesta esperada del sistema]

### Escenario 2: [Manejo de errores o caso de borde]
* **Dado que** [contexto inicial]
* **Cuando** [ocurre una excepción o acción inválida]
* **Entonces** [el sistema debe reaccionar de X forma]

---

## 🛠️ Detalles Técnicos y Dependencias

* **Impacto estimado:** [Frontend / Backend / Base de Datos / Infraestructura]
* **APIs o Servicios involucrados:**
  * `POST /api/v1/ejemplo`
* **Dependencias con otros tickets:**
  * Bloqueado por: # [ID-ticket]
  * Bloquea a: # [ID-ticket]
* **Consideraciones de Seguridad / Performance:** *(Ej. Autenticación JWT, índice en BD, caché)*

---

## 📊 Estimación y Priorización

* **Prioridad:** [Alta / Media / Baja]
* **Puntos de Historia (Story Points):** [1 / 2 / 3 / 5 / 8 / 13]
* **Etiquetas / Labels:** `feature`, `frontend`, `backend`, `ux`

---

## Check Definition of Done (DoD)

Lista de control que el equipo debe cumplir antes de considerar completada esta issue:

- [ ] Criterios de aceptación probados y cumplidos.
- [ ] Código subido y PR revisado por un par.
- [ ] Pruebas unitarias e integración creadas y pasando.
- [ ] Documentación actualizada (si aplica).
- [ ] QA / Criterio del Product Owner validado en ambiente de Staging.