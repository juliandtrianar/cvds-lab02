# LABORATORIO 2 - PATTERNS


## LA HERRAMIENTA MAVEN

### Cuál es su mayor [utilidad](https://maven.apache.org/what-is-maven.html)

    Maven sirve para facilitar la gestión de proyectos a múltiples a múltiples desarrolladores, aunque tiene múltiples utilidades y potencialidades tales como:

        - Eliminación de código innecesario.
        - Facilidad para entender un único Modelo de Objeto de Proyecto (POM).
        - Proveer información relevante.
        - Utilizar o no determinados plugins.
        - Boostear las mejores prácticas de desarrollo.

    Adicionalmente, posee otros atributos que lo [caracterizan](https://maven.apache.org/maven-features.html):

        * Instantaneidad en sus funciones.
        * Consistencia del equipo.
        * Actualización automática de la dependencia.
        * Extensibilidad del plugin.
        * Proyecto basado en modelos.

    entre otras.

### Fases de maven 

    A continuación la lista completa de [fases](https://maven.apache.org/guides/introduction/introduction-to-the-lifecycle.html) del ciclo de vida 'default' en MAVEN:

        1. ´Validate´ Validar la correctitud y completitud de la información relacionada al proyecto.
        2. ´Compile´ Compilación del coódigo fuente.
        3. ´Test´ Ensayo del funcionamiento adecuado.
        4. ´Package´ Compilar el código en formato **.jar**.
        5. ´Verify´ Control de calidad constante.
        6. ´Install´ Uso local de paquetes.
        7. ´Deploy´ Compartir el avance local, con el repositorio.

### Ciclo de vida de la construcción 

    El ciclo de vida de construcción puede variar en sus fases. Adicionalmente a la ´default´, podemos listar las siguientes:

        * ´Clean´ Eliminar archivos anteriormente creados. Realizar proyectos de elementales antes y después de la limpieza.
        * ´site´ Generar la documentación del sitio web del proyecto. Procesos anteriores y posteriores a la ejecución del sitio. Generar documentación.

### Para qué sirven los plugins 

    Sirven para [complementar funcionalidades](https://maven.apache.org/plugins/index.html) de Maven, como por ejemplo:

        * Generar EAR.
        * Construir EJB, RAR, JAR y AR.
        * Construir cliente JavaEE, Uber-JAR, fuente-JAR, Java Run Time Imagen y archivos Java JMod.
        * Generar lista de cambios SCM, informe rastreador de emision, informe de checkstyle, DOAP de POM, Javadoc de JDK, referencia cruzada en la fuente, informe Linkcheck, informe PMD, informe de proyecto estándar,                 informe basado en resultados de prueba de unidad.
        * Generar archivos Eclipse y archivo de construcción de hormigas.
        * Plugins para ayuda de tareas e interacción del legado MAVEN.

    además de las herramientas Maven por defecto, MojoHaus y Misc, etc.
    
### Qué es y para qué sirve el repositorio central de maven

    Es una biblioteca de artefactos almacenados, a manera de depósito, como parte de la filosofía Maven. Estos artefactos, pueden ser ubicados mediante coordenadas. El repositorio Maven permite [añadir o hacer uso de            plugins previamente implementados.](https://maven.apache.org/repository/index.html)

## EJERCICIO DE LAS FIGURAS

    

### CREAR UN PROYECTO CON MAVEN    

    
        
 ![mvn](http://url/a.png)                                                                                                                                                                                                                                                                                        
                            
                                                                                                                                                                                            *Autores* 
                                                                                                                                                                                                          
                                                                                                                                                                                                Daniel Alejandro Acero 
                                                                                                                                                                                                -----------------------
                                                                                                                                                                                                Julian Triana
                                                                                                                                                                                                -----------------------
