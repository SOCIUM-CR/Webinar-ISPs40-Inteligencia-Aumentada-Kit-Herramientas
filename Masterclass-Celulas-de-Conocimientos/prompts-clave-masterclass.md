# Prompts Clave - Masterclass Células de Conocimiento ISP

Este documento contiene los **2 prompts más importantes** demostrados en la masterclass, listos para que los copies y uses en tus propias implementaciones.

---

## 🧠 PROMPT #1: Construcción Automática de Células de Conocimiento

### **Cuándo usar este prompt:**
- Cuando tienes documentación de tu ISP organizada en una carpeta
- Quieres que Gemini Agent (u otra IA) construya células de conocimiento automáticamente
- Necesitas sistematizar expertise técnico sin hacerlo manualmente

### **Herramienta recomendada:**
- **Gemini CLI** (gratuito, requiere instalación)
- Alternativa: Claude Projects, ChatGPT con archivos adjuntos

### **Prerequisitos antes de usar:**
1. Tener carpeta `00-Conocimientos/` con tus documentos:
   - Perfiles de identidad, crisis, mercado, comunicación
   - Documentación técnica de tu infraestructura
   - Procedimientos existentes
   - Inventarios de equipos

2. Tener archivo `celulas_conocimiento_pragmaticas.md` (framework)
   - Descárgalo del kit de herramientas
   - Define estructura de células
   - Establece metadatos y formato

### **📋 PROMPT COMPLETO:**

```
Mira, quiero que revises todos los documentos que están dentro de la carpeta @00-Conocimientos/

Y a partir de los conocimientos que tenemos dentro de esa carpeta, tienes que leer cada uno de ellos en detalle, sin saltearte ninguno.

El objetivo es que construyamos células de conocimiento que puedan ser utilizables, tanto para el equipo de trabajo interno de mi empresa o emprendimiento, como también para las herramientas de inteligencia artificial, como con la que estamos trabajando en este momento.

Entonces, seguramente vas a tener que trabajarlo siguiendo las directrices que tenemos en el documento @celulas_conocimiento_pragmaticas.md

Entonces vas a seguir todas esas indicaciones, y vas a generar todas las células de conocimiento de manera autónoma.

Es muy importante que este trabajo lo hagas escribiendo un plan de trabajo. En el plan de trabajo, vas a construir una checklist que te va a servir de guía para poder darle continuidad al proceso paso a paso.

Y una vez que vayas marcando las tareas como realizadas, vas a seguir las tareas que están luego. Todo de manera que puedas ejecutar una tarea por vez hasta que completes todos los conocimientos que necesitamos desarrollar de manera autónoma y auto-eficiente.

Una vez acabes con tu trabajo, los conocimientos que usaste para desarrollarlos y los conocimientos del framework, los vas a guardar en una carpeta Legacy para dejar bien organizado todo el proyecto.
```

### **⚙️ Cómo Personalizar:**

**Cambiar referencias de carpetas:**
- `@00-Conocimientos/` → Ajusta al nombre de TU carpeta
- `@celulas_conocimiento_pragmaticas.md` → Usa el nombre exacto de tu framework

**Agregar restricciones específicas:**
Después del prompt base, puedes agregar:
```
IMPORTANTE: Prioriza las siguientes áreas en este orden:
1. Troubleshooting técnico (OLT, fibra, conectividad)
2. Comunicación con clientes (cobranza, soporte)
3. Procesos de instalación y mantenimiento
```

**Ajustar nivel de autonomía:**
Para más control manual:
```
Después de crear cada célula, páusate y muéstramela para validación antes de continuar con la siguiente.
```

### **🎯 Resultado Esperado:**

Al ejecutar este prompt, Gemini Agent debería:
1. ✅ Leer todos los documentos en la carpeta especificada
2. ✅ Crear un plan de trabajo con checklist
3. ✅ Generar células de conocimiento siguiendo el framework
4. ✅ Organizar archivos en estructura adecuada
5. ✅ Mover documentos originales a carpeta Legacy
6. ✅ Crear índice navegable de células

