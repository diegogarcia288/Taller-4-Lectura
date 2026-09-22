# Taller-4-Lectura

Diego García - Eduardo Carrera

Parte 1 - Teoría
1. Escribe el símbolo UML de cada visibilidad: público, privado, protegido y de paquete.
   ( + ): Público
   ( - ): Privado
   ( # ): Protegido
   ( ~ ): De Paquete
2. ¿Qué relación indica una línea sólida con triángulo hueco? ¿Y una punteada con triángulo hueco?
   Línea Sólida con triángulo hueco: Herencia
   Línea punteada con triángulo hueco: Realización
3. En un diagrama, ¿cómo distingues una agregación de una composición?
   En un diagrama:
     Agregación se representa con una línea sólida y un rombo hueco
     Composición se representa con una línea sólida y un rombo relleno
4. ¿Con qué tipo de línea y qué punta se dibuja una dependencia?
   Se dibuja con una línea punteada y una flecha abierta
5. ¿Cómo se marca una interfaz en el diagrama? ¿Y una clase abstracta?
   La interfaz se marca:
     <<interface>>
   Clase Abstracta se marca:
     {abstract}
6. ¿Qué palabras clave de Java limitan qué clases pueden heredar y listan las permitidas?
   La palabra clave sealed para la superclase y permits para listar las subclases autorizadas
7. ¿Cómo se representa una clase genérica en UML y cómo se llama su vínculo con un tipo concreto?
    se dibuja con un recuadro punteado en su esquina superior derecha que contiene el o los parámetros de tipo (por ejemplo T).
8.  ¿Qué tipo de relación tiene un record con el tipo de sus componentes?
   tiene una relación de composición (rombo lleno)
9.  Multiplicidad: ¿en qué se traduce en Java un extremo “1” y uno “*”?
    Extremo "1": Un atributo simple de referencia al objeto
    Extremo "*": Una colección (normalmente List<Tipo>)
10. ¿Con qué símbolo se indica que una clase está anidada dentro de otra?
    Con un círculo con una cruz en su interior del lado de la clase contenedora
11. En JPMS, ¿qué directiva decide qué paquetes son visibles fuera del módulo?
    La directiva export
12. En una interfaz, ¿cuál es la visibilidad por defecto de sus métodos?
    Es public por defecto




