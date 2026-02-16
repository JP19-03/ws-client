# ws-client

Cliente WebSocket para interactuar con un servidor usando Socket.IO.

## Características

- Conexión a servidor WebSocket mediante JWT.
- Visualización del estado del servidor (Online/Offline).
- Lista de clientes conectados.
- Envío y recepción de mensajes en tiempo real.

## Instalación

1. Clona el repositorio.
2. Instala dependencias:

   ```sh
   npm install
   ```

## Uso

- Inicia el servidor backend compatible con Socket.IO.
- Ejecuta el cliente en modo desarrollo:

   ```sh
   npm run dev
   ```

- Ingresa tu token JWT y haz clic en "Connect".

## Scripts

- `npm run dev`: Inicia el modo desarrollo con Vite.
- `npm run build`: Compila TypeScript y construye el proyecto.
- `npm run preview`: Previsualiza el proyecto construido.

## Estructura

- `src/`: Código fuente principal.
- `index.html`: Entrada de la aplicación.
- `style.css`: Estilos.

## Dependencias

- [socket.io-client](https://www.npmjs.com/package/socket.io-client)
- [vite](https://vitejs.dev/)
- [typescript](https://www.typescriptlang.org/)