### **⚠️ Troubleshooting Común:**

**Problema:** "API error" o interrupciones frecuentes  
**Solución:** Si se corta, simplemente escribe `continuar` y retomará

**Problema:** Células muy genéricas o incompletas  
**Solución:** Tus documentos base necesitan más detalle específico de TU operación

**Problema:** No encuentra archivos  
**Solución:** Verifica que estés en la carpeta correcta con `pwd` en terminal

**Problema:** No sigue el framework correctamente  
**Solución:** Asegúrate que el archivo framework esté bien referenciado con `@`

### **💡 Pro Tips:**

1. **Primera vez:** Hazlo con 2-3 documentos pequeños para probar
2. **Documentos grandes:** Divide en sesiones, procesa por categorías
3. **Validación:** Revisa primeras 2-3 células antes de dejar que complete todas
4. **Iteración:** Es normal que necesites 2-3 iteraciones para afinar

---

## 💬 PROMPT #2: Generación de Comunicación Masiva Personalizada (WhatsApp)

### **Cuándo usar este prompt:**
- Necesitas enviar mensajes personalizados a muchos clientes
- Tienes base de datos CSV con info de clientes
- Quieres generar enlaces directos de WhatsApp con mensaje pre-cargado
- Casos: cobranza, avisos de mantenimiento, promociones

### **Herramienta recomendada:**
- **Claude** (mejor manejo de CSVs y formato)
- Alternativa: ChatGPT Plus, Gemini Advanced

### **Prerequisitos antes de usar:**

1. **Archivo CSV de clientes** con columnas mínimas:
   - Nombre completo
   - Número de teléfono (con código de país)
   - Servicio contratado
   - Monto adeudado (si es cobranza)
   - Cualquier otra info para personalizar

2. **Perfiles de conocimiento cargados:**
   - Perfil de Identidad Corporativa
   - Perfil de Comunicación
   - Así Claude conoce tu tono de voz y valores

3. **Estructura de carpeta organizada:**
```
📁 proyecto-comunicacion/
├── 📄 clientes-pendientes.csv
├── 📄 perfil-identidad.md
└── 📄 perfil-comunicacion.md
```

### **📋 PROMPT COMPLETO:**

```
Te estoy compartiendo aquí un listado de gentes que están con pendiente de pago de nuestros servicios.

Y quiero que me ayudes a construir un artefacto en formato CSV, aunque sea un artefacto de texto, pero que respete ese formato de separado por comas.

Donde me traspone, digamos, cada uno de las personas con un mensaje personalizado, donde tenga un recordatorio muy amable del servicio que tiene que abonar con el costo, y pues un saludo cercano y amistoso.

Ese resultado va a incluir al final un enlace que ocupe https://wa.me como base y la URL completa con el número de teléfono y su código de país, para que yo pueda aplicar directamente un link a cada mensaje y pueda ir ejecutando cada mensaje abriéndose en WhatsApp directamente.
```

### **⚙️ Cómo Personalizar por Caso de Uso:**

#### **Para Cobranza (como en el ejemplo):**
```
IMPORTANTE sobre el tono:
- Ser amable pero firme
- Mencionar servicio específico y monto exacto
- Incluir fecha de vencimiento
- Ofrecer opciones de pago
- Usar lenguaje de nuestra marca (consulta @perfil-comunicacion.md)
```

#### **Para Avisos de Mantenimiento:**
```
CONTEXTO: Vamos a realizar mantenimiento programado

El mensaje debe:
- Informar fecha y hora exacta del mantenimiento
- Explicar brevemente el beneficio (mejora de servicio)
- Indicar duración estimada de la interrupción
- Agradecer la comprensión
- Mantener tono profesional y tranquilizador
```

