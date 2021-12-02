# Taller-Patrones
Patrones Estructurales
1.	Indique como podría servir cada uno de los patrones dentro de este sistema (BUILDER Y DECORATOR)

BUILDER
Es muy común encontrarnos con situaciones en las cuales tenemos que crear objetos compuestos de forma manual y repetidas veces, lo que nos lleva a tener que establecer cada propiedad del objeto y si ésta además tiene objetos compuestos dentro, tenemos que crearlos primero para después ser asignados al objeto que estamos creando. Esto desde luego que se hace una tarea tediosa y cansada, sobre todo cuando tenemos que crear de manera frecuente los objetos. Utilizaremos Builder porque tendremos dos modelos de vehiculos uno para cada casa automotriz por lo que este patron nos permite crear objetos complejos(Vehiculos de cada modelo) a través de uno más simple. Facilitando al usuario la creacion de cualquier tipo de vehiculo.
Es muy útil, ya que los dos Vehiculos se construyen de manera similar, por lo tanto sus pasos de creación serían iguales, y el builder debería de encargarse de construirlo y pedir datos en cada paso, y de esa manera nos evitamos de crear una clase con todos los atributos.

DECORATOR
El patron decorator nos evita la heredacion y por lo tanto la creacion de clases innecesarias ya que si el usuario requiere de un vehiculo con alguna variacion en sus atributos lo podra hacer sin la necesidad de crear una clase nueva completamente. Por ejemplo podria crear un modelo de vehiculo especifico (Audi) y que tenga un sistema de sensor para retor pero tambien podria crear otro vehiculo modelo Audi que no tenga el sensor pero si tenga una radio con pantalla tactil.


