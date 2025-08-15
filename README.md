# 📦 Sistema de Gestión de Recolección y Almacén

Sistema completo de gestión para servicios de recolección y almacenamiento con interfaces móviles y de escritorio.

## 📋 Descripción del Proyecto

Este proyecto consiste en un conjunto de mockups interactivos diseñados para demostrar la funcionalidad completa de un sistema de gestión de recolección y almacén. Las interfaces están optimizadas tanto para dispositivos móviles como para escritorio, proporcionando una experiencia de usuario completa para todos los actores del sistema.

## 🎯 Propósito

Los mockups han sido desarrollados como **propuesta visual para cliente**, mostrando:
- Flujos de trabajo completos
- Interfaz de usuario moderna y profesional
- Funcionalidades específicas para cada tipo de usuario
- Diseño responsive y optimizado

## 👥 Tipos de Usuario

### 📱 **Almacén**
- Programación de recolecciones
- Gestión de paquetes
- Asignación de transportistas
- Dashboard administrativo

### 🚚 **Recolector/Transportista**
- Notificaciones de recolección
- Aceptación/rechazo de solicitudes
- Confirmación de entregas
- Registro fotográfico

### 🏢 **Administrador de Almacén**
- Vista de escritorio completa
- Gestión masiva de paquetes
- Asignación de transportistas
- Reportes y estadísticas

## 🖥️ Vistas del Sistema

### 📱 Vistas Móviles

#### 1. **Login Móvil** (`login-movil.html`)
- ✅ Autenticación por email y contraseña
- ✅ Diseño glass morphism
- ✅ Validación de campos
- ✅ Opción de registro
- ✅ Toggle de visibilidad de contraseña

#### 2. **Registro Móvil** (`registro-movil.html`)
- ✅ Selección de tipo de usuario (Recolector/Almacén)
- ✅ Formulario completo de registro
- ✅ Validación de contraseñas
- ✅ Términos y condiciones
- ✅ Estados de carga animados

#### 3. **Programar Recolección** (`programar-recoleccion.html`)
- ✅ Formulario completo de recolección
- ✅ Selección de fecha y hora
- ✅ Carga de foto del producto
- ✅ Opciones de pago (único/suscripción)
- ✅ Validación de geolocalización
- ✅ Notas adicionales

#### 4. **Notificación Recolector** (`notificacion-recolector.html`)
- ✅ Alertas push simuladas
- ✅ Información completa del pedido
- ✅ Countdown de tiempo límite
- ✅ Prioridades visuales
- ✅ Aceptar/rechazar con un toque
- ✅ Mapa de ubicación

#### 5. **Confirmar Entrega** (`confirmar-entrega.html`)
- ✅ Registro de datos del receptor
- ✅ Foto obligatoria de confirmación
- ✅ Geolocalización automática
- ✅ Comentarios adicionales
- ✅ Validación completa del formulario

### 🖥️ Vista de Escritorio

#### 6. **Dashboard Almacén** (`gestion-almacen-desktop.html`)
- ✅ Interface completa de gestión
- ✅ Lista de paquetes con filtros
- ✅ Búsqueda avanzada
- ✅ Selección múltiple
- ✅ Panel de asignación de transportistas
- ✅ Estadísticas en tiempo real
- ✅ Sidebar de navegación

## 🎨 Características de Diseño

### Paleta de Colores
- **Primario**: Gradiente azul-púrpura (`#667eea` → `#764ba2`)
- **Secundario**: Grises elegantes para texto y bordes
- **Acentos**: Verde para acciones positivas, rojo para alertas

### Efectos Visuales
- **Glass Morphism**: Contenedores semi-transparentes con blur
- **Animaciones**: Formas flotantes y transiciones suaves
- **Micro-interacciones**: Hover effects y estados de carga
- **Responsive**: Optimizado para móvil y escritorio

### Iconografía
- **Material Icons**: Conjunto completo de iconos de Google
- **Consistencia**: Iconos coherentes en toda la aplicación
- **Semántica**: Iconos que refuerzan la funcionalidad

## 🛠️ Stack Tecnológico

### Frontend
- **HTML5**: Estructura semántica y accesible
- **Tailwind CSS**: Framework CSS utilitario vía CDN
- **Vanilla JavaScript**: Funcionalidad interactiva
- **Material Icons**: Iconografía de Google

### Arquitectura
- **Self-contained**: Cada archivo HTML es independiente
- **No Build Process**: Archivos listos para ejecutar
- **CDN Dependencies**: Sin instalaciones locales necesarias
- **Responsive First**: Diseño mobile-first

## 🚀 Instalación y Uso

### Requisitos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Conexión a internet (para CDNs)

### Ejecución
```bash
# Clonar el repositorio
git clone [repository-url]
cd propuesta

# Abrir cualquier archivo HTML en el navegador
# Método 1: Hacer doble clic en el archivo
# Método 2: Desde terminal
open login-movil.html
# o
firefox login-movil.html

# Para la presentación completa
open presentacion-cliente.html
```

### Vista Previa Rápida
```bash
# Abrir todas las vistas principales
open login-movil.html
open registro-movil.html
open programar-recoleccion.html
open notificacion-recolector.html
open confirmar-entrega.html
open gestion-almacen-desktop.html
```

## 📁 Estructura del Proyecto