#### **Para Promociones:**
```
CONTEXTO: Lanzamiento de nuevo plan de fibra óptica

El mensaje debe:
- Presentar la oferta de forma atractiva
- Mencionar beneficios clave vs. plan actual
- Incluir precio promocional y vigencia
- Call-to-action claro
- Tono entusiasta pero no agresivo
```

#### **Para Seguimiento Post-Venta:**
```
CONTEXTO: Clientes con instalación reciente (última semana)

El mensaje debe:
- Agradecer la confianza
- Preguntar si todo funciona correctamente
- Ofrecer soporte si lo necesitan
- Mencionar recursos disponibles (WhatsApp soporte, tutorial)
- Tono cálido y cercano
```

### **🎯 Resultado Esperado:**

Claude generará un archivo CSV con estructura similar a:

```csv
Nombre,Teléfono,Servicio,Monto,Mensaje,EnlaceWhatsApp
Juan Pérez,+52 998 123 4567,Fibra 50MB,$450,"Hola Juan, espero que estés muy bien...",https://wa.me/5299812345678?text=Hola%20Juan...
María García,+52 998 765 4321,Fibra 100MB,$650,"Hola María, es Nemesio de CW Redes...",https://wa.me/5299876543214?text=Hola%20Mar%C3%ADa...
```

**Columnas clave generadas:**
- **Mensaje:** Texto personalizado completo
- **EnlaceWhatsApp:** URL directa que abre WhatsApp con mensaje precargado

### **📱 Cómo Usar el Resultado:**

1. **Descarga el CSV** generado por Claude
2. **Abre en Excel/LibreOffice** para visualización clara
3. **Click en cada enlace** de la columna "EnlaceWhatsApp"
4. **WhatsApp Web se abrirá** con el mensaje ya escrito
5. **Revisa y envía** (puedes hacer ajustes finales si necesitas)

**IMPORTANTE:** Envía máximo 5-10 mensajes por hora para evitar bloqueos de WhatsApp

### **⚠️ Troubleshooting Común:**

**Problema:** Enlaces no funcionan (no abren WhatsApp)  
**Solución:** Verifica que números tengan formato correcto: `+[código país][número sin espacios]`

**Problema:** Mensajes suenan robóticos o genéricos  
**Solución:** Carga primero tus perfiles de identidad y comunicación antes del prompt

**Problema:** Caracteres especiales mal codificados en URL  
**Solución:** Claude debería codificar automáticamente. Si falla, pide explícitamente: "Asegúrate de URL-encodear correctamente los mensajes"

**Problema:** CSV se ve mal en Excel  
**Solución:** Al abrir en Excel, usa "Datos > Desde texto/CSV" y selecciona UTF-8 como encoding

**Problema:** Claude mezcla idiomas (español/inglés)  
**Solución:** Agrega al prompt: "TODOS los mensajes deben ser en español mexicano"

### **💡 Pro Tips:**

1. **Segmentación inteligente:**
   ```
   Clasifica los clientes en 3 grupos:
   - Morosos recientes (1-15 días): tono amable
   - Morosos moderados (16-30 días): tono firme
   - Morosos críticos (30+ días): tono urgente
   
   Genera mensajes diferentes por segmento
   ```

2. **Personalización profunda:**
   ```
   Si el cliente tiene más de 1 año con nosotros, 
   menciona: "Después de [X] tiempo juntos..."
   
   Si es extranjero, ajusta el saludo y el tono
   ```

3. **A/B Testing:**
   ```
   Genera 2 versiones de mensaje:
   - Versión A: Enfocado en beneficio (mantener servicio)
   - Versión B: Enfocado en urgencia (corte inminente)
   ```

4. **Automatización siguiente nivel:**
   Después de validar que funciona, puedes:
   - Conectar con Zapier/Make para automatización real
   - Integrar con CRM para tracking de respuestas
   - Usar APIs oficiales de WhatsApp Business (requiere setup)

---

