OBJETIVO


El objetivo principal de este proyecto es desarrollar un programa en Python que permita mejorar la percepción visual de personas con daltonismo al modificar imágenes de manera automática y personalizada según el tipo de daltonismo que presente el usuario. El propósito es crear una herramienta accesible y efectiva que facilite la visualización de imágenes para aquellos con dificultades en la discriminación de ciertos colores.

ANÁLISIS


El daltonismo es un trastorno visual que afecta la capacidad de una persona para percibir ciertos colores. Las personas con daltonismo experimentan dificultades en la diferenciación de colores específicos, lo que puede afectar significativamente su capacidad para percibir detalles en imágenes o gráficos. Este proyecto aborda la necesidad de mejorar la percepción visual de estas personas al interactuar con imágenes digitales.
El problema central radica en cómo diseñar un programa que, mediante el procesamiento de imágenes, preguntar el tipo de daltonismo en un usuario y aplicar ajustes personalizados en los canales de color de la imagen para mejorar su visibilidad. Este enfoque se vuelve esencial para garantizar que la adaptación de las imágenes sea específica y efectiva para cada usuario, considerando las variaciones en los tipos de daltonismo.
Además, se debe abordar la interfaz de usuario de manera cuidadosa para que sea intuitiva y accesible para personas con daltonismo, teniendo en cuenta las posibles limitaciones visuales que puedan tener. 

DISEÑO


La lógica de solución se basa en un enfoque multifacético que involucra la identificación del tipo de daltonismo, la aplicación de ajustes personalizados en los canales de color y la creación de una interfaz de usuario intuitiva. A continuación, se explica la lógica de solución en detalle:

El programa utiliza las siguientes bibliotecas:

tkinter:
Se emplea para desarrollar la interfaz de usuario, creando ventanas, etiquetas y botones.
filedialog:
Se utiliza para abrir cuadros de diálogo que permiten al usuario seleccionar archivos.
PIL (Python Imaging Library) - Image y ImageTk:
Se usa para abrir, manipular y mostrar imágenes en la interfaz de usuario.
matplotlib, numpy, y cv2:
Estas bibliotecas se emplean para el procesamiento de imágenes, facilitando la manipulación y transformación de los canales de color para adaptarse a diferentes tipos de daltonismo.

La combinación de estas bibliotecas permite una solución completa y efectiva para mejorar la visualización de imágenes por parte de personas con daltonismo.


Lógica de Solución:

Selección de Imagen:
Se implementa un botón "Cargar Imagen" que abre un cuadro de diálogo para que el usuario elija una imagen desde su sistema de archivos. La imagen seleccionada se carga en la interfaz.

Selección de Tipo de Daltonismo:
Se proporcionan botones para diferentes tipos de daltonismo (Deuteranopia, Deuteranomalía, Protanopia, etc.). Al seleccionar un tipo, se almacena la información correspondiente en una variable global.

Lógica de Procesamiento de Imagen:
Cuando se presiona el botón "Mostrar Imagen", se crea una nueva ventana que muestra la imagen original y la imagen procesada según el tipo de daltonismo seleccionado.
La imagen se convierte a un arreglo NumPy para el procesamiento.
Se aplican ajustes específicos en los canales de color de la imagen, adaptándola al tipo de daltonismo seleccionado.
La imagen procesada se muestra en la interfaz.

Interfaz de Usuario (Tkinter):
Se utiliza la biblioteca Tkinter para construir la interfaz de usuario. Se han incorporado elementos gráficos como etiquetas, botones y cuadros de diálogo.
La interfaz es intuitiva y accesible, con colores cuidadosamente seleccionados para personas con daltonismo. Se han agregado etiquetas informativas para guiar al usuario.
El botón "Mostrar Imagen" se habilita solo después de cargar una imagen y seleccionar un tipo de daltonismo.

Consideraciones para Personas con Daltonismo:
Se han tenido en cuenta las necesidades de personas con daltonismo al seleccionar colores y diseñar la interfaz para garantizar una experiencia amigable y legible.

Interfaz de Usuario:
La interfaz consta de botones para cargar una imagen, seleccionar el tipo de daltonismo y mostrar la imagen procesada. Se ha diseñado con la premisa de hacer que la experiencia de interactuar con el programa sea inclusiva y fácil de usar para personas con daltonismo.

La lógica de solución busca abordar de manera integral el problema del daltonismo, proporcionando una herramienta efectiva y accesible que mejore la experiencia visual de las personas con este trastorno al interactuar con imágenes digitales.
Esta implementación integral del programa aborda tanto la lógica de procesamiento de imágenes como la interfaz de usuario, proporcionando una solución completa y efectiva para mejorar la percepción visual de personas con daltonismo al interactuar con imágenes digitales.

