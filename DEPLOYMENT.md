# 🚀 Guía de Despliegue - Pokédex React en GitHub Pages

## 📋 Requisitos Previos

- Node.js y npm instalados
- Git instalado
- Una cuenta en GitHub
- Un repositorio en GitHub llamado `pokedex`

---

## ✅ Paso 1 — Instalar gh-pages (ya incluido en devDependencies)

Si no está instalado, ejecuta:

```bash
npm install gh-pages --save-dev
```

---

## ✅ Paso 2 — Configuración de package.json

Tu `package.json` ya tiene configurado:

```json
"homepage": "https://luishmat.github.io/Pok-dex/",
"scripts": {
  "predeploy": "npm run build",
  "deploy": "gh-pages -d build"
}
```

---

## ✅ Paso 3 — Subir código a GitHub

1. Inicializa el repositorio git (si no lo has hecho):
```bash
git init
git add .
git commit -m "Initial commit: Pokédex React App"
```

2. Añade el repositorio remoto (reemplaza `luismat` con tu usuario):
```bash
git remote add origin https://github.com/luishmat/Pok-dex.git
```

3. Sube el código a GitHub:
```bash
git branch -M main
git push -u origin main
```

---

## ✅ Paso 4 — Ejecutar Despliegue

En tu terminal, ejecuta:

```bash
npm run deploy
```

Este comando:
1. Ejecutará `npm run build` (crea la carpeta `build`)
2. Desplegará automáticamente en la rama `gh-pages`
3. GitHub Pages servirá tu aplicación

---

## ✅ Paso 5 — Activar GitHub Pages en Settings

1. Ve a tu repositorio en GitHub
2. Haz clic en **Settings** (Configuración)
3. En el menú izquierdo, selecciona **Pages**
4. En **Branch**, selecciona:
   - Branch: `gh-pages`
   - Folder: `/ (root)`
5. Haz clic en **Save**

---

## 🎉 ¡Listo!

Tu Pokédex estará disponible en:
```
https://luishmat.github.io/Pok-dex/
```

---

## 🔄 Futuras Actualizaciones

Cada vez que hagas cambios y quieras actualizar la versión en GitHub Pages:

```bash
git add .
git commit -m "Descripción de cambios"
git push
npm run deploy
```

---

## ⚠️ Solución de Problemas

### Error: "fatal: remote origin already exists"
```bash
git remote remove origin
git remote add origin https://github.com/luishmat/Pok-dex.git
```

### La página muestra 404
- Espera 1-2 minutos después de ejecutar `npm run deploy`
- Verifica que el branch `gh-pages` existe en GitHub
- Asegúrate que la rama está configurada correctamente en Settings > Pages

### Cambios no aparecen
```bash
npm run deploy
```

---

## 📚 Características de la Pokédex

✅ Tema claro/oscuro con 5 temas disponibles  
✅ Carrito de compras con checkout simulado  
✅ Comparar entrenadores Pokémon  
✅ Crear y editar Pokémon personalizados  
✅ Vista Pokédex con stats y movimientos  
✅ Orden personalizable de tarjetas  
✅ Persistencia en localStorage  

---

¿Necesitas ayuda? Abre un issue en el repositorio.
