# 🐔 ADONAI - Tienda y Venta de Pollo

Sitio web con catálogo, puntos, premios, pedidos por WhatsApp y panel de administración.

## 🚀 Subirlo a GitHub Pages

1. En [github.com](https://github.com) → **New repository** → nombre `adonai-pollo` → **Public** → *Create*.
2. **Add file → Upload files** → arrastra `index.html` (y `README.md`) → **Commit changes**.
3. **Settings → Pages** → en *Branch* elige `main` y `/ (root)` → **Save**.
4. En ~1 minuto GitHub te da el enlace: `https://TU-USUARIO.github.io/adonai-pollo/`

## 🔐 Administradores

- Botón **Entrar** → **🔐 Soy Administrador**.
- Usuario inicial: `admin` — Contraseña inicial: `Adonai2026`
- El sistema te obliga a **cambiar la contraseña** en el primer ingreso.
- En **🛡️ Administradores** puedes crear otros admins (mismos permisos). Solo el administrador principal puede eliminarlos o darles una contraseña nueva.

## 📦 Pedidos (pendiente → entregado)

1. El cliente envía el pedido: queda **PENDIENTE** y se abre WhatsApp. **No se dan puntos todavía.**
2. Cuando pasa a recogerlo, en **📦 Pedidos** el admin presiona **✅ Ya pasó / Entregado** → se suman los puntos.
3. Si el pedido llegó por WhatsApp desde otro celular, pega el mensaje completo en **📥 Registrar un pedido recibido por WhatsApp**.

## 📱 Tu número de WhatsApp

En `index.html` busca `whatsappNumber: '50255550000'` y cambia por tu número con código de país (502 + 8 dígitos).

## ⚠️ Importante

Todo se guarda en el navegador de cada dispositivo (localStorage). Los datos **no se comparten** entre celulares. Para que clientes y administradores vean la misma información se necesita una base de datos en línea (ej. Firebase).
