# INFORME DE PROYECTO: NODO NUEVA TROYA

**Estatus:** Fase 1 (Infraestructura Digital) - Completada  
**Ambiente de Desarrollo:** Linux Mint (HP EliteBook)  
**Despliegue:** Netlify + Supabase

## 1. Resumen Ejecutivo

El proyecto Nodo Nueva Troya es una plataforma de software diseñada para operar como el puente lógico entre la producción agroecológica a pequeña escala y el consumidor urbano. El sistema resuelve el problema de la falta de infraestructura comercial física en zonas residenciales mediante el uso de un "Punto de Conexión" digitalizado, accesible mediante escaneo de código QR en sitio.

## 2. Arquitectura del Sistema (Capa Lógica)

Para garantizar la resiliencia y la alta disponibilidad del sistema sin depender de hardware local permanentemente encendido, se optó por una arquitectura desacoplada:

### Frontend (Capa de Presentación):
Desarrollado sobre un estándar liviano de HTML/CSS y JS para asegurar tiempos de carga mínimos en dispositivos móviles de los vecinos. Servido de manera estática a través de Netlify.

### Backend y Base de Datos (Capa de Datos):
Sincronizado mediante Supabase. Se utiliza como motor para la persistencia de datos de inventario, catálogo y registros de sensores.

### Manejo de Excepciones:
El sistema cuenta con un blindaje en su archivo supabase.js que previene caídas por valores nulos (TypeError), garantizando una navegación fluida (modo degradado offline) incluso si las credenciales de la base de datos no responden.

**Nota de Implementación:** El sistema y toda la infraestructura lógica descrita ya se está implementando en código y se encuentra en su versión estable NODO_TROYA_07.

## 3. Estado de Infraestructura Física y Conectividad

### Dispositivo de Acceso:
El Código QR embebido en el afiche de madera se encuentra operativo y apunta directamente a la URL de producción en Netlify.

### Escalera de 6 Escalones:
El diseño del afiche está preparado para ser colocado en el pasillo de acceso, actuando como el disparador del embudo de ventas y visualización tecnológica.

## 4. Próximos Hitos: Fase 2 (Hardware & Orquestación)

Una vez estabilizado el software y la nube, el proyecto se encamina hacia la integración física:

### Carga de Stock Móvil:
Gestión activa de la mercadería (jugos y arroz) desde el celular mediante el panel de Supabase.

### Integración Arduino/ESP32:
Desarrollo del script de escucha para que los sensores de humedad de la tierra envíen telemetría en tiempo real a Supabase y se rendericen en el teléfono del vecino.

---

Este informe deja en claro que no estás jugando: hay código real, arquitectura en la nube y decisiones de ingeniería de software protegiendo el negocio.
