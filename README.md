# Test Firebase

Una aplicación web de prueba desarrollada con React, TypeScript y Vite, configurada para despliegue en Firebase Hosting.

## 🚀 Tecnologías

- **React 19** - Biblioteca de interfaz de usuario
- **TypeScript** - Superset tipado de JavaScript
- **Vite** - Herramienta de construcción y desarrollo
- **Firebase Hosting** - Plataforma de alojamiento web
- **ESLint** - Linter para código JavaScript/TypeScript

## 📦 Instalación

1. Clona el repositorio:
```bash
git clone https://github.com/usuario/test-firebase.git
cd test-firebase
```

2. Instala las dependencias:
```bash
npm install
```

## 🛠️ Desarrollo

Para iniciar el servidor de desarrollo:

```bash
npm run dev
```

La aplicación estará disponible en `http://localhost:5173`

## 🏗️ Construcción

Para construir la aplicación para producción:

```bash
npm run build
```

Los archivos optimizados se generarán en la carpeta `dist/`.

## 🔍 Linting

Para ejecutar el linter y verificar la calidad del código:

```bash
npm run lint
```

## 📁 Estructura del Proyecto

```
test-firebase/
├── public/          # Archivos estáticos
├── src/             # Código fuente
│   ├── assets/      # Recursos (imágenes, iconos)
│   ├── App.tsx      # Componente principal
│   ├── main.tsx     # Punto de entrada
│   └── ...
├── firebase.json    # Configuración de Firebase
├── vite.config.ts   # Configuración de Vite
└── package.json     # Dependencias y scripts
```

## 🔧 Scripts Disponibles

- `npm run dev` - Inicia el servidor de desarrollo
- `npm run build` - Construye la aplicación para producción
- `npm run lint` - Ejecuta el linter
- `npm run preview` - Previsualiza la build de producción

## 📝 Notas

- El proyecto utiliza Hot Module Replacement (HMR) para una experiencia de desarrollo fluida
- TypeScript está configurado con reglas estrictas para mejor calidad de código
- ESLint está configurado con reglas específicas para React y TypeScript
