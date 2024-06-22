# Backend en Nest

## 📄 Descripción

Este es el backend del proyecto que se encarga ....

## 💻 Tecnologías Utilizadas

- TypeScript
- [Nest](https://nestjs.com/)
- [Mongoose](https://docs.nestjs.com/techniques/mongodb)
- [Bcrypt](https://docs.nestjs.com/security/encryption-and-hashing)

## 📋 Requisitos

- Node.js y npm instalados en tu sistema. Puedes descargarlos desde [nodejs.org](https://nodejs.org/).
- Nest instalado globalmente. Puedes instalarlo con el siguiente comando:

```bash
npm i -g @nestjs/cli
```

## 🛠️ Instalación

Tener Docker desktop corriendo

**✔️ Paso 1:** Levanta el servidor de base de datos.

```bash
docker compose up -d
```

**✔️ Paso 2:** Clona el repositorio:

```bash
git clone https://github.com/Yul1b3th/eventcanvas.git
```

**✔️ Paso 3:** Ingresa al directorio del proyecto:

```bash
cd eventcanvas
```

**✔️ Paso 4:** Copia el archivo **_.env.template_** y renómbralo como **_.env_**. Este archivo contendrá las variables de entorno necesarias para la configuración del proyecto.

**✔️ Paso 5:** Abre el archivo **_.env_** y completa las variables de entorno según las especificaciones proporcionadas en el archivo.

**✔️ Paso 6:** Instala las dependencias:

```bash
npm install
```

## ▶️ Ejecución

Ejecuta la aplicación con el siguiente comando:

```bash
 npm run start:dev
```

Conectar Nest con MongoDB

Hacer el registro de un nuevo usuario
localhost:3000/auth/register

## 🚧 Endpoints de la API

### Usuarios

- **GET /auth**: Obtiene todos los usuarios.
- **GET /auth/:id**: Obtiene un usuario por ID.
- **POST /auth/register**: Crea un nuevo usuario.

**Nota:** Reemplaza **:id** con el ID del usuario correspondiente.

## 🤝 Contribuciones

Si deseas colaborar en este proyecto o informar sobre problemas, no dudes en crear un "issue" o enviar un "pull request."
