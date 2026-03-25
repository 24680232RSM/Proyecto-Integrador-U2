# Proyecto-Integrador-U2
# Animación 2D en Blender: Ciclo de Caminata (Dog Walk Cycle)

Este proyecto documenta el proceso de creación de una animación tradicional 2D utilizando la herramienta **Grease Pencil** de Blender. El objetivo es recrear un ciclo de caminata fluido basado en una referencia de 8 posiciones clave.

##  Proceso de Desarrollo

### 1. Configuración Inicial y Materiales
* **Preparación de la escena:** Creación de un nuevo objeto de *Grease Pencil* en blanco para mantener un control total sobre el proyecto desde el inicio.
* **Gestión de materiales:** Se configuraron 5 materiales específicos:
    * `Trazo`: Contorno café para definir la silueta.
    * `Rellenos`: 4 variantes de color para el cuerpo de la mascota, nariz y lengua.

### 2. Preparación de la Referencia
* **Importación:** Uso de una imagen de referencia con un ciclo de caminata de un perro (8 posiciones distintas).
* **Planificación del tiempo (Timing):** * Línea de tiempo de **24 fotogramas**.
    * Cada pose se dibuja cada **3 fotogramas**, logrando exactamente 1 segundo de animación fluida.

### 3. Proceso de Dibujo (Trazo y Relleno)
* **Estructura de Capas:** Organización en dos niveles principales: `Trazo` y `Relleno`.
* **Herramientas utilizadas:** Uso intensivo de *Arco*, *Curva* y *Línea Poligonal* para calcar la referencia con precisión.
* **Técnica de flujo:** Se aplicó un flujo de trabajo donde el trazo superior permite que el relleno sea más flexible y rápido de aplicar sin perder calidad en los bordes.

### 4. Organización de la Animación
* **Alineación:** Una vez finalizados los 8 dibujos por separado, se utilizó el **Modo Edición** para superponerlos en el centro del lienzo.
* **Fluidez:** Se tomó como punto de anclaje la cabeza y el lomo de la mascota para asegurar que el movimiento no tenga saltos bruscos y se sienta natural al reproducirse.


##  Resultado Final
El resultado es un **ciclo de caminata fluido** que demuestra el gran potencial de Blender como herramienta para la animación 2D tradicional, combinando la precisión digital con técnicas clásicas de dibujo.


*Proyecto inspirado en los flujos de trabajo de animación 2D en Blender.*

<img width="1919" height="1077" alt="image" src="https://github.com/user-attachments/assets/442dfaad-e611-47a8-99ae-740f3fa2d108" />

<img width="1919" height="1075" alt="image" src="https://github.com/user-attachments/assets/2c3c5d5e-f68e-4753-9aba-758636b05b6a" />