## 🔄 Combinación Poderosa: Usando Ambos Prompts Juntos

### **Caso de Uso Avanzado: Sistema Completo de Gestión**

1. **Primero:** Usa Prompt #1 para construir célula de "Gestión de Cobranza"
   - Incluye políticas de tu ISP
   - Tonos aprobados
   - Límites y excepciones

2. **Luego:** Usa Prompt #2 referenciando esa célula
   ```
   Antes de generar los mensajes, consulta la célula 
   @comunicacion-cobranza.md para seguir nuestros lineamientos
   ```

3. **Resultado:** Mensajes 100% alineados con tu operación sistemática

---

## 📚 Recursos Complementarios

### **Archivos que Necesitas del Kit:**
- `celulas_conocimiento_pragmaticas.md` (framework para Prompt #1)
- `perfil-identidad-corporativa.md` (contexto para Prompt #2)
- `perfil-comunicacion.md` (tono y voz para Prompt #2)
- `template-csv-clientes.csv` (ejemplo de estructura)

### **Tutoriales de Video:**
- Timestamp Prompt #1: 08:06 - 15:30 (Webinar 2)
- Timestamp Prompt #2: 45:50 - 54:28 (Webinar 2)

### **Herramientas Necesarias:**
- **Para Prompt #1:** Gemini CLI, terminal, Node.js
- **Para Prompt #2:** Claude AI (cuenta gratuita suficiente)

---

## ⚡ Quick Start: Primeros 15 Minutos

### **Validar Prompt #1:**
1. Crea carpeta de prueba con 2-3 documentos
2. Copia el prompt y ajusta rutas
3. Ejecuta en Gemini CLI
4. Valida que genere algo coherente
5. Si funciona, escala a documentación completa

### **Validar Prompt #2:**
1. Crea CSV de prueba con 3-5 clientes ficticios
2. Carga perfiles de identidad + comunicación en Claude
3. Pega CSV y ejecuta prompt
4. Valida enlaces de WhatsApp (prueba con tu número)
5. Si funciona, usa CSV real

---

## 🎓 Preguntas Frecuentes

**P: ¿Puedo usar estos prompts en ChatGPT?**  
R: Sí, funcionan en ChatGPT Plus/Team. Prompt #1 funciona mejor en Gemini CLI. Prompt #2 funciona mejor en Claude por manejo de CSVs.

**P: ¿Cuánto cuesta usar estos prompts?**  
R: Ambos funcionan con cuentas gratuitas. Para uso intensivo, considera planes pagos (Claude Pro $20/mes, Gemini Advanced $20/mes).

**P: ¿Los prompts funcionan en español e inglés?**  
R: Sí, pero ajusta explícitamente el idioma deseado en el prompt si mezcla lenguajes.

**P: ¿Qué pasa si mi CSV tiene 500 clientes?**  
R: Procesa en lotes de 50-100 por petición. Claude tiene límites de tokens. Divide y conquista.

**P: ¿Puedo modificar los prompts?**  
R: ¡Absolutamente! Estos son bases. Ajusta según tu caso específico. Experimenta.

---

## 🚀 Próximos Pasos

Después de dominar estos 2 prompts:

1. **Explora variaciones** para casos específicos de tu ISP
2. **Construye librería de prompts** personalizados
3. **Documenta qué funciona** mejor en tu operación
4. **Capacita a tu equipo** en uso efectivo
5. **Automatiza flujos** que uses semanalmente

---

## 📞 Soporte y Comunidad

Si tienes problemas implementando estos prompts:

- 💬 Pregunta en comunidad ExpansIA (miembros)
- 📧 Email: franco@socium.cr
- 🎥 Re-visita timestamps específicos del webinar
- 📚 Consulta documentación en GitHub

---

*Estos prompts son extractos de la Masterclass "Tu Experiencia ISP Amplificada" - SOCIUM.CR*

**Última actualización:** Octubre 2025  
**Versión:** 1.0