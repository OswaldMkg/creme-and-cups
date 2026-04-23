# Créme & Cups — Sitio Web

Sitio web oficial de **Créme & Cups**, postres en vaso hechos con amor en Querétaro.

## 🚀 Cómo publicar con GitHub + Vercel

### 1. Crear el repositorio en GitHub

1. Ve a [github.com](https://github.com) e inicia sesión (o crea una cuenta gratis)
2. Haz clic en el botón verde **"New"**
3. Ponle de nombre: `creme-and-cups`
4. Déjalo en **Público**
5. Haz clic en **"Create repository"**

### 2. Subir el código con Claude Code

Abre una terminal en la carpeta de este proyecto y ejecuta:

```bash
# Instalar Claude Code (si no lo tienes)
npm install -g @anthropic-ai/claude-code

# Iniciar el repositorio de Git
git init
git add .
git commit -m "Sitio web Créme & Cups"

# Conectar con GitHub (cambia TU_USUARIO por tu usuario de GitHub)
git remote add origin https://github.com/TU_USUARIO/creme-and-cups.git
git branch -M main
git push -u origin main
```

### 3. Publicar en Vercel

1. Ve a [vercel.com](https://vercel.com) e inicia sesión con tu cuenta de GitHub
2. Haz clic en **"Add New Project"**
3. Selecciona el repositorio **`creme-and-cups`**
4. Vercel detectará automáticamente la configuración
5. Haz clic en **"Deploy"**

¡En menos de 1 minuto tendrás tu sitio en línea con una URL tipo:
`https://creme-and-cups.vercel.app`

---

## 📁 Estructura del proyecto

```
creme-and-cups/
├── public/
│   ├── index.html      ← Página principal
│   ├── style.css       ← Estilos
│   ├── logo.png        ← Logo oficial
│   ├── producto1.jpg   ← Fresas con Chocolate Turín
│   └── producto2.jpg   ← Fresas con Crema y Oreo
├── vercel.json         ← Configuración de Vercel
└── README.md
```

## 📞 Contacto del negocio

- **Teléfono / WhatsApp:** 999 332 3043
- **Instagram:** [@cremeandcups](https://www.instagram.com/cremeandcups)
- **Zona de entregas:** Querétaro, México
