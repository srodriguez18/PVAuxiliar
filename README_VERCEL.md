# 🌮 Akasia Tortillería - Punto de Venta

Mini app de punto de venta para tortillería. Totalmente funcional, sin servidor backend necesario.

## 🚀 Desplegar en Vercel (2 minutos)

### Paso 1: Preparar archivos
1. Descarga estos 2 archivos:
   - `app_final.html` (app completa con productos incrustados)
   - `productos.json` (base de datos)

### Paso 2: Crear repo en GitHub
1. Ve a https://github.com/new
2. Crea un repo nuevo: `akasia-ventas`
3. Sube los archivos

### Paso 3: Desplegar en Vercel
1. Ve a https://vercel.com
2. Haz clic en "New Project"
3. Selecciona tu repo de GitHub
4. Haz clic en "Deploy"
5. ¡Listo! Vercel te dará un link como: `https://akasia-ventas.vercel.app`

### Paso 4: Usar la app
- PC: Abre el link en navegador
- Móvil: Abre el link en Chrome/Safari
- Comparte el link con quien quieras

## 📊 Características

✅ 2,570 productos incluidos  
✅ Búsqueda con autocompletado  
✅ Carrito interactivo  
✅ Registra ventas (guardadas en navegador)  
✅ Ver ventas en pantalla  
✅ Descargar CSV con todas las ventas  
✅ Funciona en PC, iPhone, Android  
✅ Sin servidor, sin instalación  

## 🔧 Configuración

Si usas `app_online.html`, cambia la URL de productos:

En `app_online.html`, busca:
```javascript
const PRODUCTOS_URL = 'https://...';
```

Y reemplaza con:
```javascript
const PRODUCTOS_URL = 'https://tu-dominio-vercel.vercel.app/productos.json';
```

## 💾 Datos

- Las ventas se guardan en el navegador (localStorage)
- Puedes descargar ventas como CSV
- Los datos NO se envían a servidores
- Todo es 100% privado

## 📝 Licencia

Libre para usar y modificar.
