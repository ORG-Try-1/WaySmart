# 🚀 Pull Request: [Título breve del cambio / ID del Ticket]

## 📌 Contexto y Tipo de Usuario
- **Ticket / Issue:** [ENLACE-1234](https://jira.ejemplo.com/browse/ENLACE-1234)
- **Tipo de Usuario Afectado:** *(Ej. Cliente final, Administrador del sistema, Usuario anónimo, Operador de soporte)*
- **Historia de Usuario:** 
  > **Como** [tipo de usuario]  
  > **Quiero** [funcionalidad o acción solicitada]  
  > **Para** [beneficio u objetivo perseguido]

---

## 📝 Descripción del Cambio
*Resumen técnico o funcional claro sobre lo que se implementó, corrigió o refactorizó en este PR.*

### Tipo de Cambio
- [ ] 🐛 **Fix** (corrección de errores que no rompe compatibilidad)
- [ ] ✨ **Feat** (nueva funcionalidad para el usuario)
- [ ] 💥 **Breaking Change** (cambio que rompe o altera la funcionalidad existente)
- [ ] 🛠️ **Refactor** (optimización de código sin cambios funcionales)
- [ ] 📚 **Docs** (actualización de documentación)
- [ ] ⚙️ **Chore / Infra** (configuración, CI/CD, dependencias)

---

## ✅ Criterios de Aceptación
Marca con una `x` los criterios definidos en el ticket que han sido verificados:
- [ ] **Criterio 1:** [Descripción del criterio de aceptación 1]
- [ ] **Criterio 2:** [Descripción del criterio de aceptación 2]
- [ ] **Criterio 3:** [Casos de borde o manejo de errores esperado]

---

## 📸 Posibles Evidencias
*(Adjunta capturas de pantalla, GIFs, videos del flujo, logs o pruebas de endpoints que demuestren el correcto funcionamiento).*

### Visuales / UI (Si aplica)
| Antes | Después |
| :---: | :---: |
| *(Captura o N/A)* | *(Captura de la solución)* |

### Backend / API / Base de Datos (Si aplica)
- **Resultados de Pruebas Unitarias / Cobertura:** *(Adjuntar captura o reporte del runner de pruebas)*
- **Pruebas de Integración / Postman:** *(Captura de respuestas de API exitosas/fallidas)*
- **Logs relevantes:** *(Snippet o captura de logs si aplica)*

---

## 📋 Lista de Chequeo del Autor (Self-Review)
Antes de asignar a los revisores, confirma que has completado los siguientes pasos:
- [ ] Mi código sigue la guía de estilos de este proyecto.
- [ ] Realicé una autorrevisión manual (*self-code-review*) de mis cambios.
- [ ] Escribí o actualicé las pruebas unitarias/integración correspondientes.
- [ ] Todas las pruebas automatizadas locales pasaron exitosamente.
- [ ] No introduje *warnings* ni *logs* innecesarios (ej. `console.log`, `print` de depuración).
- [ ] La documentación fue actualizada si el cambio lo requería (Swagger, README, etc.).

---

## 🛡️ Revisión del Líder / Tech Lead

*Sección reservada para el Líder Técnico / Revisor principal.*

### Checklist de Calidad Técnica
- [ ] **Arquitectura y Estándares:** El diseño se acopla a las buenas prácticas y arquitectura del proyecto.
- [ ] **Seguridad y Rendimiento:** No presenta vulnerabilidades evidentes (OWASP, inyecciones, fuga de datos) ni cuellos de botella de rendimiento.
- [ ] **CI/CD & Builds:** El pipeline de compilación y pruebas automatizadas se ejecutó correctamente sin fallos.
- [ ] **Estrategia de Despliegue:** No requiere migraciones complejas o las variables de entorno necesarias ya fueron configuradas en el entorno destino.

### Estado de Aprobación
- Status: **[ ] APROBADO** | **[ ] REQUIERE CAMBIOS** | **[ ] RECHAZADO**
- **Notas del Líder:**  
  > *(Comentarios finales, observaciones sobre deuda técnica o sugerencias de mejora si aplican)*

- **Firma / Revisor:** `@usuario_lider` - *[Fecha]*