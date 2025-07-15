# TEMPLATE UNIVERSAL - BIBLIOTECA TÉCNICA ISP

## 🎯 CÓMO USAR ESTE TEMPLATE

### FILOSOFÍA SIMPLE
1. **Empieza pequeño** - Documenta solo lo que usas frecuentemente
2. **Crece gradualmente** - Agrega contenido cuando lo necesites
3. **Mantén actualizado** - Revisa y actualiza cada 6 meses
4. **Hazlo práctico** - Si no lo usas, no lo documentes

### ESTRUCTURA DE CARPETAS
```
/Mi-Biblioteca-ISP/
├── /01-Equipos-Criticos/
├── /02-Procedimientos/
├── /03-Configuraciones/
├── /04-Contactos/
├── /05-Herramientas/
└── /06-Emergencias/
```

---

## 📁 01-EQUIPOS-CRITICOS

### TEMPLATE POR EQUIPO
```
## [NOMBRE EQUIPO] - [MODELO]

### INFORMACIÓN BÁSICA
- **Ubicación:** [Rack/Sala específica]
- **Función:** [Qué hace en tu red]
- **Clientes afectados:** [Cuántos se quedan sin servicio si falla]
- **Firmware actual:** [Versión instalada]

### DOCUMENTACIÓN
- [ ] Manual técnico (PDF)
- [ ] Backup configuración (archivo + fecha)
- [ ] Procedimiento básico troubleshooting
- [ ] Contacto soporte fabricante

### PROBLEMAS FRECUENTES
1. **Problema:** [Síntoma más común]
   - **Causa:** [Causa típica]
   - **Solución:** [Pasos para resolver]

2. **Problema:** [Segundo síntoma común]
   - **Causa:** [Causa típica]
   - **Solución:** [Pasos para resolver]

### COMANDOS ÚTILES
```
[Comando 1]: [Para qué sirve]
[Comando 2]: [Para qué sirve]
[Comando 3]: [Para qué sirve]
```

### CONTACTOS
- **Soporte:** [Teléfono + horario]
- **Distribuidor:** [Contacto local]
- **Interno responsable:** [Quién sabe de este equipo]
```

### EQUIPOS A DOCUMENTAR (PRIORIDAD)
- [ ] **Equipo #1** - [El que más problemas causa]
- [ ] **Equipo #2** - [El que afecta más clientes]
- [ ] **Equipo #3** - [El más crítico para funcionar]
- [ ] **Equipo #4** - [El más complejo de configurar]
- [ ] **Equipo #5** - [El que necesita más soporte]

---

## 📝 02-PROCEDIMIENTOS

### TEMPLATE PROCEDIMIENTO
```
# PROCEDIMIENTO: [NOMBRE]

## CUÁNDO USARLO
[Descripción de la situación que requiere este procedimiento]

## TIEMPO ESTIMADO
[Cuánto tarda típicamente]

## HERRAMIENTAS NECESARIAS
- [ ] [Herramienta física 1]
- [ ] [Software/acceso 1]
- [ ] [Materiales necesarios]

## PASOS
1. **[Paso 1]:** [Descripción detallada]
   - Verificar: [Qué confirmar]
   - Si falla: [Qué hacer]

2. **[Paso 2]:** [Descripción detallada]
   - Verificar: [Qué confirmar]
   - Si falla: [Qué hacer]

3. **[Paso 3]:** [Descripción detallada]
   - Verificar: [Qué confirmar]
   - Si falla: [Qué hacer]

## VALIDACIÓN FINAL
- [ ] [Verificación 1]
- [ ] [Verificación 2]
- [ ] [Verificación 3]

## QUÉ PUEDE SALIR MAL
- **Problema:** [Qué puede fallar]
  - **Solución:** [Cómo solucionarlo]

## CONTACTOS DE ESCALAMIENTO
- **Si no funciona:** [A quién llamar]
- **Si necesitas ayuda:** [Experto interno]
```

### PROCEDIMIENTOS ESENCIALES
- [ ] **Instalación nueva** - [Tu servicio principal]
- [ ] **Problema sin internet** - [Troubleshooting básico]
- [ ] **Equipo no responde** - [Diagnóstico L1]
- [ ] **Velocidad lenta** - [Diagnóstico performance]
- [ ] **Cambio de configuración** - [Modificaciones seguras]

---

