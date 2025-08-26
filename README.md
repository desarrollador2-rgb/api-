# Integración Evolution API con Labchats

Este proyecto documenta el proceso de instalación y configuración de **Evolution API** en un VPS de Hostinger usando **EasyPanel**, y su posterior integración con **Labchats** para la gestión de WhatsApp.

---

## 🚀 Pasos realizados

### 1. Conexión del servidor VPS a EasyPanel
- Se contrató un **VPS en Hostinger**.
- Se conectó el VPS con **EasyPanel** para la gestión de aplicaciones vía contenedores.

### 2. Creación del proyecto Evolution API
- Desde EasyPanel se creó un nuevo proyecto.
- Se seleccionó el stack de **Evolution API v2**.
- Se configuraron las variables de entorno necesarias en EasyPanel (base de datos, Redis, puerto, etc.).
- Se desplegó el proyecto correctamente.

### 3. Acceso mediante dominio
- Se configuró un **dominio personalizado** apuntando al servidor.
- Con el dominio se accedió a la interfaz de **Evolution API** desde el navegador.

### 4. Creación de instancia en Evolution API
- Dentro de Evolution API se creó una **nueva instancia**.
- Se agregó el **número de WhatsApp**.
- Se escaneó el **código QR** para vincular el dispositivo a la API.

### 5. Conexión con Labchats
- En el panel de **Labchats**, se ingresó a **API personalizada de WhatsApp**.
- Se seleccionó el **proveedor Evolution V2**.
- Se agregaron los datos requeridos:
  - Número de WhatsApp.
  - Nombre de instancia (copiado desde Evolution API).
  - API Key y URL del dominio configurado.
- Se validó la conexión y el bot quedó **Activo**.

---

## ✅ Resultado
- El número de WhatsApp quedó **conectado y activo en Labchats** mediante Evolution API.
- Ahora es posible gestionar conversaciones y automatizaciones desde Labchats usando el número conectado.

---

## 📌 Notas importantes
- Si el bot aparece como `close`, se debe:
  - Verificar la conexión en Evolution API.
  - Re-escanear el QR si la sesión expira.
  - Reiniciar la instancia desde Labchats o Evolution.

- El **Webhook de Labchats** debe estar configurado en Evolution API para la recepción de eventos y mensajes.

---

## 🔧 Herramientas utilizadas
- **Hostinger VPS**
- **EasyPanel**
- **Evolution API v2**
- **Labchats**

