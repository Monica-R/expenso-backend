# Expenso Backend

Este es el backend de Expenso, una aplicación de finanzas personales que permite gestionar ingresos y gastos. Se ha construido con JSON Server para simular una API REST, proporcionando un CRUD funcional para las transacciones.

## Instalación y ejecución

Clonar el repositorio:

git clone <URL_DEL_REPOSITORIO>
cd expenso-backend

Instalar dependencias con Bun:

bun install

Crear un archivo .env en la raíz con el siguiente contenido:

PORT=3001

Iniciar el servidor en modo desarrollo:

bun run dev

O en modo producción:

bun run start


## Endpoints disponibles

GET /movements → Obtiene todas las transacciones

GET /movements/:id → Obtiene una transacción por ID

POST /movements → Agrega una nueva transacción

PUT /movements/:id → Actualiza una transacción existente

DELETE /movements/:id → Elimina una transacción
