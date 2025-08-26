# Integración de Z-API con Labchats

Este documento describe los pasos realizados para conectar **Z-API** con **Labchats** y enviar mensajes de WhatsApp desde la API.

---

## 🚀 Pasos realizados

### 1. Creación de la instancia en Z-API
- Se creó una **instancia** en [Z-API](https://z-api.io/).
- Se generó un **nombre de instancia**: `labchats`.
- Se obtuvo:
  - **API de instancia** (URL base con ID y token).
  - **ID de instancia**.
  - **Token de instancia**.
- Estado: ✅ Conectado (versión multidispositivo).
- Nota: Durante el período **trial**, los mensajes incluyen un aviso de prueba.

---

### 2. Configuración en Labchats
- Dentro de Labchats se añadieron los datos de la instancia:
  - Nombre de instancia: `labchats`.
  - API URL: proporcionada por Z-API.
  - ID de instancia y token copiados desde Z-API.
- La conexión se estableció correctamente:
  - Estado mostrado como **Conectado**.
  - Se puede enviar y recibir mensajes vía Labchats.

---

### 3. Prueba de envío de mensajes
- Se envió un mensaje de prueba desde Labchats vía Z-API.
- El mensaje llegó al WhatsApp del cliente con el aviso de **Trial**:

