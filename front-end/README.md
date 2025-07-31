# AgroConecta

AgroConecta es una plataforma web que conecta directamente a agricultores con compradores, eliminando intermediarios y fomentando el comercio justo de productos agrícolas frescos y locales.

## 🌱 Descripción

Esta aplicación web facilita la comunicación y comercialización entre productores agrícolas y compradores, ofreciendo:

- **Conexión directa**: Los agricultores pueden publicar sus productos con información detallada sobre técnicas de cultivo, insumos utilizados y ubicación
- **Comunicación en tiempo real**: Sistema de mensajería integrado para negociación directa de precios y coordinación

## 🚀 Características Principales

### Para Agricultores
- Gestión completa de productos (crear, editar, eliminar)
- Publicación de información detallada sobre cultivos e insumos
- Dashboard personalizado para seguimiento de productos
- Sistema de mensajería con compradores potenciales

### Para Compradores
- Búsqueda avanzada de productos por categoría, y filtros
- Visualización detallada de productos con información del agricultor
- Comunicación directa con productores
- Navegación intuitiva y responsive

### Características Técnicas
- Interfaz moderna y responsive con Tailwind CSS
- Componentes reutilizables con Radix UI
- Gestión de estado global con Zustand
- Comunicación en tiempo real con Socket.io
- Autenticación y autorización por roles (agricultor/comprador)

## 🛠️ Tecnologías Utilizadas

- **Frontend**: React 19 + Vite
- **Styling**: Tailwind CSS + CSS Modules
- **UI Components**: Radix UI + Lucide React Icons
- **Routing**: React Router DOM v7
- **State Management**: Zustand
- **HTTP Client**: Axios
- **Real-time**: Socket.io Client
- **Forms**: React Hook Form
- **Build Tool**: Vite

## 📦 Instalación y Configuración

### Prerrequisitos
- Node.js (versión 18 o superior)
- npm o bun

### Pasos de instalación

1. **Clonar el repositorio**
   ```bash
   git clone [URL_DEL_REPOSITORIO]
   cd front-end
   ```

2. **Instalar dependencias**
   ```bash
   npm install
   # o usando bun
   bun install
   ```

3. **Iniciar el servidor de desarrollo**
   ```bash
   npm run dev
   # o usando bun
   bun dev
   ```

4. **Acceder a la aplicación**
   La aplicación estará disponible en `http://localhost:5173`

## 📁 Estructura del Proyecto

```
src/
├── components/ui/          # Componentes base reutilizables
├── features/              # Funcionalidades por módulos
│   ├── authentication/    # Login, registro y gestión de usuarios
│   ├── home/             # Página de inicio y landing
│   ├── messaging/        # Sistema de mensajería
│   ├── product-discovery/ # Búsqueda y descubrimiento de productos
│   └── product-management/ # Gestión de productos para agricultores
├── shared/               # Componentes y utilidades compartidas
│   ├── components/       # Componentes compartidos
│   ├── context/         # Contextos de React
│   └── utils/           # Utilidades y configuraciones
└── styles/              # Estilos globales
```

## 🎯 Scripts Disponibles

- `npm run dev`: Inicia el servidor de desarrollo
- `npm run build`: Construye la aplicación para producción
- `npm run preview`: Previsualiza la construcción de producción

## 🤝 Contribución

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - consulta el archivo [LICENSE](LICENSE) para más detalles.

## 🌐 Impacto Social

AgroConecta busca:
- Apoyar a los agricultores locales garantizando precios justos
- Reducir la huella de carbono promoviendo el consumo local
- Fomentar la transparencia en la cadena de suministro agrícola
- Fortalecer la economía rural mediante la tecnología
