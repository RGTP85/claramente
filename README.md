# 💜 ClaraMente

**Organizá tu consultorio psicológico desde el celular.**

ClaraMente es una web app progresiva (PWA) diseñada para profesionales de la psicología. Se instala como una app en el celular, funciona offline y no requiere ningún servidor.

---

## ✨ Funcionalidades

- **👤 Pacientes** — Ficha completa con lugar de atención (Particular / Centro / Centro Vecinal), precio por sesión, comisión y frecuencia
- **📅 Agenda** — Citas organizadas por día con confirmación
- **📝 Notas clínicas** — Registro por sesión con estado emocional y etiquetas
- **📋 Turnero** — Resumen semanal (Lun→Dom) de turnos del Centro, con comisión total y envío directo por WhatsApp
- **💰 Finanzas** — Cobros con estados (completo, seña 50%, no pagó), ganancia mensual solo con tu honorario
- **⚠️ Deudores** — Pacientes que deben, agrupados con totales
- **🔔 Notificaciones** — 8am resumen diario, 5 min antes de cada cita, viernes 20hs recordatorio del turnero

---

### Instalar en el celular (Android):
1. Abrí el link en **Chrome**
2. Tocá el menú **⋮** (tres puntitos arriba a la derecha)
3. Tocá **"Agregar a pantalla de inicio"**
4. ¡Se instala como app con ícono propio!

### Instalar en iPhone:
1. Abrí el link en **Safari**
2. Tocá el botón de **compartir** (cuadrado con flecha)
3. Tocá **"Agregar a inicio"**

---

## 🔒 Privacidad

Todos los datos se guardan **localmente en el celular** del usuario (localStorage). No se envía nada a ningún servidor. Cada persona tiene sus propios datos privados.

---

## 📂 Estructura del proyecto

```
claramente-project/
├── README.md           ← Este archivo
├── .gitignore
└── public/
    ├── index.html      ← La app completa
    ├── manifest.json   ← Configuración PWA
    ├── sw.js           ← Service Worker (offline)
    ├── icon-192.png    ← Ícono app
    └── icon-512.png    ← Ícono app (alta res)
```

---

Hecho con 💜
