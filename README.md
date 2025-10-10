# RESTAURANT-FRANCES
Proyecto equipo 7, Gestión de pedidos para restaurant.

( les deje el readme para que indquen que librerias usaron y como poder instalarlas asi lo pueden ejecutar o modificar a gusto, recuerden que deben descargarlo y crear
una copia para luego re nombrarla y modificar solo esa, el otro que nadie toco es el que sera entregado y usado para mesclar ideas del grupo )

¡Entendido\! Aquí tienes el `README.md` enfocado en lo que ya hemos hecho y, crucialmente, lo que queda pendiente para que los otros miembros del equipo puedan retomar el trabajo fácilmente.

Guarda este texto en un archivo llamado **`README.md`** en la carpeta **raíz de tu proyecto**: `D:\proyecto-restaurante\`

## Creacion de estructuras y primeros pasos

````markdown
# 🍽️ Proyecto Restaurante Francés: Digitalización

Este repositorio contiene el proyecto para la digitalización de los procesos de un restaurante francés, dividido en un Backend (API) y un Frontend (Web App).

## 🚀 Estado Actual del Proyecto (Checkpoint)

| Componente | Estado | Ubicación Clave |
| :--- | :--- | :--- |
| **Estructura** | Completa (Backend/Frontend/Src/Components) | Raíz del Proyecto |
| **Backend (API)** | Listo para Endpoints (Node.js/Express) | `server.js` |
| **HU1: Reserva de mesas** | Endpoint API creado | `server.js` |
| **HU2: Menú Digital** | Endpoint API creado | `server.js` |
| **HU3: Realizar Pedidos** | Endpoint API creado | `server.js` |

**Nota Importante:** La lógica del Backend (`server.js`) está creada usando **arrays en memoria** como base de datos simulada.

---

## 📋 Pendientes para Continuar

El foco principal es la implementación de la **interfaz de usuario (Frontend)** y la integración con la API existente.

| ID | Funcionalidad | Descripción (Qué falta) | Asignado |
| :--- | :--- | :--- | :--- |
| **HU1** | Reserva de mesas | **Frontend:** Crear el componente de React (`ReservaMesas.js`) para capturar datos y hacer la petición `POST /api/reservas`. | [Miembro A] |
| **HU2** | Menú Digital | **Frontend:** Crear el componente de React (`MenuDigital.js`) para hacer la petición `GET /api/menu` y mostrar el listado de platillos. | [Miembro B] |
| **HU3** | Realizar Pedidos | **Frontend:** Extender `MenuDigital` para que permita seleccionar ítems y enviar la petición `POST /api/pedidos`. | [Miembro C] |
| **HU4** | Pago en línea | **Backend/Frontend:** Implementación completa (integración con pasarela de pagos simulada o real). | [Miembro D] |
| **HU5** | Modificar Menú | **Backend/Frontend:** Crear endpoints `POST/PUT/DELETE /api/menu` y un panel de administración para usarlos. | [Miembro B] |
| **HU6** | Gestión de pedidos | **Backend/Frontend:** Crear endpoints `GET/PUT /api/pedidos/{id}` y un panel para el personal que muestre y actualice el estado de los pedidos. | [Miembro A] |

---

## ⚙️ Cómo Levantar el Proyecto

### Requisitos

Asegúrate de tener **Node.js** y **npm** instalados.

### 1. Configuración Inicial (Solo la primera vez)

Desde la carpeta raíz (`proyecto-restaurante`):

```bash
# 1. Instala las dependencias del Backend (API)
npm install
npm install cors

# 2. Crea el proyecto React y sus dependencias (Si no lo hizo `npx create-react-app`)
npx create-react-app frontend
cd frontend
npm install
cd ..
````

### 2\. Ejecución

Debes usar dos terminales separadas.

#### Terminal 1: Backend (API)

```bash
cd proyecto-restaurante
npm start
# La API correrá en: http://localhost:3000
```

#### Terminal 2: Frontend (Web App)

```bash
cd frontend
npm start
# La app web correrá en: http://localhost:3001 (o similar)
```

-----

```
¿Te gustaría que te ayude con el siguiente paso, que sería empezar con el código del componente **`MenuDigital.js`** para que el Miembro B tenga código base?
```
