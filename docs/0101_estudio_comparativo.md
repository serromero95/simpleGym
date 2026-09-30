ACTIVIDAD 1

1. Tecnologías elegidas:
    - Android Nativo, que es el desarrollo específico para dispositivos Android.
    - React Native, un framework multiplataforma que permite desarrollar aplicaciones para Android e iOS con JavaScript o TypeScript y React, compartiendo gran parte del código entre ambas plataformas.
    - PWA (Progressive Web App). Una web que el navegador permite instalar como app. Sin tienda, sin proceso de revisión y sin intermediarios. La app se actualiza cada vez que el usuario la abre, porque está conectada a un servidor.

2. Tabla comparativa de las tecnologías elegidas:

| Aspecto                                | Android Nativo                                                 | React Native                                                                                                                         | PWA                                                       |
|----------------------------------------|----------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------|
| Lenguajes que utiliza                  | Kotlin o Java                                                  | JavaScript o TypeScript                                                                                                              | HTML, CSS y JS. También React.                            
| Herramientas que necesita              | Android Studio, Android SDK y un emulador o dispositivo físico | Node.js, un editor como VS Code y herramientas tipo Expo. Para compilación local: Android Studio en Android y MacOS con Xcode en iOS | Editor de código, navegador y herramientas de desarrollo. |
| Plataformas que soporta                | Dispositivo Android                                            | Android e iOS                                                                                                                        | Móviles y ordenadores con navegador compatible.           
| Rendimiento                            | Alto rendimiento.                                              | Rendimiento bajo.                                                                                                                    | Rendimiento muy bajo.                                     |
| Acceso al hardware                     | Acceso total.                                                  | Acceso alto. A veces mediante plugin.                                                                                                | Acceso limitado.                                          |
| Coste de desarrollo y mantenimiento    | Alto.                                                          | Bajo                                                                                                                                 | Muy bajo

3. Casos de uso y elección justificada:

- Android Nativo: Aplicación de cámara para Android. Eligiría esta opción porque nos permite utilizar directamente las funciones de cámara que ofrece Android y controlar su comportamiento. Además, como es una app específica para Android, compartir código con iOS no es una prioridad.
- React Native. Aplicación de seguimiento de entrenamientos. Si un gimnasio quiere ofrecer esta app a sus clientes para que creen rutinas y registren sus pesos y repeticiones, necesitarán una app que sirva tanto para Android como para iOS. Esta opción reduciría el esfuerzo de crear y mantener dos aplicaciones independientes y las funciones previstas no requieren un procesamiento muy exigente. Como el gimnasio pretende fidelizar al usuario, frente a PWA, React Native permitirá integrar recordatorios locales, mayor acceso a funciones del móvil y construir una interfaz más eficiente y amigable.
- PWA. Aplicación de registro de entrada y salida. Permite acceder mediante enlace, sin exigir la instalación desde una tienda, por lo que podrían hacerlo también desde el ordenador. Las funciones no son exigentes para el hardware y un mayor gasto no estaría justificado para una app tan sencilla.