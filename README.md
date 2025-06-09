# Proyecto-Final-
Esto es un proyecto basado en la materia de Topicos Avanzados De Programacion , el objetivo es implementar un proyecto completo con base a los conocimientos adquiridos en la materia bienvenido a nuestra empresa de ropa diseñada y pensada para las mujeres 

# 👗 Proyecto Novae

**Novae** es un proyecto de venta de ropa de mujer enfocado en **empoderar y hacer sentir segura** a cada clienta a través de su estilo.

## 🌟 Objetivo Principal

Brindar ropa moderna, cómoda y elegante que resalte la autenticidad y seguridad de la mujer en cada momento de su vida.

## 🛍️ ¿Qué ofrece Novae?

- 👚 **Catálogo variado** de prendas para todos los estilos
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
-

### 🧩 Campos de entrada

- 🆔 **Usuario (correo electrónico o nombre de usuario)**
- 🔑 **Contraseña**
- 🔘 **Botones:**
  - `Aceptar` → Valida los datos e ingresa al sistema
  - `visualizar contraseña` → Cierra la aplicación

### 💡 Nota técnica

> El login está desarrollado en Java utilizando `JFrame`, sin imágenes ni íconos externos, para mantener un diseño limpio y funcional, compatible con el resto de las ventanas del sistema.

![Captura de pantalla 2025-06-09 092206](https://github.com/user-attachments/assets/1053edd2-72a9-48b3-9792-42b00db52a1d)
![image](https://github.com/user-attachments/assets/b88307b4-55cd-4fcd-9905-6e7767632c82)


------------------------
## 🔑 Acceso y Roles de Usuario

Una vez que el usuario inicia sesión correctamente en **Novae**, el sistema muestra un mensaje de confirmación para indicar que el acceso ha sido exitoso y le da la bienvenida según su rol asignado.

### ✅ Confirmación de Inicio de Sesión

Al ingresar credenciales válidas, se muestra el siguiente mensaje:

![Captura de pantalla 2025-06-09 093301](https://github.com/user-attachments/assets/34396814-c458-469c-9642-e2eb83cc21ca)



---

### 👥 Roles Disponibles

| Rol          | Descripción                                                                 |
|--------------|------------------------------------------------------------------------------|
| 🛠️ Administrador | Accede a todas las funcionalidades del sistema: gestión de productos, usuarios, ventas y reportes. |
| 💵 Cajero       | Tiene acceso limitado solo al módulo de ventas y emisión de tickets.     |

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
<img width="907" alt="image" src="https://github.com/user-attachments/assets/8a315987-ae73-4f81-9c22-b8dab60d619f" />


Funcionalidad para dar de baja un producto, eliminándolo del sistema si ya no se comercializa.  
Se puede confirmar la eliminación para evitar errores.
Solo pide el id del menu para eliminarlo

---




