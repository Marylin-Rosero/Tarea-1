DESCRIPCION DEL CODIGO:

Este código Java desarrolla una aplicación de escritorio utilizando JavaFX para crear una interfaz gráfica que muestra una lista de nombres de clientes junto con imágenes asociadas. Aquí está una descripción detallada de lo que hace:

1. **Configuración de la Interfaz de Usuario (UI)**:
   - Se utiliza un `AnchorPane` como contenedor principal para organizar los elementos de la interfaz.
   - Se crea un `ListView` para mostrar la lista de nombres de clientes.
   - Se crea un `TextField` para permitir al usuario ingresar información.

2. **Configuración de los Componentes UI**:
   - Se establecen las propiedades y restricciones de anclaje para posicionar los elementos en el `AnchorPane`.
   - Se define un texto de sugerencia para el `TextField`.

3. **Carga de Imágenes y Nombres de Clientes**:
   - Se definen los nombres de los clientes en un arreglo.
   - Se itera sobre los nombres de los clientes.
   - Se intenta cargar imágenes asociadas a cada cliente desde archivos `.jpg` ubicados en la carpeta `/IMAGENES/` del proyecto.
   - Si se encuentra la imagen, se crea un `ImageView` para mostrarla junto con un `Label` que muestra el nombre del cliente.
   - Tanto la imagen como el `Label` se agregan al `AnchorPane` con restricciones de anclaje.

4. **Configuración de la Escena y el Escenario**:
   - Se crea una escena con el `AnchorPane` como raíz y se establece su tamaño.
   - Se configuran propiedades del `Stage` (escenario principal), como el título y la escena creada.
   - Finalmente, se muestra el escenario.

5. **Inicio de la Aplicación**:
   - El método `main` inicia la aplicación llamando al método `launch` de la clase `Application`.

En resumen, este código desarrolla una aplicación de escritorio con JavaFX que muestra una lista de clientes con imágenes asociadas en una interfaz gráfica de usuario. Los usuarios pueden interactuar con la aplicación ingresando información en un `TextField`.

![c026efeb-f761-4c22-bee9-11054fc97eb5](https://github.com/Marylin-Rosero/Tarea-1/assets/169502533/195745fd-b0be-4477-8354-59125e5e6c1a)
