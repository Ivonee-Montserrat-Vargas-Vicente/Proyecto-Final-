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


