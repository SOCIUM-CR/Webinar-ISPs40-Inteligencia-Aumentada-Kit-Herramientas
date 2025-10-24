# Células de Conocimiento Pragmáticas
## Framework Simplificado para Empresas Reales

---

## Filosofía Central

Las células de conocimiento deben resolver problemas específicos y recurrentes de manera inmediata. No son repositorios de información general, sino **soluciones probadas para situaciones concretas** que se pueden reutilizar y mejorar.

### Principios Fundamentales
1. **Especificidad sobre generalidad**: "Cómo manejar cliente que amenaza cancelar por precio" vs "Gestión de clientes"
2. **Acción sobre teoría**: Pasos concretos, no conceptos abstractos
3. **Trigger claro**: Obviamente cuándo usarla
4. **Resultado medible**: Sabes si funcionó
5. **Captura el "secreto"**: El insight que marca la diferencia

---

## Template Básico de Célula

```markdown
# CÉLULA: [Problema Específico que Resuelve]

## Cuándo usar esto
- [Situación específica A]
- [Situación específica B] 
- [Señales de que necesitas esta célula]

## El "truco" que marca la diferencia
[El insight clave que hace que esto funcione bien - máximo 2-3 líneas]

## Proceso (paso a paso)
1. **[Acción concreta]** - [Por qué es importante]
2. **[Acción concreta]** - [Punto de validación]
3. **[Acción concreta]** - [Resultado esperado]

## Cómo saber que funcionó
- [Indicador concreto 1]
- [Indicador concreto 2]

## Si algo sale mal
- **Problema común**: [Solución rápida]
- **Red flag**: [Qué hacer]

## Se conecta con
- [[Célula que usas antes]]
- [[Célula que usas después]]
- [[Célula alternativa para caso X]]

---
*Última actualización: [fecha] | Usos exitosos: [contador]*
```

---

## Tipología de Células por Utilidad Real

### Tipo 1: Células de Troubleshooting
**Propósito**: Resolver problemas específicos y recurrentes
**Características**:
- Diagnóstico paso a paso
- Múltiples rutas según síntomas
- Conexiones en cadena de escalamiento

**Ejemplo de nombre**: 
- "Cliente reporta internet lento pero speed test da normal"
- "Servicio funciona pero cliente insatisfecho con velocidad"

**Patrón de conexiones**:
```
[[Diagnóstico inicial]] → [[Problema de hardware]] → [[Reemplazo de equipo]]
                       → [[Problema de configuración]] → [[Ajuste remoto]]
                       → [[Problema de expectativas]] → [[Comunicación con cliente]]
```

### Tipo 2: Células de Comunicación Crítica
**Propósito**: Manejar conversaciones difíciles o importantes
**Características**:
- Scripts o frameworks probados
- Variaciones según tipo de interlocutor
- Manejo de objeciones comunes

**Ejemplo de nombre**:
- "Explicar aumento de precios sin perder cliente"
- "Convertir queja en oportunidad de mejora"

**Patrón de conexiones**:
```
[[Preparación de conversación]] → [[Conversación principal]] → [[Seguimiento post-conversación]]
                                 ↓
                               [[Manejo de objeciones]]
                                 ↓  
                               [[Escalamiento gerencial]]
```

### Tipo 3: Células de Decisión
**Propósito**: Tomar decisiones complejas consistentemente
**Características**:
- Criterios de evaluación claros
- Matriz de decisión estructurada
- Documentación de rationale

**Ejemplo de nombre**:
- "Evaluar viabilidad de zona para expansión"
- "Decidir si cliente merece descuento especial"

**Patrón de conexiones**:
```
[[Recolección de datos]] → [[Evaluación de criterios]] → [[Decisión final]]
                                      ↓
                               [[Casos especiales]] → [[Escalamiento a gerencia]]
```

### Tipo 4: Células de Ejecución
**Propósito**: Ejecutar tareas complejas correctamente
**Características**:
- Checklist detallado
- Puntos de validación
- Procedimientos de rollback

**Ejemplo de nombre**:
- "Configurar router empresarial para cliente nuevo"
- "Implementar solución de respaldo para cliente crítico"

