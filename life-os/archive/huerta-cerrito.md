📊 **INFORME DE PROYECTO: HUERTA-CERRITO**
### Sistema Agéntico de Gestión y Economía Circular para Huertas Comunitarias

## 1. RESUMEN EJECUTIVO

HUERTA-CERRITO es una solución tecnológica diseñada específicamente para comunidades de agricultura urbana y consumo responsable (prosumidores). A diferencia de las aplicaciones tradicionales basadas en menús visuales complejos y transacciones monetarias, este sistema utiliza una interfaz de voz nativa impulsada por Inteligencia Artificial y un modelo de economía de confianza basado en puntos. Su objetivo es eliminar la brecha digital en el barrio, permitiendo que los vecinos gestionen intercambios, logística y asambleas simplemente hablando con su celular.

## 2. EL MODELO DE NEGOCIO Y OPERACIÓN (PROCEDIMIENTOS)

Para garantizar la adopción y la armonía en la huerta al sur del Cerrito de la Victoria, hemos establecido los siguientes procedimientos de mejor práctica:

### A. Gestión de Intercambios (La Moneda de Confianza)

**El Trueque Tasado:** Los productos, herramientas y servicios no se venden; se les asigna un valor referencial en "Puntos".

**Procedimiento de Transacción:** El vecino anuncia por voz lo que ofrece (ej. "Presto mi pala") y lo que necesita (ej. "Zapallitos"). La IA actúa como el contador del ecosistema: calcula la diferencia de puntos, descuenta o suma saldos y confirma la operación sin que los usuarios deban registrar nada manualmente.

### B. El Rol del Mandadero (Logística de Proximidad)

**Inclusión de Actores:** Para vecinos que no pueden trasladarse, el sistema integra a repartidores locales (como el ejemplo de José).

**Procedimiento de Envío:** La IA calcula la distancia óptima y propone una comisión pequeña en puntos para el mandadero, resolviendo la logística de la "última cuadra".

### C. Transparencia Radical y Rendición de Cuentas

**Libro Abierto:** Para evitar suspicacias en el manejo de fondos colectivos, la aplicación muestra una tabla permanente y en tiempo real de ingresos y egresos.

**Procedimiento de Registro:** Cada vez que se realiza un gasto comunitario (ej. compra de mangueras), el responsable lo dicta a la app y esta actualiza la visualización para todos los vecinos de forma inmediata.

## 3. ARQUITECTURA TÉCNICA DE COSTO CERO (MVP)

Para validar la idea con los vecinos sin realizar inversiones económicas previas, el proyecto se apoyará en la siguiente infraestructura gratuita:

| Componente | Tecnología Propuesta | Razón de la Elección |
|------------|---------------------|----------------------|
| Frontend (App) | PWA (Progressive Web App) | Se instala en el celular como app nativa, accede al micrófono y no cuesta publicarla en tiendas. |
| Cerebro (Lógica) | Gemini API (Nivel Gratuito) | Procesa el lenguaje natural, entiende el contexto local y toma decisiones lógicas sin costo para baja escala. |
| Base de Datos | Google Sheets (Oculto) | Funciona como el "backend" donde se guardan los puntos y el stock. Es gratis y fácil de auditar. |
| Alojamiento | Netlify o Vercel | Plataformas seguras de despliegue web con excelentes planes gratuitos para proyectos sociales. |

## 4. PROCEDIMIENTO DE ADAPTABILIDAD (EL "CÓDIGO VIVO")

Uno de los mayores hallazgos de este diseño es cómo responde el software a las decisiones de la asamblea de vecinos:

### Cambios en Reglas y Valores (Inmediatos):
Si la comunidad decide cambiar el valor de un producto o suspender los repartos un día festivo, no se requiere programador. Basta con actualizar las instrucciones de texto de la IA (el System Prompt) dictándole las nuevas normas.

### Cambios de Información (Inmediatos):
Si se quieren agregar recetas o consejos de cultivo, basta con crear una nueva pestaña en el Google Sheet. La IA la leerá de forma orgánica.

### Cambios en Interfaz (Sesión de Vibe Coding):
Si se requiere un botón físico nuevo o un mapa, se utiliza programación asistida por IA para generar el código de la PWA en cuestión de minutos, garantizando que la app evolucione al ritmo del barrio.

## 5. PRÓXIMOS PASOS RECOMENDADOS

Para cuando decidas retomar el proyecto o abrir un nuevo espacio de trabajo, el orden de prioridades sugerido es:

1. **Redactar el "System Prompt":** El documento de texto que le da personalidad y límites lógicos a la IA.
2. **Maquetar el Google Sheet:** Definir las columnas exactas de Vecinos, Puntos, Stock y Finanzas.
3. **Crear el prototipo de interfaz:** Un sitio web simple de un solo botón para probar la captura de audio.
