ACTIVIDAD 2

1. Captura de los 3 emuladores ejecutando la app:

Teléfono actual:

![Teléfono actual ejecutando la app](res/avd_modern_mobile_running.png)

Teléfono pequeño:

![Teléfono pequeño ejecutando la app](res/avd_small_phone_running_rotated.png)

Tablet:

![Tablet ejecutando la app](res/avd_tablet_running.png)

2. Captura de la ficha de configuración de cada emulador:

Teléfono actual: 

![Configuración teléfono actual](res/avd_modern_phone_configuration_sheet.png)

Teléfono pequeño:

![Configuración teléfono pequeño](res/avd_small_phone_configuration_sheet.png)

Tablet:

![Configuración tablet](res/avd_tablet_configuration_sheet.png)

3. Comentario breve sobre las diferencias observadas.

Las diferencias más visibles son a nivel de espacio en la pantalla. Mientras en el emulador pequeño el contenido dispone de menos espacio y los elementos ocupan una mayor proporción en la pantalla, en el mediano hay más espacio para distribuirlos. Y más todavía en la tablet.

Durante las pruebas, la aplicación no se ejecutaba en el emulador pequeño y antiguo porque tenía configurado un `minSdk` de 34, por lo que tuve que buscar cómo solucionarlo. Al bajarlo a 24, que era el mínimo, apareció un error con los iconos adaptativos, que requerían API 26. Me sorprendió que fallara incluso usando un emulador con API 26, pero comprendí que establecer un mínimo de 24 obligaba a que los recursos fuesen también compatibles igualmente con versiones 24 y 25. Finalmente, al establecer `minSdk = 26`, la aplicación compiló y se instaló correctamente.
