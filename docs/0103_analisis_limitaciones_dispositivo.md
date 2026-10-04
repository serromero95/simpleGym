ACTIVIDAD 3: ANÁLISIS DE LAS LIMITACIONES DE UN DISPOSITIVO

Dispositivo: Samsung Galaxy A56 5G

- **Especificaciones**:
  - Procesador: Samsung Exynos 1580.
  - RAM: 8 GB.
  - Almacenamiento libre: 10 GB de un total de 128 GB.
  - Pantalla: Super AMOLED de 6,7 pulgadas, hasta 120 Hz.
    - Resolución: 1080 x 2340 píxeles.
    - Densidad: aproximadamente 385 ppp. Se calcula dividiendo la diagonal en píxeles entre la diagonal en pulgadas.
  - Versión de Android: 16.
  - Nivel de API: 36.
- **Sensores disponibles**:
  - Acelerómetro.
  - Luminosidad.
  - Proximidad.
  - Magnetómetro.
  - Giroscopio.
- **Estado de la batería y consumo por aplicación:**
  - Capacidad: 5.000 mAh.
  - Carga en el momento de consulta: 87%.
  - Estado: no está cargando.
  - Salud indicada por el sistema: 100%.
  - Ciclos de carga: 288.
  - Consumo por aplicación (consulta realizada el 2 de octubre de 2026 a las 12:09, consumo acumulado mostrado 18%):
    - Firefox: 3,7%.
    - Youtube: 3,3%.
    - Servicios de Google Play 1,6%.
    - WhatsApp: 0,5%.
    - Spotify: 0,3%.

CONCLUSIONES DE DISEÑO:

1. Reducir el espacio ocupado por las fotos. El dispositivo tiene solo 10GB libres, por lo que en SimpleGym se guardarán las fotografías opcionales de seguimiento con una resolución reducida y comprimida. También permitiré eliminarlas sin afectar al histórico de pesos y repeticiones.
2. Registro manual de repeticiones. El Samsung Galaxy A56 cuenta con acelerómetro y giroscopio entre sus sensores, pero estos detectan el movimiento del teléfono, que puede permanecer apoyado durante el entrenamiento. Por ello, SimpleGym optará por introducir peso y repeticiones manualmente, sin obligar a llevar el móvil encima al realizar cada ejercicio. Esta decisión simplifica el desarrollo y evita la lectura y el procesamiento continuo de los sensores, lo cual puede beneficiar también a nivel de batería.
3. Interfaz adecuada a la pantalla. La pantalla tiene 6,7 pulgadas, una resoluciónd de 1080x2340 y una densidad aproximada de 385 ppp. La aplicación definirá el tamaño de los botones y otros elementos en dp y los textos en sp, para mentener un tamaño adecuado en pantallas con distintas densidades y respetar el tamaño de letra configurado por el usuario. Así, facilitaremos la lectura de los ejercicios y la introducción de peso y repeticiones.