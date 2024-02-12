# Project 2 - Veterinary management 🐶

## Árbol de Trabajo 📂
```
└── 📁Backend-Frontend
    └── README.md
    └── 📁Backend
        └── .env.example
        └── .gitignore
        └── package-lock.json
        └── package.json
        └── 📁src
            └── database.js
            └── index.js
            └── server.js
            └── 📁config
                └── nodemailer.js
            └── 📁controllers
                └── paciente_controller.js
                └── tratamiento_controller.js
                └── veterinario_controller.js
            └── 📁helpers
                └── crearJWT.js
            └── 📁middlewares
                └── autenticacion.js
                └── validacionVeterinario.js
            └── 📁models
                └── Paciente.js
                └── Tratamiento.js
                └── Veterinario.js
            └── 📁routers
                └── paciente_routes.js
                └── tratamiento_routes.js
                └── veterinario_routes.js
    └── 📁Frontend
        └── .env.example
        └── .gitignore
        └── index.html
        └── package-lock.json
        └── package.json
        └── postcss.config.cjs
        └── tailwind.config.cjs
        └── vite.config.cjs
        └── 📁public
            └── 📁images
        └── 📁src
        └── App.css
        └── App.jsx
        └── index.css
        └── main.jsx
            └── 📁assets
            └── 📁components
                └── 📁Alertas
                    └── Mensaje.jsx
                └── 📁Perfil
                    └── CardPerfil.jsx
                    └── FormularioPerfil.jsx
                └── Formulario.jsx
                └── Tabla.jsx
            └── 📁context
                └── AuthProvider.jsx
            └── 📁layout
                └── Auth.jsx
                └── Dashboard.jsx
            └── 📁paginas
                └── Actualizar.jsx
                └── Confirmar.jsx
                └── Crear.jsx
                └── Forgot.jsx
                └── LandingPage.jsx
                └── Listar.jsx
                └── Login.jsx
                └── NotFound.jsx
                └── Perfil.jsx
                └── Register.jsx
                └── Restablecer.jsx
                └── Visualizar.jsx
```
## Clonación e Instalación ⌨️
Para acceder al proyecto se debe realizar la clonación del mismo mediante:
```
git clone https://github.com/brittanypallasco2003/api-veterinaria.git
```
> [!NOTE]
>
> Este proyecto trabaja con el sistema de módulos ES Modules

### Instalación de Dependencias

> [!IMPORTANT]
>
> Una vez clonado el repositorio se debe correr, por terminal, el siguente comando para poder instalar las dependencias correspondientes al proyecto.

```
npm i
```

## Environment Variables 🗄️
### Backend ⚙️
**Cadena de conexión BDD:**

`MONGODB_URI`

**Servidor SMTP:**

`URL_FRONTEND` 
`HOST_MAILTRAP`
`PORT_MAILTRAP`
`USER_MAILTRAP`
`PASS_MAILTRAP`

> [!NOTE]
>
> Este sistema tiene un enfoque Stateless, por lo tanto, se tiene una variable de entorno para el secreto JWT que permitirá firmar y verificar la autenticidad del token.

**Jason Web Token**

`JWT_SECRET`

### Frontend 🎨

`VITE_BACKEND_URL`

Landing Page
------
![Image text](https://raw.githubusercontent.com/Byrontosh/Plantilla-App-Demo/main/src/assets/fondos/captura-1.png)


Login
------
![Image text](https://raw.githubusercontent.com/Byrontosh/Plantilla-App-Demo/main/src/assets/fondos/captura-2.png)

Register
------
![Image text](https://raw.githubusercontent.com/Byrontosh/Plantilla-App-Demo/main/src/assets/fondos/captura-3.png)

Forgot Password
------
![Image text](https://raw.githubusercontent.com/Byrontosh/Plantilla-App-Demo/main/src/assets/fondos/captura-4.png)

Confirm email
------
![Image text](https://raw.githubusercontent.com/Byrontosh/Plantilla-App-Demo/main/src/assets/fondos/captura-6.png)

Not Found
------
![Image text](https://raw.githubusercontent.com/Byrontosh/Plantilla-App-Demo/main/src/assets/fondos/captura-5.png)

Dashboard
------
![Image text](https://raw.githubusercontent.com/Byrontosh/Plantilla-App-Demo/main/src/assets/fondos/captura-7.png)