**Patrón de conexiones**:
```
[[Preparación pre-ejecución]] → [[Ejecución principal]] → [[Validación post-ejecución]]
                                         ↓
                               [[Rollback si falla]] → [[Escalamiento técnico]]
```

---

## Principios de Conexión Práctica

### Conexiones que Agregan Valor

#### 1. Secuenciales
**Propósito**: "Después de esto, haz esto"
**Ejemplo**: `[[Diagnóstico inicial]] → [[Implementar solución]] → [[Validar con cliente]]`

#### 2. Condicionales  
**Propósito**: "Si pasa X, usa esta otra célula"
**Ejemplo**: `[[Evaluación de problema]] → [[Si es hardware: Reemplazo]] / [[Si es config: Ajuste]]`

#### 3. Complementarias
**Propósito**: "Mientras haces esto, también considera esto"
**Ejemplo**: `[[Instalación técnica]] ↔ [[Comunicación con cliente durante proceso]]`

#### 4. Escalatorias
**Propósito**: "Si esto no funciona, escala a esta célula"
**Ejemplo**: `[[Solución nivel 1]] → [[Escalamiento nivel 2]] → [[Escalamiento gerencial]]`

### Evitar Conexiones Inútiles
- **No conectar solo por temas similares**: "Clientes" no conecta automáticamente con todo lo de clientes
- **No crear conexiones "por si acaso"**: Solo conexiones que realmente usarás
- **No sobreconectar**: Máximo 5 conexiones por célula para mantener claridad

---

## Criterios para que una Célula sea Realmente Útil

### 1. Resuelve algo específico
**Bueno**: "Cliente amenaza con cancelar por precio alto"
**Malo**: "Gestión de clientes"
**Por qué**: Lo específico es accionable, lo general es teórico

### 2. Captura el "secreto"
**Qué incluir**: El insight, técnica o enfoque que hace la diferencia entre un novato y un experto
**Ejemplo**: "El truco está en validar primero que el cliente siente que recibe valor antes de hablar de precio"

### 3. Es accionable
**Bueno**: "1. Revisar logs de conexión de los últimos 7 días"
**Malo**: "Analizar el comportamiento de la red"
**Por qué**: Pasos concretos vs conceptos abstractos

### 4. Tiene trigger claro
**Debe responder**: ¿Cuándo uso exactamente esta célula?
**Ejemplo**: "Cuando cliente reporta lentitud pero speed test muestra velocidad contratada"

### 5. Genera resultado medible
**Debe incluir**: Indicadores claros de éxito o fracaso
**Ejemplo**: "Funcionó si: cliente confirma que percibe mejora + no hay reclamos en 48 horas"

---

## Estructura de Archivos Recomendada

```
conocimiento-empresa/
├── CÉLULAS-ACTIVAS/
│   ├── troubleshooting/
│   │   ├── CÉLULA-Internet-lento-speedtest-normal.md
│   │   ├── CÉLULA-Cortes-intermitentes-conexión.md
│   │   └── CÉLULA-Cliente-no-puede-conectar-wifi.md
│   ├── comunicación/
│   │   ├── CÉLULA-Explicar-aumento-precios.md
│   │   ├── CÉLULA-Convertir-queja-en-oportunidad.md
│   │   └── CÉLULA-Propuesta-cliente-empresarial.md
│   ├── decisiones/
│   │   ├── CÉLULA-Evaluar-zona-expansión.md
│   │   ├── CÉLULA-Decidir-descuento-especial.md
│   │   └── CÉLULA-Priorizar-mantenimiento-red.md
│   └── ejecución/
│       ├── CÉLULA-Configurar-router-empresarial.md
│       ├── CÉLULA-Implementar-respaldo-crítico.md
│       └── CÉLULA-Migrar-cliente-nuevo-plan.md
├── MAPA-GENERAL.md
└── ÍNDICE-POR-SITUACIÓN.md
```

---

## Ejemplo Práctico: Célula Completa

### CÉLULA: Cliente reporta internet lento pero speed test muestra velocidad normal

