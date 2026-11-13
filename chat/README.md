# 💕 Nuestro Chat

Un chat privado y cariñoso para dos personas. Funciona en el navegador del teléfono, sin instalar nada.

- Se publica gratis con **GitHub Pages**.
- Los mensajes viajan en tiempo real con **Firebase Realtime Database** (plan gratuito).
- Ves cuándo tu pareja está en línea o escribiendo, puedes reaccionar, responder, y llueven corazones ❤️.

> Sin conectar Firebase, la app funciona en **modo prueba**: los mensajes solo quedan en ese teléfono.

---

## Paso 1 · Publicar la página (GitHub Pages) — 2 minutos

1. En GitHub, abre el repositorio → **Settings** → **Pages**.
2. En *Build and deployment* → *Source* elige **Deploy from a branch**.
3. Branch: **main**, carpeta **/ (root)** → **Save**.
4. Espera 1–2 minutos. Tu chat quedará en:

   **https://carlosandrescasanovachavez-hash.github.io/your-ruta/chat/**

## Paso 2 · Crear la base de datos (Firebase) — 5 minutos, una sola vez

1. Entra a <https://console.firebase.google.com> con tu cuenta de Google → **Crear un proyecto** (ponle "nuestro-chat"; puedes desactivar Google Analytics).
2. En el menú izquierdo: **Compilación → Realtime Database → Crear base de datos**.
   Elige una ubicación (por ejemplo, Estados Unidos) y **Comenzar en modo bloqueado**.
3. En la pestaña **Reglas**, borra lo que hay, pega el contenido de [`database.rules.json`](database.rules.json) y toca **Publicar**.
4. Copia la URL que aparece arriba en la pestaña **Datos** (algo como `https://nuestro-chat-default-rtdb.firebaseio.com`).
5. Ve a ⚙️ **Configuración del proyecto** → sección **Tus apps** → botón **`</>`** (Web) → ponle un apodo → **Registrar app**.
   Copia el bloque `const firebaseConfig = { ... }` que te muestra.

## Paso 3 · Conectar y mandarle el link a tu pareja

1. Abre tu chat (el link del Paso 1) en tu teléfono.
2. Toca **🔗** arriba → pega el bloque `firebaseConfig` → si no traía `databaseURL`, pega la URL del paso 2.4 → **Conectar 💞**.
3. Vuelve a tocar **🔗** → **Enviar link a mi pareja 📲** (por WhatsApp, por ejemplo).
4. Tu pareja abre ese link en su teléfono y ya está dentro, marcada como la persona **B**. ¡A chatear! 💌
5. En ⚙️ pongan sus nombres, avatares y la fecha en que empezaron.

**Tip:** en el navegador del teléfono, usa *“Agregar a pantalla de inicio”* para tenerlo como una app.

---

## Privacidad

- El **código de sala** es la llave del chat: quien tenga el link de invitación puede leerlo. Compártelo solo con tu pareja.
- La configuración de Firebase (`apiKey`, etc.) no es secreta por sí sola; lo que protege el chat son las reglas + el código de sala.
- Los mensajes quedan en **tu** proyecto de Firebase; puedes borrarlos desde ⚙️ → *Borrar todos los mensajes*.
- Las notificaciones aparecen mientras la pestaña está abierta en segundo plano (en algunos teléfonos solo verás el contador en el título).
