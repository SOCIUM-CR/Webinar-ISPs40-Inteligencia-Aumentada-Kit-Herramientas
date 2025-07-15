# Constructor de Consultor de Biblioteca Técnica - ISP

Necesito que me ayudes a construir mi **PERFIL DE CONSULTOR DE BIBLIOTECA TÉCNICA** para mi ISP. Este perfil me permitirá obtener las preguntas exactas que debo hacerle a mi biblioteca técnica según el problema específico que tenga.

**MI OBJETIVO:** Crear un documento que contenga toda la información sobre mi infraestructura técnica y tipos de problemas para que puedas generar las preguntas precisas que me ayuden a encontrar la solución en mi documentación.

**PROCESO QUE QUIERO SEGUIR:**

1. Hazme UNA pregunta específica por vez
2. Espera mi respuesta completa antes de continuar
3. Haz preguntas de seguimiento para obtener detalles específicos
4. No aceptes respuestas genéricas - empújame a ser específico
5. Al final, genera mi PERFIL DE CONSULTOR DE BIBLIOTECA TÉCNICA completo

**CONTEXTO INICIAL DE MI ISP:**

- Nombre: [COMPLETA: Nombre de tu ISP]
- Tecnología principal: [COMPLETA: FTTH, DOCSIS, WISP, etc.]
- Equipos principales: [COMPLETA: Marcas y modelos críticos]
- Tamaño de red: [COMPLETA: Clientes, nodos, complejidad]
- Tipos de documentación: [COMPLETA: Manuales, configuraciones, procedimientos]
- Problemas frecuentes: [COMPLETA: Qué fallas típicas tienes]

**ESTRUCTURA OBJETIVO - Mi perfil debe incluir:**

## 1. INVENTARIO DE DOCUMENTACIÓN
- Manuales técnicos: Por fabricante, modelo, versión
- Guías de configuración: Por equipo, por servicio, por escenario
- Procedimientos operativos: Instalación, mantenimiento, troubleshooting
- Documentación de red: Topología, diagramas, especificaciones
- Regulaciones y estándares: Normativas, compliance, certificaciones

## 2. EQUIPOS Y TECNOLOGÍAS
- Equipos core: Modelos específicos, versiones firmware, capacidades
- Equipos de acceso: Tecnologías, configuraciones, limitaciones
- Infraestructura soporte: Energía, clima, seguridad, monitoreo
- Herramientas diagnóstico: Software, hardware, accesos, procedimientos
- Integraciones: Sistemas conectados, APIs, interfaces

## 3. TIPOS DE PROBLEMAS FRECUENTES
- Conectividad: Fallas de enlace, problemas de acceso, degradación
- Configuración: Errores de setup, incompatibilidades, actualizaciones
- Rendimiento: Latencia, throughput, congestión, optimización
- Seguridad: Vulnerabilidades, accesos, políticas, incidents
- Operación: Monitoreo, mantenimiento, procedimientos, escalamiento

## 4. CONTEXTO DE RESOLUCIÓN
- Niveles de urgencia: Crítico, alto, medio, bajo - criterios específicos
- Impacto de usuarios: Cuántos afectados, tipos de clientes, SLA
- Recursos disponibles: Personal, herramientas, tiempo, presupuesto
- Escalamiento: Cuándo, a quién, cómo, criterios de decisión
- Documentación: Qué registrar, cómo, dónde, seguimiento

## 5. PATRONES DE CONSULTA
- Diagnóstico inicial: Qué información necesito primero
- Investigación profunda: Qué detalles técnicos buscar
- Validación de soluciones: Cómo confirmar procedimientos
- Implementación: Qué pasos seguir, qué verificar
- Prevención: Cómo evitar recurrencia, mejoras

**INSTRUCCIONES ESPECÍFICAS:**

1. **SÉ INSISTENTE:** Si digo "problemas de red", pregúntame tipos específicos, equipos afectados, síntomas.

2. **BUSCA ESPECIFICIDAD:** Si digo "manuales técnicos", pregúntame fabricantes exactos, modelos, versiones.

3. **VALIDA COMPLETITUD:** Si una sección parece incompleta, haz preguntas adicionales específicas.

4. **ENFÓCATE EN PROBLEMAS REALES:** Cada elemento debe reflejar situaciones que realmente enfrento.

5. **PIENSA EN CONSULTAS:** Las preguntas deben ayudarte a generar consultas precisas para mi biblioteca.

**EJEMPLO DE PREGUNTA BUENA:**

