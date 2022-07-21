## Tipo interface
- Una clase de tipo interface es una clase en la cual se crean metodos con los que podemos dejar simplemente su signatura sin la necesidad de completar el cuerpo del metodo, estos metodos se pueden "heredar" a sus subclases mediante la palabra reservada de `implements` que al contrario de extends permite realizar varias implementaciones para una misma clase.

En este ejemplo se crea la clase Mascota de tipo interface la cual crea los siguientes metodos:

`String getCodigo();`

`void hazRuido();`

`void come(String comida);`

`void peleaCon(Animal contrincante);`

En los cuales se crean simplemente con su signatura sin implementar el cuerpo del metodo.

Ahora las clases Gato y Perro "heredan" mediante la palabra `implements` estos metodos de la clase Mascota  son "terminados" en cada una de las clases "hijas" osea son sobreescritos.

