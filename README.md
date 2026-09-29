# Frontend - Sedan vs Mototaxi

## Ejecutar localmente

```bash
npm install
npm run dev
```

Crea un archivo `.env`:

```env
VITE_API_URL=http://127.0.0.1:8000
```

## Netlify

Build command:

```text
npm run build
```

Publish directory:

```text
dist
```

En Netlify agrega la variable:

```text
VITE_API_URL=https://TU-BACKEND.onrender.com
```

Después realiza un nuevo deploy.

## Cámara del celular

El botón "Tomar foto" usa:

```html
<input type="file" accept="image/*" capture="environment">
```

En navegadores móviles compatibles solicita la cámara trasera. El botón "Subir foto" permite elegir una imagen existente.
