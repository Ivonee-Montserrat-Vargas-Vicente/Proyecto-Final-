# Proyecto-Final-
Esto es un proyecto basado en la materia de Topicos Avanzados De Programacion , el objetivo es implementar un proyecto completo con base a los conocimientos adquiridos en la materia bienvenido a nuestra empresa de ropa diseñada y pensada para las mujeres 

# 👗 Proyecto Novae

**Novae** es un proyecto de venta de ropa de mujer enfocado en **empoderar y hacer sentir segura** a cada clienta a través de su estilo.

## 🌟 Objetivo Principal

Brindar ropa moderna, cómoda y elegante que resalte la autenticidad y seguridad de la mujer en cada momento de su vida.

## 🛍️ ¿Qué ofrece Novae?

- 📦 **Gestión de inventario** eficiente y automatizada
- 💳 **Opciones de pago modernas**: efectivo, tarjeta, transferencia
- 🧾 **Registro de ventas y clientes** para control y seguimiento
- 🌐 **Plataforma accesible**, tanto en tienda física como en línea

## ❤️ Filosofía Novae

En **Novae**, cada prenda está pensada para que la mujer se sienta **cómoda, segura y fiel a sí misma**. No seguimos tendencias, **creamos experiencias**.

> "Moda con propósito, estilo con identidad."

---

🔗 *Desarrollado con pasión para transformar la moda en una herramienta de confianza femenina.*

----------------------------------------------------------
## 🔐 Ventana de Inicio de Sesión (Login)

La aplicación **Novae** comienza con una ventana de inicio de sesión que permite acceder de forma segura al sistema de ventas. Este módulo es esencial para proteger la información del negocio y garantizar que solo usuarios autorizados puedan acceder a las funcionalidades para ingresar el usuario es el correo y una contraseña.

### 🧾 Características del Login

- ✅ Validación de usuario y contraseña
- 🔒 Seguridad básica con validaciones de entrada
- ⚠️ Mensajes de error en caso de datos incorrectos


### 🧩 Campos de entrada

- 🆔 **Usuario (correo electrónico o nombre de usuario)**
- 🔑 **Contraseña**
- 🔘 **Botones:**
  - `Aceptar` → Valida los datos e ingresa al sistema
  - `visualizar contraseña` → Cierra la aplicación

### 💡 Nota técnica

> El login está desarrollado en Java utilizando `JFrame`, sin imágenes ni íconos externos, para mantener un diseño limpio y funcional, compatible con el resto de las ventanas del sistema.

