# Backend API - Servicio de Saludo

## API simple construida con Node.js que proporciona un endpoint de saludo.

1.- 🚀 Características

- Endpoint GET `/saludo` que devuelve un mensaje de saludo
- Configuración mínima con Express.js
- Puerto configurable (3000 por defecto)

2.- 📦 Prerrequisitos

- Node.js v16+
- npm o yarn

3.- 🔧 Instalación

3.1. Clonar el repositorio:
	git clone [URL_DEL_REPOSITORIO]
	cd mi-backend-api

3.2. Instalar dependencias:
	npm install
	o
	yarn install

4.- 🏃 Ejecución
Para iniciar el servidor en desarrollo:
	npm start
	o
	yarn start
El servidor estará disponible en:
	http://localhost:3000

5.- 🌐 Endpoints
	GET /saludo
	Devuelve un mensaje de saludo en formato JSON.

	Ejemplo de respuesta:
		json
		{
		  "mensaje": "¡Hola desde el backend!"
		}
6.- 🔧 Configuración
	Puedes modificar el puerto creando un archivo .env:
		PORT=4000
	O pasando la variable de entorno al ejecutar:
		PORT=4000 npm start
7.- 🧪 Testing
Para ejecutar pruebas (si existen):
	npm test
8.- 🛠️ Estructura del Proyecto
mi-backend-api/
├── node_modules/
├── src/
│   ├── index.js          # Configuración principal de Express
├── package.json
└── README.md

> ⌨️ Atentamente, María Alina Vargas García