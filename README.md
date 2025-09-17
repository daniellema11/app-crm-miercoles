# 📊 CRM de Clientes y Productos

Sistema de gestión de relaciones con clientes (CRM) desarrollado con JavaScript vanilla, siguiendo una arquitectura MVC y utilizando módulos ES6.

## 🚀 Características

- ✨ **JavaScript Vanilla**: Sin dependencias de frameworks pesados
- 📦 **Módulos ES6**: Uso de import/export para una mejor organización del código
- 🏗️ **Arquitectura MVC**: Separación clara entre Modelo, Vista y Controlador
- 🍬 **SweetAlert**: Notificaciones y alertas elegantes
- 👥 **Gestión de Clientes**: Registro, edición y eliminación de clientes
- 📦 **Gestión de Productos**: Administración completa de productos
- 💾 **Local Storage**: Persistencia de datos en el navegador
- 📱 **Diseño Responsivo**: Interface adaptable a diferentes dispositivos

## 📁 Estructura del Proyecto

```
app-crm-miercoles/
├── index.html              # Página principal
├── styles.css              # Estilos globales
├── script.js               # Archivo principal de JavaScript
├── controllers/            # Controladores MVC
│   ├── clienteController.js
│   └── productoController.js
├── models/                 # Modelos de datos
│   ├── Cliente.js
│   └── Producto.js
├── views/                  # Vistas y componentes UI
├── services/              # Servicios y utilidades
│   ├── storage.js
│   └── validator.js
└── README.md              # Este archivo
```

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: Estilos y animaciones
- **JavaScript ES6+**: Lógica de aplicación
- **SweetAlert**: Biblioteca para alertas
- **Local Storage**: Almacenamiento local del navegador

## ⚡ Instalación y Uso

### Prerrequisitos
- Navegador web moderno con soporte para ES6 modules
- Servidor local (opcional, recomendado para desarrollo)

## 🎨 Estilos y UI

- **CSS personalizado** con animaciones
- **Formularios responsivos**
- **Efectos visuales** con capas decorativas
- **Paleta de colores** moderna y profesional

## 🧪 Validaciones

### Validaciones de Cliente
- **Nombre**: Mínimo 2 caracteres, solo letras
- **Apellido**: Mínimo 2 caracteres, solo letras
- **Documento**: Formato numérico, único
- **Teléfono**: Formato válido
- **Género**: Selección obligatoria

## 🤝 Contribuir

1. Fork del proyecto
2. Crear una rama para tu feature (`git checkout -b feature/nueva-funcionalidad`)
3. Commit de tus cambios (`git commit -m 'Agregar nueva funcionalidad'`)
4. Push a la rama (`git push origin feature/nueva-funcionalidad`)
5. Abrir un Pull Request


## 👨‍💻 Autor

**Tu Nombre**
- GitHub: [jaimezzapata](https://github.com/jaimezzapata)


⭐ Si te gusta este proyecto, ¡no olvides darle una estrella!

## 📚 Recursos Adicionales

- [MDN Web Docs - Módulos JavaScript](https://developer.mozilla.org/es/docs/Web/JavaScript/Guide/Modules)
- [SweetAlert Documentation](https://sweetalert2.github.io/)
- [Patrón MVC en JavaScript](https://www.patterns.dev/posts/mvc-pattern/)