"¿Cuáles son los 3 tipos de problemas más frecuentes que tienes con tu OLT Huawei MA5608T y qué síntomas específicos observas en cada caso?"

**EJEMPLO DE PREGUNTA MALA:**

"¿Qué problemas tienes?"

**VALIDACIÓN FINAL:**

Cuando terminemos, el perfil debe permitirte generar consultas como:

- Para problema de conectividad: "Lista de 5 preguntas específicas para consultar manuales"
- Para problema de configuración: "Secuencia de consultas para validar procedimientos"
- Para problema de rendimiento: "Preguntas diagnósticas para documentación técnica"

Con resultados como:

- Preguntas específicas para mi tecnología exacta
- Consultas que consideran mi nivel de documentación
- Secuencias lógicas de investigación técnica

**¿ESTÁS LISTO PARA COMENZAR?**

Por favor, haz tu primera pregunta sobre qué tipos de documentación técnica tengo organizada.

---

## RESULTADO FINAL ESPERADO

Al completar este proceso, obtendrás un **PERFIL DE CONSULTOR DE BIBLIOTECA TÉCNICA** estructurado así:

```markdown
# PERFIL DE CONSULTOR DE BIBLIOTECA TÉCNICA - [NOMBRE ISP]

## INVENTARIO DE DOCUMENTACIÓN
- Manuales Huawei: MA5608T v8.0, MA5800 v10.1, ONT HG8546M
- Configuraciones Cisco: 3850 series, 2960 series, templates VLAN
- Procedimientos: Instalación FTTH, troubleshooting L1-L3, mantenimiento preventivo
- Diagramas red: Topología física, lógica, VLAN design, IP addressing
- Normativas: IFT México, IEEE 802.1Q, ITU-T G.984 GPON

## EQUIPOS Y TECNOLOGÍAS
- Core: Huawei MA5608T (8 puertos GPON, 1024 ONTs), Cisco 3850 (48 puertos)
- Acceso: GPON 2.5G down/1.25G up, cobertura 20km, splitters 1:32
- Soporte: UPS APC, aires acondicionados, Zabbix monitoring
- Diagnóstico: Reflectómetro EXFO, power meter, laptop configuración
- Integraciones: Radius server, DHCP pool, billing system CRM

## TIPOS DE PROBLEMAS FRECUENTES
- Conectividad: Fibra cortada (60%), ONT sin luz (25%), OLT caído (15%)
- Configuración: VLAN incorrecta, perfil ONT mal asignado, QoS issues
- Rendimiento: Congestión upstream, latencia alta, packet loss
- Seguridad: Accesos no autorizados, vulnerabilidades firmware
- Operación: Alarmas falsas, mantenimiento programado, expansión

## CONTEXTO DE RESOLUCIÓN
- Crítico: >100 clientes afectados, clientes VIP, <2h resolución
- Alto: 50-100 clientes, clientes empresariales, <4h resolución
- Medio: 10-50 clientes, residenciales, <8h resolución
- Bajo: <10 clientes, mejoras, <24h resolución

## PATRONES DE CONSULTA
- Diagnóstico: Síntomas → Causas probables → Verificaciones
- Investigación: Manuales técnicos → Procedimientos → Configuraciones
- Validación: Best practices → Compatibilidad → Precauciones
- Implementación: Paso a paso → Verificaciones → Rollback
- Prevención: Root cause → Monitoring → Mejoras
```

**CÓMO USAR EL PERFIL RESULTANTE:**

Una vez construido, úsalo comenzando futuras conversaciones con:
"Basándote en mi Perfil de Consultor de Biblioteca Técnica [adjuntar], genera las preguntas exactas que debo hacer a mi biblioteca para resolver: [descripción del problema]"

**EJEMPLO DE RESPUESTA ESPECÍFICA:**

En lugar de: "Busca información sobre problemas de red"
Obtendrás: "Hazle estas 5 preguntas específicas a tu biblioteca: 1) ¿Cuál es el procedimiento exacto para diagnosticar pérdida de señal en ONT HG8546M según manual Huawei? 2) ¿Qué valores de potencia óptica son normales para GPON 20km según especificaciones? 3) ¿Cuáles son los pasos de troubleshooting L1 para fibra cortada según procedimiento interno? 4) ¿Qué comandos CLI usar en MA5608T para verificar estado puerto GPON? 5) ¿Cuál es protocolo de escalamiento para fallas >100 clientes según manual operativo?"