```
propuesta/
├── README.md                           # Este archivo
├── CLAUDE.md                          # Instrucciones para Claude Code
├── .github/
│   └── copilot-instructions.md        # Instrucciones para Copilot
├── login-movil.html                   # Vista de login móvil
├── registro-movil.html                # Vista de registro móvil
├── programar-recoleccion.html         # Vista de programación de recolecciones
├── notificacion-recolector.html       # Vista de notificaciones para recolectores
├── confirmar-entrega.html             # Vista de confirmación de entregas
├── gestion-almacen-desktop.html       # Dashboard de gestión de almacén
└── presentacion-cliente.html          # Presentación completa para cliente
```

## 💡 Funcionalidades Destacadas

### 📱 Móvil
- **Cámara integrada** para fotos en tiempo real
- **Geolocalización** automática
- **Notificaciones push** simuladas
- **Drag & Drop** para carga de archivos
- **Touch optimizado** con gestos intuitivos

### 🖥️ Escritorio
- **Gestión masiva** de paquetes
- **Filtros avanzados** y búsqueda
- **Asignación drag & drop** de transportistas
- **Dashboard en tiempo real**
- **Interface profesional** multi-panel

### 🔧 Técnicas
- **Validación client-side** completa
- **Estados de carga** animados
- **Error handling** user-friendly
- **Progressive enhancement**
- **Accessibility** considerations

## 🎬 Demo y Presentación

### Presentación para Cliente
El archivo `presentacion-cliente.html` contiene:
- **Portada profesional** con branding
- **Mockup de cada vista** con descripciones
- **Dos versiones del dashboard** (inicial y con selecciones)
- **Resumen técnico** del proyecto
- **Optimizado para PDF** (Ctrl+P para imprimir)

### Flujos de Usuario Demostrados

1. **Flujo de Almacén**:
   Login → Programar Recolección → Dashboard → Asignar Transportista

2. **Flujo de Recolector**:
   Login → Recibir Notificación → Aceptar → Confirmar Entrega

3. **Flujo Administrativo**:
   Dashboard → Seleccionar Paquetes → Asignar en Lote → Confirmar

## 🌍 Localización

- **Idioma**: Español (Colombia)
- **Direcciones**: Medellín, Antioquia
- **Formato de fecha**: DD/MM/YYYY
- **Moneda**: Pesos colombianos (COP)
- **Teléfonos**: Formato colombiano (+57)

## 📊 Datos de Ejemplo

### Direcciones de Medellín
- El Poblado: Carrera 43A #5-15
- Laureles: Calle 10 #43-25
- Estadio: Carrera 70 #52-21
- Buenos Aires: Av. Oriental #45-67

### Transportistas Ficticios
- Miguel Ángel Torres (Moto - El Poblado)
- Sandra Milena Vargas (Carro - Estadio)
- Andrés Felipe Gómez (Moto - Centro)
- Diana Carolina Ruiz (Bicicleta - El Poblado)

## 🔒 Consideraciones de Seguridad

- **Validación client-side** (demo purposes)
- **Sanitización** de inputs en producción requerida
- **HTTPS** recomendado para producción
- **Autenticación real** necesaria para implementación
- **Geolocalización** con permisos de usuario

## 🚧 Limitaciones Actuales

- **Solo mockups**: Sin backend funcional
- **Datos simulados**: No persisten entre sesiones
- **Sin autenticación real**: Login simulado
- **No PWA**: Funcionalidades offline limitadas
- **CDN dependiente**: Requiere conexión a internet

## 🔄 Próximos Pasos para Desarrollo

### Fase 1: Backend
- [ ] API REST con Node.js/PHP/Python
- [ ] Base de datos (MySQL/PostgreSQL/MongoDB)
- [ ] Sistema de autenticación JWT
- [ ] Upload de imágenes real

### Fase 2: Features Avanzadas
- [ ] PWA con service workers
- [ ] Notificaciones push reales
- [ ] Geolocalización avanzada
- [ ] Chat en tiempo real

### Fase 3: Producción
- [ ] Deploy en cloud (AWS/Azure/GCP)
- [ ] CI/CD pipeline
- [ ] Monitoring y logging
- [ ] Testing automatizado

## 🤝 Contribución

Este proyecto está diseñado como propuesta para cliente. Para contribuir:

1. **Fork** el proyecto
2. **Crear branch** para features (`git checkout -b feature/nueva-funcionalidad`)
3. **Commit** cambios (`git commit -m 'Add: nueva funcionalidad'`)
4. **Push** al branch (`git push origin feature/nueva-funcionalidad`)
5. **Crear Pull Request**

### Estándares de Código
- **HTML5** semántico y accesible
- **Tailwind CSS** para estilos
- **JavaScript vanilla** (ES6+)
- **Comentarios en español**
- **Nombres de variables descriptivos**

## 📄 Licencia

Este proyecto es una propuesta comercial. Todos los derechos reservados.

## 📞 Contacto

Para consultas sobre el proyecto o implementación:
- **Proyecto**: Sistema de Gestión de Recolección
- **Propósito**: Propuesta para cliente
- **Estado**: Mockups completados ✅

---

**Nota**: Este README describe mockups interactivos diseñados para demostración. Para implementación en producción, se requiere desarrollo de backend y características adicionales de seguridad.