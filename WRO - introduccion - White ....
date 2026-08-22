# WRO-Future-Engineers-2026
Este repositorio reúne la documentación y los recursos de ingeniería utilizados para desarrollar un vehículo autónomo que compite en la categoría WRO Future Engineers 2026. 

CONTENIDO

-t-photos  Contiene 2 fotos del equipo (una oficial y una divertida con todos los miembros).

-v-photos  Contiene 6 fotos del vehículo (desde todos los lados, desde arriba y desde abajo).

-video     Contiene el archivo video.md con el enlace a un video donde se muestra una demostración de conducción.

-schemes   Contiene uno o varios diagramas esquemáticos en formato JPEG, PNG o PDF de los componentes electromecánicos, que ilustran todos los elementos (componentes electrónicos y motores) utilizados en el vehículo y cómo se conectan entre sí.

-src       Contiene el código del software de control para todos los componentes que fueron programados para participar en la competición.

-models    Esta carpeta contiene los archivos de los modelos que utilizan las impresoras 3D, las máquinas de corte láser y las máquinas CNC para fabricar los componentes del vehículo. Si no hay nada más que añadir, puede eliminarse.

INTRODUCCION

Nuestro código está organizado en diferentes partes, cada una encargada de controlar una función específica del vehículo. Estas partes permiten que los sensores, el sistema de dirección y el movimiento del vehículo trabajen de manera autonoma

Módulo de sensores: se encarga de obtener las distancias detectadas por los sensores ultrasónicos y haci cumplir la primera prueba.

Módulo de dirección: esta lo controla el servo , que permite orientar las ruedas mediante el sistema de dirección Ackermann.

Módulo de movimiento: controla el motor que proporciona el movimiento al vehículo mediante el sistema diferencial. Durante la navegación, el motor mantiene el vehículo en movimiento hacia adelante, mientras que la dirección se controla mediante el servo.

Módulo principal: coordina el funcionamiento general del vehículo, ejecutando continuamente la lectura de los sensores y las acciones de dirección y movimiento.

COMO SE RELACIONA EL CODIGO CON EL VEHICULO

La lógica del programa analiza continuamente las lecturas de los tres sensores. Cuando existe una diferencia entre las distancias laterales, el sistema realiza una corrección mediante el servo para acercar el vehículo hacia una posición más centrada. Al mismo tiempo, la lectura del sensor central permite determinar las condiciones de la trayectoria frontal y realizar las curvas sin dificultad .