![Captura de pantalla 2025-06-09 092206](https://github.com/user-attachments/assets/1053edd2-72a9-48b3-9792-42b00db52a1d)



------------------------
## 🔑 Acceso y Roles de Usuario

Una vez que el usuario inicia sesión correctamente en **Novae**, el sistema muestra un mensaje de confirmación para indicar que el acceso ha sido exitoso y le da la bienvenida según su rol asignado.

### ✅ Confirmación de Inicio de Sesión

Al ingresar credenciales válidas, se muestra el siguiente mensaje:

![Captura de pantalla 2025-06-09 093301](https://github.com/user-attachments/assets/34396814-c458-469c-9642-e2eb83cc21ca)
![image](https://github.com/user-attachments/assets/b88307b4-55cd-4fcd-9905-6e7767632c82)


---

### 👥 Roles Disponibles

| Rol          | Descripción                                                                 |
|--------------|------------------------------------------------------------------------------|
| 🛠️ Administrador | Accede a todas las funcionalidades del sistema: gestión de productos, usuarios, ventas. |
| 💵 Cajero       | Tiene acceso limitado a los productos solo puede visualizar,modificar y ver el carrito      |

### 🧭 Redirección según el rol

- Si el usuario es **Administrador**, se redirige al **menú principal** con acceso completo.
- Si el usuario es **Cajero**, se redirige directamente a la ventana de **modificar/visualizar/carrito**.

---

🔐 Esto permite una estructura más segura, organizada y orientada al control de accesos según la responsabilidad del personal.


## 🛠️ Rol de Administrador

El **Administrador** es el usuario con mayor nivel de acceso dentro del sistema **Novae**. Su función principal es gestionar y supervisar todas las operaciones clave del sistema, desde el control de productos hasta la administración de personal .

### 📋 Funcionalidades del Administrador

| Módulo                     | Descripción                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| 🧾 Gestión de Productos     | Agregar, editar, eliminar y visualizar productos en el inventario.          |
| 📂 Categorías              | Crear y modificar categorías de productos (Ej: blusas, pantalones, etc.). |
| 👤 Gestión de Usuarios     | Registrar y administrar cuentas de Cajeros.                               |
| 📈 Reportes de Ventas      | Consultar reportes diarios, semanales o mensuales con filtros avanzados.  |
| 🔍 Control de Stock        | Visualizar niveles de inventario          |
| 🛒 Supervisión de Ventas   | Ver historial completo de ventas realizadas por los cajeros.              |
| ⚙️ Configuración del sistema | Ajustes generales del sistema, descuentos y parámetros globales.          |


## 📌 Menú Principal: **Inicio**

El menú **Inicio** es la primera pantalla del sistema y actúa como puerta de entrada a las funcionalidades del sistema. Está compuesto por las siguientes secciones:

### 🔹 Información

Aquí se presenta una breve introducción a la empresa y su propósito:

<img width="610" alt="image" src="https://github.com/user-attachments/assets/2132ec47-8d69-469d-84f6-a65a8010733d" />

- 🌐 Horario(Fecha y hora de atención)
- 📞 Información de contacto (Direccion, correo, telefono y redes sociales).

### 🔹 Registro de Usuario

Esta sección permite que nuevas clientas o usuarios del sistema se registren de forma sencilla:
<img width="470" alt="image" src="https://github.com/user-attachments/assets/0307f6c8-4cbf-410d-96a1-851170ccb03c" />

- 🧍‍♀️ **Formulario de registro** con los siguientes campos:
  - Nombre
  - Apellido
  - Usuario (Correo electrónico)
  - Contraseña
  - Confirmación de contraseña
 - Tipo de usuario
- ✅ Mensajes de éxito o error tras completar el registro.

  ## 🛍️ Menú: Producto

La sección **Producto** permite una gestión completa del inventario de ropa, asegurando que cada prenda esté debidamente registrada, actualizada y disponible para su venta.

Esta sección incluye las siguientes funcionalidades:
<img width="418" alt="image" src="https://github.com/user-attachments/assets/5b513dba-fd9e-4ea9-ad17-4a06fb07988c" />


### 🔹 Registrar Producto
<img width="607" alt="Captura de pantalla 2025-06-09 a la(s) 11 09 30 a m" src="https://github.com/user-attachments/assets/87428109-697f-4480-a0d1-2fa2663e3682" />

Formulario para agregar nuevos productos al inventario. Los campos disponibles son:

- 🏷️ **Nombre**: Nombre del producto.
- 📝 **Descripción**: Detalles del producto (tipo de prenda, estilo, etc.).
- 🗂️ **Categoría**: Clasificación (Ej: Blusas, Pantalones, Vestidos, etc.).
- 📏 **Talla**: Tallas disponibles (S, M, L, XL, etc.).
- 🎨 **Color**: Color principal del producto.
- 💲 **Precio**: Precio unitario.
- 📦 **Stock**: Cantidad disponible.
- 🧾 **Proveedor**: Nombre del proveedor.
- 📌 **Estado**: Activo o Inactivo (para descontinuados o fuera de temporada).

**Botones disponibles:**
- ✅ `Registrar`
- ❌ `Cancelar`

---

### 🔹 Modificar Producto

Permite editar los datos de un producto previamente registrado.  
Se pueden actualizar todos los campos mencionados arriba y guardar los cambios fácilmente.
<img width="607" alt="image" src="https://github.com/user-attachments/assets/5c5ad9ae-e33d-45d3-bf7c-ac371f4548a7" />


---

### 🔹 Visualizar Productos
<img width="907" alt="image" src="https://github.com/user-attachments/assets/fe1a8c5d-2234-4766-9e34-86f6104a6c2b" />

Muestra una tabla con todos los productos disponibles, incluyendo filtros por:

- Categoría
- Talla
- Color
- Precio
- Stock
- Estado
- Proveedor
- Nombre

Esto facilita encontrar y revisar cualquier prenda del inventario.

---

### 🔹 Eliminar Producto
<img width="509" alt="Captura de pantalla 2025-06-09 a la(s) 11 15 16 a m" src="https://github.com/user-attachments/assets/0b966d98-2364-4dbd-976f-29de735f24a9" />



Funcionalidad para dar de baja un producto, eliminándolo del sistema si ya no se comercializa.  
Se puede confirmar la eliminación para evitar errores.
Solo pide el id del menu para eliminarlo

---

## 📖 Menú: Historial

La sección **Historial** permite consultar de forma detallada todas las ventas realizadas en la boutique. Es una herramienta clave para el control interno, auditorías y análisis de desempeño.

---

### 🔹 Historial de Ventas

Muestra un registro completo y ordenado de cada transacción realizada.  
La tabla incluye la siguiente información por cada venta:
<img width="900" alt="image" src="https://github.com/user-attachments/assets/d7cdcfe9-f75f-42bd-9ba9-09902df01830" />


- 🧾 **ID Venta**: Identificador único de la transacción.
- 👩‍💼 **ID Cliente**: Cliente asociado a la compra.
- 📅 **Fecha**: Día en que se realizó la venta.
- 💰 **Total**: Monto total pagado.
- 💳 **Método de Pago**: Efectivo, tarjeta, transferencia, etc.
- 📌 **Estado**: Puede indicar si la venta fue completada, cancelada o en proceso.
- 🧑‍💼 **ID Empleado**: Empleado responsable de realizar la venta.

---
## 🛒 Menú: Carrito de Compras

La sección **Carrito de Compras** está diseñada para facilitar el proceso de venta de manera rápida y organizada. Es una herramienta esencial para el flujo de caja y la atención al cliente.
<img width="1003" alt="image" src="https://github.com/user-attachments/assets/bf7e486b-7c41-4abe-b71f-dfba5957bc28" />


### 🔹 Funcionalidades principales

La interfaz del carrito incluye:

#### 🔍 Buscador superior
Permite buscar productos por nombre o ID, facilitando la selección rápida de artículos disponibles en el sistema.

#### 📋 Tabla de productos disponibles

La tabla muestra los siguientes campos:

- 🆔 **ID**: Identificador del producto.
- 🏷️ **Nombre**: Nombre de la prenda.
- 💲 **Precio**: Precio unitario del producto.
- 📦 **Stock**: Cantidad disponible en inventario.

---

### 🔘 Botones disponibles

- ➕ **Agregar al carrito**: Añade el producto seleccionado a la venta actual.
- 💳 **Finalizar compra**: Registra la venta en el sistema y actualiza el historial.
- ❌ **Cerrar**: Sale del carrito sin realizar cambios o finaliza la sesión del proceso de venta.

---
## 🚪 Menú: Cerrar

La opción **Cerrar** permite salir de la vista actual y regresar de forma segura al **Menú Principal** del sistema.

---
## 🎬 Demo del Proyecto

🧵 Observa cómo funciona Novae en tiempo real:  
[▶️ Ver video en YouTube]([https://www.youtube.com/watch?v=ID_DEL_VIDEO](https://youtu.be/2IuSjiku_OQ?si=HMtjPpHcWS3vUO1w))





