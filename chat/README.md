# 💕 Nuestro Chat

Un chat privado y cariñoso para dos personas. Funciona en el navegador del teléfono, sin instalar nada,
**sin cuentas y sin base de datos**.

## Cómo funciona

- Los mensajes viajan **al instante** de un teléfono al otro a través de un relevo público gratuito (MQTT).
- Van **cifrados** (AES-GCM) con una clave secreta que solo está en su link de invitación:
  el relevo no puede leerlos y no guarda nada.
- Cada teléfono guarda **su propio historial**.
- Para que un mensaje llegue, **los dos tienen que tener el chat abierto**.
  Si tu pareja no estaba, el mensaje queda con ✓ y se entrega solo (✓✓) cuando ambos vuelvan a coincidir.
- Muestra si tu pareja está en línea o escribiendo; hay reacciones, respuestas y lluvia de corazones ❤️.

## Publicarlo (GitHub Pages) — 2 minutos

1. En GitHub: repositorio → **Settings** → **Pages**.
2. *Source*: **Deploy from a branch** → Branch **main**, carpeta **/ (root)** → **Save**.
3. En 1–2 minutos el chat queda en:
   **https://carlosandrescasanovachavez-hash.github.io/your-ruta/chat/**

## Empezar a chatear

1. Abre el link en tu teléfono → toca **🔗** → **Crear nuestro chat 💞**.
2. Toca **Enviar link a mi pareja 📲** (por WhatsApp, por ejemplo).
3. Tu pareja abre ese link y ya están conectados. ¡Listo! 💌
4. En ⚙️ pongan sus nombres, avatares y la fecha en que empezaron (se sincroniza en los dos teléfonos).

**Tip:** en el navegador usa *“Agregar a pantalla de inicio”* para tenerlo como una app.

## Bueno saber

- El link de invitación **es la llave** del chat: compártelo solo con tu pareja.
- Si borras los datos del navegador o cambias de teléfono, abre el link otra vez: tu pareja te reenvía
  los últimos mensajes la próxima vez que coincidan con el chat abierto.
- Las notificaciones solo aparecen mientras la pestaña está abierta (no hay avisos con el teléfono bloqueado).
