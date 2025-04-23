# Creación de Cuenta en la Nube Pública (Vercel)

Este archivo describe el proceso paso a paso que seguí para crear una cuenta en **Vercel**, un servicio de despliegue en la nube, y vincularlo a mi proyecto de **PokeDex**.

## Paso 1: Crear una cuenta en Vercel

1. Abre el navegador y dirígete al sitio web oficial de [Vercel](https://vercel.com).
   
2. Haz clic en el botón **"Sign Up"** o **"Crear Cuenta"** en la página principal.

3. Selecciona un método para crear tu cuenta. Puedes usar una de las siguientes opciones:
   - **GitHub**: Si tienes una cuenta en GitHub, puedes vincularla directamente con Vercel. Esto permitirá que puedas desplegar proyectos directamente desde tus repositorios de GitHub.
   - **GitLab** o **Bitbucket**: También puedes usar estas opciones si prefieres vincular una cuenta de estos servicios.
   - **Correo electrónico**: Si prefieres no vincular ninguna cuenta externa, puedes optar por registrarte con tu dirección de correo electrónico.

4. Completa el proceso de registro o autenticación según el método elegido.

5. Una vez completado el registro, serás redirigido al panel de control de Vercel.

---

## Paso 2: Vincular GitHub a Vercel

1. Después de iniciar sesión en Vercel, haz clic en el botón **"New Project"** (Nuevo Proyecto).

2. Vercel te pedirá que vincules tu cuenta de GitHub, si no lo has hecho ya. Haz clic en **"Connect GitHub"**.

3. Se abrirá una ventana emergente de GitHub que te pedirá permisos para que Vercel acceda a tu cuenta de GitHub. Haz clic en **"Authorize Vercel"** (Autorizar Vercel).

4. Una vez autorizada la vinculación, Vercel mostrará una lista de tus repositorios en GitHub. Selecciona el repositorio del proyecto al que quieres vincular, por ejemplo, **"pokedex"**.

---

## Paso 3: Desplegar el Proyecto

1. Después de vincular el repositorio, Vercel automáticamente importará el proyecto y te llevará a una página de configuración del proyecto.

2. En esta página, puedes configurar algunas opciones como el entorno de despliegue (producción o desarrollo) y las variables de entorno (si las necesitas).

3. Haz clic en **"Deploy"** (Desplegar). Vercel comenzará a compilar y desplegar el proyecto automáticamente.

4. Una vez completado el proceso de despliegue, Vercel te proporcionará una URL única para acceder al proyecto en línea. La URL será algo como: `https://pokedex.vercel.app`.

---

## Paso 4: Verificación

1. Abre el enlace proporcionado por Vercel y verifica que la aplicación se esté ejecutando correctamente.

2. Si todo funciona bien, tu proyecto estará en producción en la nube pública de Vercel.

---

## Notas Adicionales

- **Despliegue automático**: Cada vez que realices un cambio en tu repositorio de GitHub y hagas un "push", Vercel actualizará automáticamente la versión en producción de tu aplicación.
  
- **Control de versiones**: Si deseas controlar las versiones de tu aplicación, puedes crear "Deployments" para diferentes ramas en tu repositorio y gestionarlas directamente desde Vercel.
