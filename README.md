# todo-app-react-native

La aplicación ToDoList esta diseñada para organizar y gestionar tareas diarias de manera eficiente.
Ofrece una interfaz intuitiva y fácil de usar permitiendo a los usuarios ver, editar y eliminar sus 
tareas, con funcionalidades adicionales como agregar subtareas o marcarlas como completadas.

## Características

Esta es una aplicación sencilla con las siguientes características:

- Iniciar sesión/Cerrar sesión
- Agregar nueva tarea para hacer
- Editar el estado de la tarea por hacer
- Eliminar tarea por hacer

## Tecnologías

- Expo -- es un ecosistema de herramientas que facilitan el uso de React Native. Al mismo tiempo, es una plataforma de código abierto para crear aplicaciones nativas universales para Android, iOS y la web.

- React Native -- es un marco para construir aplicaciones móviles utilizando React y JavaScript. Permite el desarrollo de aplicaciones nativas para iOS y Android a partir de un único código base en JavaScript.

- React Navigation/native -- proporciona la infraestructura básica para la navegación en aplicaciones React Native. Incluye componentes y funciones para configurar la navegación entre diferentes pantallas.

- AsyncStorage -- es una biblioteca para React Native que proporciona una forma simple y asíncrona de almacenar datos en el dispositivo del usuario. Se utiliza comúnmente para almacenar información localmente, como tokens de acceso, preferencias del usuario, etc.

- Android Studio - es el entorno de desarrollo integrado (IDE) oficial para el desarrollo de aplicaciones Android. En este caso se utilizó el 'Emulator Virtual Device'.
Puedes interactuar con el emulador utilizando el mouse y el teclado. También hay controles específicos para simular acciones táctiles, como tocar, arrastrar y deslizar.

## Funcionalidad

Para la funcionalidad de autenticación y manejo de perfiles se realizaron solicitudes a una API para obtener datos de usuarios, y gestionar el cierre de sesión eliminando tokens y datos de usuario almacenados localmente.

La implementación de Hooks para determinar el estado general de la tarea y persistir los datos en el almacenamiento local. Tambien utiliza 'AsyncStorage' para almacenar y recuperar datos, y 'React Navigation' para la navegación entre pantallas.

## Repositorio

https://github.com/lanusroots/ToDoList_TPF-Numen.git


## Configuración para el desarrollo local.

-- Install node dependencies --

npm install


-- Start the development server --

npx expo start


-- Scan the QR code shown in the terminal using the Expo Go app to open the app for local development --

## LOGIN / API

email:      "admin@mail.com"
password:   "admin123"

API:     https://api.escuelajs.co/api/v1/users