## ⚙️ 03-CONFIGURACIONES

### TEMPLATE CONFIGURACIÓN
```
# CONFIGURACIÓN: [NOMBRE/PROPÓSITO]

## EQUIPO APLICABLE
[Marca/modelo específico]

## CUÁNDO USAR
[Situación que requiere esta configuración]

## CONFIGURACIÓN
```
[Código/comandos exactos]
```

## EXPLICACIÓN
- **Línea 1:** [Qué hace]
- **Línea 2:** [Qué hace]
- **Línea 3:** [Qué hace]

## ANTES DE APLICAR
- [ ] Backup configuración actual
- [ ] Verificar compatibilidad
- [ ] Planificar rollback si falla

## DESPUÉS DE APLICAR
- [ ] [Verificación 1]
- [ ] [Verificación 2]
- [ ] Documentar cambio

## ROLLBACK
```
[Comandos para deshacer si algo sale mal]
```
```

### CONFIGURACIONES BÁSICAS
- [ ] **Configuración inicial** - [Setup básico equipos]
- [ ] **VLAN estándar** - [Configuración redes]
- [ ] **QoS básico** - [Priorización tráfico]
- [ ] **Backup/restore** - [Respaldo configuraciones]
- [ ] **Monitoreo básico** - [SNMP, alertas]

---

## 📞 04-CONTACTOS

### TEMPLATE CONTACTO
```
## [NOMBRE/EMPRESA]

### INFORMACIÓN BÁSICA
- **Tipo:** [Proveedor/Fabricante/Interno]
- **Servicio:** [Qué nos proporciona]
- **Prioridad:** [Crítico/Importante/Útil]

### CONTACTOS
- **Soporte 24/7:** [Teléfono]
- **Soporte horario:** [Teléfono + horario]
- **Comercial:** [Contacto ventas]
- **Técnico:** [Contacto especializado]

### INFORMACIÓN CUENTA
- **Número cliente:** [ID con ellos]
- **Contrato:** [Tipo de servicio]
- **SLA:** [Tiempo de respuesta]

### NOTAS
- [Información útil sobre cómo trabajar con ellos]
- [Horarios especiales]
- [Procedimientos específicos]
```

### CONTACTOS ESENCIALES
- [ ] **Proveedor internet principal**
- [ ] **Proveedor internet backup**
- [ ] **Fabricante equipos críticos**
- [ ] **Distribuidor local**
- [ ] **Soporte eléctrico**
- [ ] **Soporte técnico externo**

---

## 🔧 05-HERRAMIENTAS

### TEMPLATE HERRAMIENTA
```
# HERRAMIENTA: [NOMBRE]

## TIPO
[Física/Software/Online]

## PARA QUÉ SIRVE
[Función principal en tu operación]

## CÓMO USAR
1. [Paso básico 1]
2. [Paso básico 2]
3. [Paso básico 3]

## VALORES NORMALES
- **Parámetro 1:** [Rango normal]
- **Parámetro 2:** [Rango normal]
- **Parámetro 3:** [Rango normal]

## CUÁNDO USAR
- [Situación 1]
- [Situación 2]
- [Situación 3]

## UBICACIÓN
[Dónde está físicamente o cómo acceder]

## CONTACTOS
- **Soporte:** [Si necesitas ayuda]
- **Mantenimiento:** [Calibración/servicio]
```

### HERRAMIENTAS BÁSICAS
- [ ] **Sistema de monitoreo** - [Tu NMS principal]
- [ ] **Herramienta medición** - [Instrumentos físicos]
- [ ] **Software configuración** - [Gestión equipos]
- [ ] **Herramienta diagnóstico** - [Troubleshooting]
- [ ] **Backup/documentación** - [Respaldos]

---

## 🚨 06-EMERGENCIAS

