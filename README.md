i. y ii. Identificación de las Clases, lo que presentan, analisis de sus métodos y atributos, y plantamiento de la relacion que estas poseen:
  Clase Calculadora:
    En esta clase encontramos las funcionalidades básicas de una calculadora. Esta cuenta con 2 varibles de tipo entera inicializadas. Presenta 2 constructuros (uno con párametros y otro sin párametros), el              constructor sin párametros se encarga de inicializar las variables a un valor inicial mientras que el contructor con parámetros se le agrega un valor proporcionado.
    Cuanta con las operaciones básicas de una calculadora las cuales son: sumar y multiplicar.
    Ademas cuenta con 2 metodos para cambiarle los valores a las variables enteras, que en este caso son los número que realizan las diferentes operaciones.

  Clase CarroCompra:
    Esta clase modela un sistema de carrito de compras básico. Para ello utiliza un almacenamiento en memoria que es un array bidimensional (una matriz) donde se aloja la informacion de 5 productos, donde en una        fila se guarda la cantidad predefinida como 1 y en la otra el precio predefinido en 1000.
    Posee dos métodos los cuales calcula el costo de un artículo delegando la operación a la clase Calculadora y otro que imprime el resultado por pantalla.

  Analisando ambas clases, pude llegar a la conclusión de que se relacionan mediante una dependencia ya que la clase CarroCompra necesita o depende de la clase Calculadora para realizar una parte de su                funcionabilidad, en este caso para calcular subtotal de compra.
  Es decir ambas clase crean un módelo funcional de mercado de negocios, ya que mientras en la clase CarritoCompra almacena los productos a comprar mediante un método, en este se intancia la clase Calculadora 
  para utilizar un método presente en ella y nuevamente posterior al calculo retornar ese valor en la clase CarritoCompra y mostrar el subtotal en pantalla con el método mostrarTotal().

iii. Creacion de Diagrama de clases UML con Visual Paradimg
  Ver la imagen adjunta en el branch