#### Cuándo usar esto
- Speed test desde múltiples dispositivos muestra velocidad contratada o superior
- Cliente insiste en que "se siente lento" o "no es como antes"
- No hay reportes de cortes o intermitencias

#### El "truco" que marca la diferencia
El problema usualmente no es velocidad sino latencia, saturación de WiFi, o expectativas. La clave es diagnosticar qué está causando la PERCEPCIÓN de lentitud, no la velocidad real.

#### Proceso (paso a paso)
1. **Validar la percepción específica** - Pregunta exactamente qué se siente lento (páginas web, videos, juegos, videollamadas)
2. **Revisar uso de red en tiempo real** - Verificar si hay dispositivos consumiendo ancho de banda desproporcionadamente
3. **Probar latencia y pérdida de paquetes** - Ping sostenido a 8.8.8.8 por 2 minutos
4. **Evaluar configuración de WiFi** - Revisar canal, interferencias, cantidad de dispositivos conectados
5. **Implementar solución específica** - Basado en hallazgos: cambio de canal, configuración de QoS, o educación del cliente

#### Cómo saber que funcionó
- Cliente confirma mejora en actividades específicas que reportó como lentas
- No hay nuevos reclamos de velocidad en los siguientes 7 días
- Métricas técnicas (latencia, pérdida de paquetes) dentro de parámetros normales

#### Si algo sale mal
- **Problema persiste después de ajustes**: [[CÉLULA-Escalamiento-técnico-nivel-2]]
- **Cliente sigue insatisfecho con explicación**: [[CÉLULA-Manejo-expectativas-técnicas]]
- **Se descubre problema real de infraestructura**: [[CÉLULA-Diagnóstico-red-upstream]]

#### Se conecta con
- [[CÉLULA-Speed-test-inicial-diagnóstico]]
- [[CÉLULA-Configuración-optimal-WiFi-residencial]]
- [[CÉLULA-Educación-cliente-uso-eficiente]]
- [[CÉLULA-Seguimiento-post-solución]]

---
*Última actualización: 2024-01-15 | Usos exitosos: 23 | Efectividad: 87%*

---

## Métricas de Éxito de las Células

### Por Célula Individual
- **Usos totales**: Cuántas veces se ha aplicado
- **Tasa de éxito**: % de casos donde logró el resultado esperado
- **Tiempo promedio**: Cuánto tarda ejecutarla vs método anterior
- **Refinamientos**: Cuántas mejoras se han incorporado

### Por Conjunto de Células
- **Cobertura**: % de situaciones recurrentes que tienen célula
- **Adopción**: % del equipo que las usa regularmente
- **Eficiencia**: Reducción promedio de tiempo en tareas cubiertas
- **Calidad**: Consistencia de resultados entre diferentes usuarios

---

## Implementación Progresiva Recomendada

### Semana 1: Identificación
- Listar 10 situaciones más recurrentes y problemáticas
- Seleccionar las 3 que más tiempo consumen o más frustración generan
- Validar que cumplen los criterios de utilidad

### Semana 2: Desarrollo
- Crear las 3 células usando el template básico
- Documentar el proceso actual más exitoso para cada situación
- Establecer conexiones obvias entre las 3 células

### Semana 3: Prueba
- Usar las células en situaciones reales
- Documentar qué funciona y qué no
- Refinar basado en experiencia práctica

### Semana 4: Expansión
- Agregar 2-3 células más basadas en aprendizajes
- Entrenar al resto del equipo en uso de células existentes
- Establecer proceso de mejora continua

---

## Señales de que el Sistema Funciona

### Positivas
- La gente busca células antes de preguntar a expertos
- Se crean células nuevas orgánicamente por el equipo
- Las conexiones entre células se usan regularmente para navegar problemas
- Reducción medible en tiempo de resolución de problemas recurrentes
- Nuevos empleados se vuelven productivos más rápido

### Negativas (para corregir)
- Células muy complejas que nadie usa
- Conexiones que nadie sigue
- Información que se vuelve obsoleta rápidamente
- Resistencia del equipo a documentar o usar células
- Células que duplican conocimiento en lugar de capturar lo único

---

*Framework desarrollado para maximizar adopción y utilidad práctica en empresas reales*