### TEMPLATE EMERGENCIA
```
# EMERGENCIA: [TIPO DE PROBLEMA]

## IDENTIFICACIÓN RÁPIDA
**Síntomas:**

- [Síntoma 1]
- [Síntoma 2]
- [Síntoma 3]

**Afectación:**

- [Cuántos clientes]
- [Qué servicios]
- [Zonas impactadas]

## PRIMEROS 5 MINUTOS
1. [Verificación crítica 1]
2. [Verificación crítica 2]
3. [Acción inmediata 1]
4. [Comunicación urgente]
5. [Iniciar diagnóstico]

## DIAGNÓSTICO RÁPIDO
- **Verificar:** [Qué revisar primero]
- **Comandos:** [Comandos de diagnóstico]
- **Herramientas:** [Qué usar para diagnosticar]

## SOLUCIONES RÁPIDAS
1. **Solución temporal:** [Para restaurar servicio rápido]
2. **Solución definitiva:** [Para resolver permanentemente]

## ESCALAMIENTO
- **Cuándo:** [Criterios para escalar]
- **A quién:** [Contacto específico]
- **Cómo:** [Método de contacto]

## COMUNICACIÓN
- **Clientes VIP:** [Mensaje y método]
- **Clientes masivos:** [Mensaje y método]
- **Interno:** [Quién informar]
```

### EMERGENCIAS PRINCIPALES
- [ ] **Sin internet total** - [Caída completa]
- [ ] **Sin internet parcial** - [Zonas afectadas]
- [ ] **Velocidad muy lenta** - [Degradación masiva]
- [ ] **Equipo crítico caído** - [Hardware principal]
- [ ] **Problema energía** - [Cortes eléctricos]

---

## 🚀 PLAN DE IMPLEMENTACIÓN

### SEMANA 1: FUNDACIÓN
- [ ] Crear estructura de carpetas
- [ ] Documentar equipo más crítico
- [ ] Escribir procedimiento más usado
- [ ] Crear lista contactos básicos

### SEMANA 2: EXPANSIÓN
- [ ] Agregar 2 equipos más
- [ ] Escribir 2 procedimientos más
- [ ] Completar contactos críticos
- [ ] Documentar herramientas básicas

### SEMANA 3: REFINAMIENTO
- [ ] Agregar configuraciones básicas
- [ ] Escribir procedimientos emergencia
- [ ] Probar documentación con equipo
- [ ] Hacer ajustes basados en feedback

### SEMANA 4: OPTIMIZACIÓN
- [ ] Completar documentación faltante
- [ ] Capacitar equipo en uso
- [ ] Establecer rutina de actualización
- [ ] Validar con casos reales

---

## 📊 MÉTRICAS DE ÉXITO

### INDICADORES SIMPLES
- [ ] **Tiempo resolución:** Se redujo al tener documentación
- [ ] **Escalamientos:** Menos llamadas a fabricantes
- [ ] **Capacitación:** Nuevos técnicos se adaptan más rápido
- [ ] **Consistencia:** Todos hacen lo mismo correctamente

### VALIDACIÓN MENSUAL
- [ ] **¿Usamos la biblioteca?** Si no, ¿por qué?
- [ ] **¿Está actualizada?** ¿Qué cambió?
- [ ] **¿Falta algo crítico?** ¿Qué problemas no están documentados?
- [ ] **¿Es fácil de usar?** ¿Qué mejorar?

---

## 💡 TIPS PARA MANTENER ACTUALIZADA

### RUTINA SEMANAL (15 minutos)
- Revisar si hubo problemas nuevos que documentar
- Actualizar contactos si cambiaron
- Verificar si hay actualizaciones de firmware

### RUTINA MENSUAL (1 hora)
- Revisar procedimientos más usados
- Actualizar configuraciones si cambiaron
- Validar que contactos funcionen

### RUTINA SEMESTRAL (4 horas)
- Revisar toda la biblioteca
- Eliminar información obsoleta
- Capacitar equipo en cambios
- Planificar mejoras

---

## ✅ CHECKLIST FINAL

### BIBLIOTECA MÍNIMA FUNCIONAL
- [ ] 3 equipos críticos documentados
- [ ] 3 procedimientos básicos escritos
- [ ] Contactos de emergencia actualizados
- [ ] 1 procedimiento de emergencia completo
- [ ] Estructura de carpetas organizada

### VALIDACIÓN PRÁCTICA
- [ ] Resolviste un problema usando solo la biblioteca
- [ ] Un compañero pudo seguir un procedimiento
- [ ] Encontraste información crítica en menos de 2 minutos
- [ ] La documentación está actualizada (menos de 6 meses)

**🎯 OBJETIVO:** Una biblioteca técnica que realmente uses y que te ahorre tiempo en situaciones críticas.

**📝 REGLA DE ORO:** Si no lo usas en 6 meses, elimínalo. Si lo usas seguido, mejóralo.