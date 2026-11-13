# 💬 ChatPol

Un chat privado para dos personas que funciona en el navegador del teléfono, sin instalar nada,
**sin cuentas y sin base de datos**.

**Abrir:** https://carlosandrescasanovachavez-hash.github.io/your-ruta/chatpol/
(el link antiguo `/chat/` redirige aquí, así que las invitaciones ya enviadas siguen funcionando).

## Cómo funciona

- Los mensajes viajan **al instante** de un teléfono a otro por un relevo público gratuito (MQTT),
  **cifrados** (AES-GCM) con una clave secreta que solo está en el link de invitación.
  El relevo no puede leerlos y no guarda nada.
- Cada teléfono guarda **su propio historial** (mensajes y fotos).
- Para que algo llegue, **los dos deben tener el chat abierto**. Lo enviado mientras el otro no estaba
  queda con ✓ y se entrega solo (✓✓) cuando ambos vuelven a coincidir.

## Qué se puede hacer

- Mensajes, emojis, reacciones, responder, borrar para los dos, frases rápidas.
- 📷 Fotos desde la galería o con la cámara (frontal o trasera).
- 📍 Ubicación actual o 🛰️ en tiempo real (15 min, 1 h u 8 h), con mapa.
- Ver si el otro está en línea o escribiendo; ajustes de nombres, avatares y color (azul, violeta, verde u oscuro).

## Empezar

1. Abre ChatPol → toca **🔗** → **Crear un chat nuevo**.
2. Toca **Enviar link de invitación 📲** y mándaselo a la otra persona.
3. Al abrir el link quedan conectados.

**Tip:** abre el link en Chrome o Safari (no dentro de WhatsApp/Instagram) y usa *“Agregar a pantalla de inicio”*.

## Bueno saber

- El link de invitación **es la llave** del chat: quien lo tenga puede entrar.
- La ubicación en tiempo real solo se actualiza mientras el chat está abierto en ambos teléfonos.
- Si borras los datos del navegador, se borra el historial de ese teléfono.
