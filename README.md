# 🎮 Pokédex Personal - React App

Una aplicación interactiva de Pokédex construida con React que permite explorar, comprar, comparar y gestionar entrenadores Pokémon.

## 🌟 Características Principales

### 🎨 Sistema de Temas
- 5 temas personalizables: Claro, Oscuro, Medianoche, Atardecer y Océano
- Cambio dinámico de colores en toda la aplicación
- Preferencias guardadas en localStorage

### 🛒 Carrito de Compras
- Añade Pokémon a tu carrito
- Visualiza y gestiona items del carrito
- Checkout simulado con generación de recibos
- Descarga automática del ticket en formato .txt
- Envío del recibo por correo electrónico

### ⚖️ Comparador de Entrenadores
- Compara hasta 4 entrenadores diferentes
- Panel visual de comparación
- Añade entrenadores directamente desde la comparación

### 📊 Vista Pokédex Avanzada
- Interfaz tipo Pokédex física (roja y verde)
- Pantalla grande con imagen del Pokémon
- Estadísticas y movimientos
- Controles de navegación (anterior/siguiente)
- Botones para editar, comprar o eliminar

### ✏️ Edición y Personalización
- Crea Pokémon personalizados
- Edita Pokémon existentes
- Clona Pokémon de la API para personalizarlos
- Gestión completa de tu colección personal

### 🔍 Búsqueda y Ordenamiento
- Busca Pokémon por nombre
- 4 opciones de ordenamiento: ID ascendente/descendente, Nombre A-Z/Z-A
- Acceso a 151 Pokémon de la API oficial

### 💾 Persistencia de Datos
- Todos los datos se guardan en localStorage
- Carrito, comparación, Pokémon personalizados y preferencias de tema persisten entre sesiones

---

## 🚀 Inicio Rápido

### Instalación

```bash
# Clona el repositorio
git clone https://github.com/luishmat/Pok-dex.git
cd pokedex

# Instala dependencias
npm install

# Inicia el servidor de desarrollo
npm start
```

La aplicación se abrirá en `http://localhost:3000`

### Build para Producción

```bash
npm run build
```

Crea una carpeta `build` optimizada para producción.

---

## 📦 Despliegue en GitHub Pages

Para publicar tu Pokédex en GitHub Pages, consulta [DEPLOYMENT.md](DEPLOYMENT.md)

Comando rápido:
```bash
npm run deploy
```

---

## 📁 Estructura del Proyecto

```
src/
├── App.js                 # Componente principal
├── App.css                # Estilos globales
├── ThemeContext.js        # Contexto de temas
├── CartContext.js         # Contexto del carrito
├── CompareContext.js      # Contexto de comparación
├── Settings.js            # Panel de configuración
├── Cart.js                # Componente del carrito
├── Checkout.js            # Modal de pago
├── Compare.js             # Panel de comparación
├── PokedexView.js         # Vista Pokédex detallada
├── PokedexView.css        # Estilos de la Pokédex
└── index.js               # Punto de entrada
```

---

## 🎯 Cómo Usar

### Ver tu Pokédex
1. Abre la app y selecciona un Pokémon haciendo clic en su tarjeta
2. Haz doble clic para abrir la vista Pokédex completa

### Agregar al Carrito
- Haz clic en "🛒 Agregar" en cualquier tarjeta
- O abre la vista Pokédex y haz clic en "🛒 Comprar"

### Comparar Entrenadores
1. Ve a la sección "Entrenadores"
2. Añade un nuevo entrenador con el formulario
3. Haz clic en "⚖️ Comparar" para añadirlo al panel de comparación

### Editar Pokémon Personalizados
1. Selecciona un Pokémon personalizado
2. Haz clic en "✎ Editar"
3. Modifica los datos y guarda

### Cambiar Tema
- Haz clic en el botón ⚙️ en la esquina superior derecha
- Selecciona tu tema favorito

---

## 🛠️ Tecnologías Utilizadas

- **React 19** - Librería de UI
- **React Context API** - Gestión de estado global
- **localStorage** - Persistencia de datos
- **CSS3** - Diseño y animaciones
- **PokeAPI** - Datos de Pokémon

---

## 📝 Scripts Disponibles

```bash
npm start        # Inicia desarrollo
npm build        # Crea build para producción
npm test         # Ejecuta tests
npm deploy       # Despliega en GitHub Pages
```

---

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Para cambios importantes:
1. Haz fork del proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

---

##  Licencia

Este proyecto está bajo licencia MIT.

---

##  Soporte

¿Encontraste un bug? Abre un [issue](https://github.com/luishmat/Pok-dex/issues)

---

**Hecho con  para los amantes de Pokémon**

