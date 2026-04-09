# Informe de Estado y Avances: Proyecto Ojo de Paz

Este informe resume la estructuración técnica, la estrategia de vinculación internacional y los pasos de postulación desarrollados recientemente para el protocolo de identidad marítima.

## 1. Definición del Producto y Propuesta de Valor

El proyecto se ha consolidado bajo el nombre técnico de **Protocolo de Identidad Marítima Soberana (PIMS)**.

**Concepto:** Es una solución de ingeniería basada en una arquitectura de Confianza Cero (Zero Trust) de bajo costo.

**Propósito:** Permitir que los sectores de pesca artesanal vulnerables se identifiquen de manera segura ante sistemas de vigilancia (como drones y radares) sin revelar públicamente su ubicación geográfica ni comprometer su seguridad ante terceros.

**Diferencial:** A diferencia del sistema AIS convencional, que emite señales abiertas y resulta costoso, este protocolo protege la privacidad de la ruta del pescador y garantiza la integridad de los datos mediante firmas digitales y atestación de hardware.

**Modelo Económico:** Se plantea un esquema B2G/B2B (SaaS o licenciamiento para gobiernos y ONGs) que financie la infraestructura. El acceso y uso del sistema para el pescador artesanal será totalmente gratuito.

## 2. Proyecto "Anfitrión" (Estrategia de Outreach)

Para no avanzar únicamente desde el entorno de desarrollo y lograr un contacto real con la problemática operativa, se estructuró el proyecto Anfitrión. Este actúa como el brazo de comunicación y validación en territorio colombiano.

**Hoja de Ruta y Canales:** Se pautó la búsqueda y contacto de perfiles mediante LinkedIn, correos institucionales y monitoreo en redes como X (Twitter).

**Protocolo de Timing:** Se estableció el lunes a primera hora de Colombia (GMT-5) como el momento idóneo para los envíos, buscando máxima visibilidad en las agendas semanales de las autoridades.

## 3. Mapeo de Contactos y Mensajería Calibrada

Se consolidó una lista de actores clave en Colombia y se redactaron propuestas de comunicación específicas en el archivo PERSONAL_MESSAGES.md:

### AUNAP (Autoridad Nacional de Acuicultura y Pesca):

- **Dra. Yarledy Lozano Tovar** (Directora de Inspección y Vigilancia): Enfoque técnico centrado en resolver las alertas y falsos positivos en las zonas de control.
- **Dra. Karen Elena Mejía Piñerez** (Directora General): Enfoque institucional solicitando orientación sobre cómo encajaría el protocolo en la hoja de ruta de la entidad.

### DIMAR (Dirección General Marítima):

- **Cap. José Andrés Díaz Ruiz** (Subdirector de Marina Mercante): Propuesta enfocada en la integración de sistemas mediante API REST y control de tráfico marítimo en zonas donde el AIS no es viable.

### Organizaciones y Gremios de Base:

- **Adriana Cadena Cancino** (Representante de la Mesa Nacional de Pesca / CONFEPESCA): Mensaje con un tono mucho más humano y humilde, buscando validar directamente con las comunidades si la protección de la identidad es una necesidad real en el agua antes de imponer código o infraestructura.

## 4. Postulación ante Uruguay XXI

Se diseñó un procedimiento de 7 pasos y un borrador de postulación (URUGUAY_XXI_DRAFT.md) para el programa "Uruguay al Mundo":

- Se enfatiza el proyecto no como una iniciativa asistencial, sino como una exportación de servicios de software y ciberseguridad con alto valor añadido.
- Se utiliza el despliegue de un plan piloto de 10 dispositivos en el área de Buenaventura como un hito claro y medible para justificar el uso de apoyos económicos.
- Se apoya la postulación en la experiencia previa de más de 20 años en seguridad de infraestructuras críticas (puertos y refinerías) para dar garantías de robustez técnica (seniorship).

## 5. Material de Respaldo Técnico

Toda la estrategia descrita se encuentra vinculada directamente a los repositorios alojados en tu cuenta de GitHub (HectorCorbellini):

- El núcleo del desarrollo en `ojo-de-paz-core`.
- El repositorio de normas de calidad industrial `hector-repo-standard`.

De cara a los próximos pasos, las estructuras de comunicación, los ensayos de posibles objeciones y las carpetas del proyecto Anfitrión han quedado completamente listos para dar inicio a la fase de vinculación externa.
