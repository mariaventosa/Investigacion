# Investigacion


• Memoria dinámica (lenguaje C) - Es memoria que se reserva en tiempo de ejecución. Su principal ventaja frente a la estática, es que su tamaño puede variar durante la ejecución del programa. (En C, el programador es encargado de liberar esta memoria cuando no la utilice más). El uso de memoria dinámica es necesario cuando a priori no conocemos el número de datos/elementos a tratar.

• Clase - plantilla para la creación de objetos de datos según un modelo predefinido. Las clases se utilizan para representar entidades o conceptos, como los sustantivos en el lenguaje. Cada clase es un modelo que define un conjunto de variables -el estado, y métodos apropiados para operar con dichos datos -el comportamiento. 

• Objeto -  unidad dentro de un programa de computadora que consta de un estado y de un comportamiento, que a su vez constan respectivamente de datos almacenados y de tareas realizables durante el tiempo de ejecución. Cada objeto creado a partir de la clase se denomina instancia de la clase.

• Instanciación -  cuando se ejecuta un programa en un computador, se dice que éste se instancia. En lenguajes que crean objetos a partir de clases, un objeto es una instancia de una clase. 
	
• Herencia - creación de una clase nueva a partir de una existente. La herencia (a la que habitualmente se denomina subclases) proviene del hecho de que la subclase (la nueva clase creada) contiene las atributos y métodos de la clase primaria. La principal ventaja de la herencia es la capacidad para definir atributos y métodos nuevos para la subclase, que luego se aplican a los atributos y métodos heredados. 

• Sobrecarga (Override) -  capacidad de un lenguaje de programación, que permite nombrar con el mismo identificador diferentes variables u operaciones, la posibilidad de tener dos o más funciones con el mismo nombre pero funcionalidad diferente.

• Ensombrecimiento (Shadowing) - que en una clase, una variable miembro y una variable local definida en un método miembro, se llamen igual.

• Ciclo de vida de variables en Java:
	
• Variables de clase (estáticas)
– Se crean cuando la clase se usa por primera vez. 
– Se inicializan por defecto si no se hace de modo explícito: 0 para números, "false" para booleano, "null" para objetos 
– Suelen existir para el resto del programa (salvo que no esté cargado)
	
• Variables de método (locales) 
– Existen desde el punto de definición hasta el final del bloque 
--  Los bloques se definen mediante llaves { }
– Las variables locales sólo existen dentro del propio método 
-- No se da acceso a ningún otro método 
	
• Variables de instancia (u objeto): 
–  Se crean cuando se crea el objeto que las contiene. 
–  Se inicializan por defecto si no se hace de modo explícito: 0 para números, "false" para booleano, "null" para objetos. 
–  Se destruyen cuando el recolector de basura de Java no encuentra referencias activas para el objeto. 
	
	
Referencias:

Programación básica - Tecnológico de Monterrey http://campus.cva.itesm.mx/nazira/Tc1001/Programación%20básica%20C++.pdf

Guia de programación - Microsoft
https://msdn.microsoft.com/es-MX/library/x9afc042.aspx

Conceptos básicos de la programación orientada a objetos - SCEHU
http://www.sc.ehu.es/sbweb/fisica/cursoJava/fundamentos/clases1/clases.htm
