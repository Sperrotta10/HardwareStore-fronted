# 🛠️ HardwareStore-fronted

En este proyecto se va a desarrollar el frontend del ecommerce de Hardware store

---

## 🧩 Modulos Ecommerce

- Productos 🔨
- Register/Login 📩
- Carrito de compras 🛒
- Pago 💵
- Administrador 👨‍💼
- Ventas 📊
- Notificaciones 🔔

---

## 🔧 Tecnologias

- Frontend --> React + Vite
- Backend --> TypeScript

---

## 📂 Estructura de las carpetas

```text
.
├──frontend/ 
├────  public/                  # imagenes, iconos
├────  src/                     # Estructura del frontend
├───────── assets/
├───────── modules/
│───────────├── cart-shopping/
│───────────│   ├── components/
│───────────│   ├── hooks/
│───────────│   ├── services/           # lógica de negocio o dominio
│───────────│   ├── utils/
│───────────│   ├── pages/
│───────────│   ├── types/
│───────────│   └── store/
│───────────├── login/
│───────────└── ...
├───────── routes/                # rutas generales del proyecto
├───────── shared/                # componentes reutilizables globalmente
├───────── config/                # configuración de axios, temas, etc
├───────── styles/                # tailwind, variables css, temas
├───────── main.tsx
├───────── App.tsx
├───── node_modules/        # node modules
├───── .env                 # Variables de entorno
├───── package.json         # Paquetes instalados
├───── package-lock.json    # Configuracion de los paquetes
├───── .gitignore           # Contenido que se requiere ignorar
├───── eslint.config.js     # cnofig del eslint
├───── tsconfig.app.json    # config de typescript
├───── tsconfig.json        # config de typescript
├───── tsconfig.node.json   # config de typescript
├───── vite.config.ts       # config de vite
└──README.md                # Informacion del proyecto
```

---

## 🚀 Como ejecutar el proyecto

Paso 1: Clonar el repositorio
```bash
git clone https://github.com/Sperrotta10/HardwareStore-fronted
```

Paso 2: Dirigirse a la carpeta de fronted
```bash
cd frontend
```

Paso 3: Instalar las dependencias
```bash
npm install
```

Paso 4: Ejecutar el proyecto
```bash
npm run dev
```

---