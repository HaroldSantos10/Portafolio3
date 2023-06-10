<template >

    <section class="page-section" >

        <div class="container px-4 px-lg-5">
            <div class="row gx-4 gx-lg-5 justify-content-center ">
                <div class="col-lg-8 col-xl-6 text-center">
                            <h2 class="mt-0">Sumario</h2>
                            <hr class="divider" />
                            <p class="text-muted mb-1">
                               En esta sección puede encontrarse un resumen de cada uno de los contenidos estudiados hasta el momento.
                            </p>
                        </div>

                <div class="container my-5">
                    <nav>
                    <div class="nav nav-tabs" id="nav-tab" role="tablist">

                        <button  class="nav-link active text-danger" id="nav-cont1-tab" data-bs-toggle="tab" 
                        data-bs-target="#nav-cont1" type="button" role="tab" aria-controls="nav-cont1" 
                        aria-selected="true">Contenido 1</button>

                        <button class="nav-link text-danger" id="nav-cont2-tab" data-bs-toggle="tab" 
                        data-bs-target="#nav-cont2" type="button" role="tab" aria-controls="nav-cont2" 
                        aria-selected="false">Contenido 2</button>

                        <button class="nav-link text-danger" id="nav-cont3-tab" data-bs-toggle="tab" 
                        data-bs-target="#nav-cont3" type="button" role="tab" aria-controls="nav-cont3" 
                        aria-selected="false">Contenido 3</button>

                        <button class="nav-link text-danger" id="nav-cont4-tab" data-bs-toggle="tab" 
                        data-bs-target="#nav-cont4" type="button" role="tab" aria-controls="nav-cont4" 
                        aria-selected="false">Contenido 4</button>

                        <button class="nav-link text-danger" id="nav-cont5-tab" data-bs-toggle="tab" 
                        data-bs-target="#nav-cont5" type="button" role="tab" aria-controls="nav-cont5" 
                        aria-selected="false">Contenido 5</button>

                    </div>
                    </nav>

                    <div class="tab-content" id="nav-tabContent">

                    <div class="tab-pane fade show active p-3" id="nav-cont1" role="tabpanel" aria-labelledby="nav-cont1-tab">
                        <h2>Contenido #1 JavaScript</h2>
                        <p>
                            JavaScript es un lenguaje de programación que los desarrolladores web utilizan para hacer sus páginas web interactivas. 
                            Permite mostrar animaciones y proporcionar una mejor experiencia de uso al usuario, también puede ser utilizado en la 
                            parte del servidor.   
                        <br>
                        <br>
                            Al principio surgió para hacer que las aplicaciones web fueran más dinámicas, los desarrolladores hicieron evolucionar el 
                            lenguaje permitiendo que fuera usado fuera de los navegadores.   
                        <br>
                        <br>
                            Funcionamiento JavaScript: 

                            <ul>
                                <li>Es interpretado.</li>
                                <li>Puede ser utilizado tanto en el lado del cliente como en el lado del servidor. </li>
                            </ul>

                            <img src="https://i.imgur.com/xoPQUJL.jpeg" class="img-fluid" alt="usos de JavaScript">

                        </p>

                            <dl><dt>JavaScript del lado del cliente</dt><dd> 
                                En este caso JavaScript funciona en el navegador, cada navegador incluye un motor de JavaScript con el cual se 
                                ejecutan las diferentes funciones asociadas a diferentes eventos. Estas funciones realizan cambios en HTML y CSS.
                            </dd></dl>
                            <dl><dt>JavaScript del lado del servidor</dt><dd>
                                En este caso se hace referencia a la codificación en la lógica del servidor. Es decir, en el backend.

                                El motor de JavaScript se encuentra directamente en el servidor, por lo tanto, una función de JavaScript es capaz de acceder a 
                                la información contenida en una base de datos, realizar diferentes operaciones en ella y responder a diferentes eventos
                                a partir del sistema operativo del servidor.

                            </dd></dl>
                        <br>
                        <h4> Bibliotecas y Frameworks en JavaScript</h4>
                        <p>
                            Las bibliotecas son fragmentos de códigos escritos previamente para la realización de funciones estándar en JavaScript. 
                            Mientras que los Frameworks son Marcos de trabajo que contienen una gran colección de fragmentos de códigos que permiten 
                            realizar diferentes funciones y que se pueden reutilizar.
                            Javascript contiene diferentes tipos de datos. Entre los cuales se pueden mencionar Boolean, Undefined, Number, String, Date, 
                            Object, Array.
                        </p>



                    </div>

                    <div class="tab-pane fade p-3" id="nav-cont2" role="tabpanel" aria-labelledby="nav-cont2-tab">
                        <h2>Contenido #2 Bootstrap-VueJS</h2>
                      
                        <p>
                            Bootstrap es un marco de desarrollo web, orientado a la creación de interfaces web, El enfoque del marco, esencialmente
                             consiste en permitir a los desarrolladores crear diseños y ayudar a desarrollar una apariencia consistente, proporcionando 
                             estilos para botones, formularios y otros componentes de la interfaz de usuario.  
                        <br>
                        <br>

                            Principalmente es una herramienta útil en: 

                            <ul>
                                <li>Diseño.</li>
                                <li>Contenido.</li>
                                <li>Componentes.</li>
                                <li>Soporte Móvil</li>
                                <li>Clases</li>
                                <li>Compatibilidad (Soporta la mayoría de los navegadores modernos).</li>
                                <li>Cuadricula.</li>
                                <li>Texto Ajustable</li>
                                <li>Controles de formulario</li>
                                <li>Personalización.</li>
                            </ul>

                            <img src="https://i.imgur.com/8LlQano.jpeg" class="img-fluid" alt="imagen bootstrap">

                        </p>

                            <dl><dt>¿Qué es VueJS?</dt><dd> 
                                Es un marco de trabajo pensado para el desarrollo de páginas web con él se pueden crear todas las vistas de una página web. 
                                Se pueden hacer dinámicas, pueden conectarse a un servidor para tener datos dinámicos de una base de datos. Y está diseñado 
                                desde cero para ser adaptable de forma incremental.                         
                            </dd></dl>
                            <dl><dt>Características de VueJS.</dt><dd>
                                <ul>
                                    <li>Progresividad.</li>
                                    <li>Modularidad.</li>
                                    <li>Reactividad.</li>
                                    <li>Basado en Componentes web.</li>
                                    <li>Virtual DOM.</li>
                                    <li>Eventos y Transiciones.</li>
                                    <li>Mixins.</li>
                                    <li>Lifecicle.</li>
                                    <li>Aplicaciones SPA</li>

                                </ul>
                            </dd></dl>

                            <img src="https://i.imgur.com/HYRWsE5.png" class="img-fluid" alt="imagen bootstrap">

                        <br>
                        <br>
                        <h4> Vue-CLI</h4>
                        <p>
                            Vue cuenta con su propia interfaz de línea de comandos que permite inicializar una aplicación Vue y otras configuraciones que se 
                            desean dentro de un proyecto con Vue.
                            <br>
                            Existen diferentes formas de inicializar una aplicación con Vue usando Vue CLI.
                            <br>
                            <ul>
                                <li>vue init webpack</li>
                                <li>vue init webpack-simple</li>
                                <li>vue init browserify</li>
                                <li>vue init browserify-simple</li>
                                <li>Virtual DOM.</li>
                                <li>vue init simple</li>

                            </ul>
                            La diferencia entre estas diferentes formas de inicializar una aplicación podrá ser notada en la estructura del proyecto creado.
                        </p>

                    </div>

                    <div class="tab-pane fade p-3" id="nav-cont3" role="tabpanel" aria-labelledby="nav-cont3-tab">
                        <h2>Contenido #3 Rendering Declarativo - Directivas</h2>
                        
                        <p>
                            El rendering declarativo es una opción que propone VueJS para interactuar con el DOM, que se basa en:
                            <br>
                            <br>
                            Vista: HTML.
                            <br>
                            Estado: Datos JS.
                            <br>
                            Usuario: interactúa e introduce cambios en la vista.

                        <br>
                        <br>
                            <u>Funcionamiento</u>
                            <br>
                            Render: es la función que le permite al Estado indicarle a la vista como y cuando 
                            copilar y cuál será el resultado que debe de mostrar.  
                        <br>
                        <br>
                            Comandos proyecto VueJS: 

                            <ul>
                                <li>Crear proyecto -> vue create vuejs-app</li>
                                <li>Ejecución proyecto -> npm run serve </li>
                            </ul>



                        </p>

                            <dl><dt>Directivas</dt><dd> 
                                Son atributos especiales que se colocan en las etiquetas HTML y están prefijados por v-, como por ejemplo, v-for, v-bind o v-on, 
                                entre muchas otras. Estas directivas permiten realizar acciones dinámicas potentes (bucles, condicionales, etc.…).

                            </dd></dl>
                            
                            <img src="https://i.imgur.com/XjHS8bN.png" class="img-fluid" alt="partes de una directiva">

                        <p>
                            <br>
                            Existen diferentes tipos de directivas en VueJS divididas en diferentes grupos:
                            <br>
                            <br>

                            <ul>
                                <li><b>Directivas básicas:</b> Permite realizar tareas simples. Ejemplos v-pre, v-once, v-model </li>
                                <li><b>Directivas condicionales:</b> Permiten realizar acciones según condiciones. Ejemplos v-show, v-if, v-else</li>
                                <li><b>Directivas de bucles:</b> Permiten realizar operaciones varias veces. Ejemplos v-for</li>
                                <li><b>Directivas avanzadas:</b> Permiten realizar tareas más específicas. Ejemplos v-bind, v-on, v-slot</li>
                            </ul>

                            <br>
                            

                            <u>Representación de lista</u>

                            <br>
                            Se puede representar una lista usando la directiva v-for. La sintaxis requiere que especifique la matriz de origen para iterar, 
                            y un alias que se usará para hacer referencia a cada elemento en la iteración.

                            <br>
                            <br>

                            <img src="https://i.imgur.com/BFOUgZ9.png" class="img-fluid" alt="partes de una directiva for">

                        </p>

                        <br>
                        <h5> Directivas Personalizadas</h5>
                        <p>
                            Además de las directivas por defecto del incluidas en el núcleo de VueJS, también se permite registrar directivas personalizadas 
                            que proporcionan mecanismos para asignar cambios de datos a un comportamiento arbitrario de DOM.

                            <br>
                            <br>

                            <u>Sintaxis</u>

                            <br>
                            <ul>
                                <li>Vue.directive(id, definition);</li>
                            </ul>
                                
                            <u>Parametros</u>

                            <br>

                                <ul>
                                    <li>Id: cadena -> ID de la directiva que se utilizara</li>
                                    <li>Definition: objeto -> un objeto de definición</li>
                                </ul>
  
                    
                        </p>

                            <dl><dt>Propiedades de las directivas personalizadas</dt><dd> 
                                <ul>
                                    <li><b>el:</b> el elemento al que está dirigida la directiva.</li>
                                    <li><b>vm:</b> el contexto ViewModel que posee esta directiva.</li>
                                    <li><b>expresión:</b> la expresión del enlace, excluyendo argumentos y filtros.</li>
                                    <li><b>arg:</b> el argumento, si está presente.</li>
                                    <li><b>nombre:</b> el nombre de la directiva, sin el prefijo.</li>
                                    <li><b>modificadores:</b> un objeto que contiene modificadores, si los hay.</li>
                                    <li><b>descriptor:</b> un objeto que contiene el resultado del análisis de toda la directiva.</li>
                                    <li><b>params:</b> un objeto que contiene atributos param</li>
                                </ul>
                            </dd></dl>

                        <br>
                            <b>Infografia Direcitivas VUE</b>
                        <br>

                        <img src="https://i.imgur.com/Vo2LEkn.png" class="img-fluid" alt="Infografia directivas">

                    </div>

                    <div class="tab-pane fade p-3" id="nav-cont4" role="tabpanel" aria-labelledby="nav-cont4-tab">
                        <h2>Contenido #4 Eventos y Clases</h2>
                        
                        <h5>¿Qué son los eventos?</h5>
                        <p>
                            
                            <br>
                            Es una acción del usuario ante la cual puede realizarse algún proceso (por ejemplo, el cambio del valor de un formulario, 
                            o la pulsación de un enlace). 
                        <br>
                        <br>
                            <b>Manejadores de evento</b><br>

                            La interacción con el usuario se consigue mediante la captura de eventos, estos se capturan mediante manejadores de eventos. 
                            El proceso por realizar se programa mediante funciones JavaScript que reciben este nombre.
                            La directiva v-on se puede utilizar para escuchar eventos del DOM. Cuando la lógica es muy compleja v-on también es capaz de 
                            aceptar el nombre del método al que quiere llamar.

                        <br>
                        <img src="https://i.imgur.com/sn5SiQP.png" class="img-fluid" alt="partes de una directiva">

                        <br>
                        <br>

                            <b>Modificadores de eventos</b><br>
                            La directiva v-on funciona como un listener y para manejar eventos del DOM a través de estos se proporcionan modificadores, 
                            como por ejemplo: event.preventDefault() o event.stopPropagation(). Se usa el sufijo (.) para invocar los modificadores, 
                            algunos ejemplos: .stop .prevent .capture .self .once

                        <br>
                        <br>

                            <b>Modificadores de teclas</b><br>
                            Para facilitar la tarea de verificar códigos de teclas comunes, vue proporciona alias para las claves más utilizadas. 
                            Ejemplos: (.enter .tab .delete .esc .up .down .left .right )

                        <br>
                        <br>

                            <b>Clases y estilos</b><br>
                            Usando la directive v-binding se pueden aplicar clases y estilos reactivos a la etiquetas dentro del DOM, se deben especificar 
                            como texto entre comillas dobles que dentro llevan comillas simple sobre la clase que se quiere asignar. 
                            <br>
                            Usando :style se puede cambiar el estilo de algún elemento HTML en tiempo de ejecución. Para esto se utiliza el 
                            nombre de la propiedad CSS seguido del valor que se quiere que tome entre comillas simples y todo dentro de {}.

                        </p>

                    
                    </div>

                    <div class="tab-pane fade p-3" id="nav-cont5" role="tabpanel" aria-labelledby="nav-cont5-tab">
                        <h2>Contenido #5 Componentes en VueJS</h2>
                        <h5>Componentes</h5>
                        <p>
                             
                            Es la forma de reutilizar una instancia de Vue tantas veces como sea necesario. Usando componentes 
                            se pueden crear elementos html propios, con sus propiedades y métodos particulares que pueden reutilizar 
                            en toda la aplicación.

                        <br>
                        <br>
                            Sintaxis para la creación de componentes: Vue.component(“name”, { options })<br>

                            <ul>
                                <li>Name -> nombre del componente</li>
                                <li>{ options } -> todas las opciones que se pueden enviar a una instancia de Vue</li>
                            </ul>

                            -	No se especifica {el:’#app’} <br>
                            -	Data es una función que retorna un objeto.

                        <br>
                        <br>

                        <img src="https://i.imgur.com/GiFoQDz.png" class="img-fluid" alt="partes de una directiva for">

                        <br>
                        <br>

                            <b>Registro Global de componentes </b><br>
                            El registro global se realiza al llamar al método component de Vue. Que un componente se registre de forma 
                            global significa que estará disponible en cualquier componente de Vue. <br><br>

                            <b>Registro Local de componentes </b><br>
                            Acumular componentes globales los cuales se utilizan en pocas o solamente en una vista es una mala práctica, 
                            por ello Vue aporta la flexibilidad de agregar los componentes que se utilizarán en un componente específico.

                        <br>
                        <br>

                        </p>

                        <h5>Comunicación entre componentes: propiedades y eventos</h5>

                        <p>

                            <b>Pasando datos mediante métodos(propiedades)</b><br>
                            En Vue.js se envían datos desde un componente padre hacia el hijo mediante sus propiedades ( props ) 
                            y desde el componente hijo hacia el padre mediante eventos ( $emit ).

                        <br>
                        <br>

                            <b>Pasando datos mediante eventos</b><br>
                            Paso de datos con el bus de eventos, un bus de eventos no es más que otra instancia de Vue. Una instancia 
                            que puede tener las mismas propiedades que cualquier otra instancia.


                        </p>

                    
                    </div>


                    
                    </div>

                    <br>
                <h4 class="mt-0 text-center" style="background-color: coral; color: aliceblue;">Computo 2</h4>
                    <br>

                <div class="container my-5">
                    <nav>
                    <div class="nav nav-tabs" id="nav-tab2" role="tablist">

                        <!--Computo 2 semana 7 en adelante-->
                        
                        <button class="nav-link active text-danger" id="nav-cont7-tab" data-bs-toggle="tab" 
                        data-bs-target="#nav-cont7" type="button" role="tab" aria-controls="nav-cont7" 
                        aria-selected="true">Contenido 7</button>

                        <button class="nav-link text-danger" id="nav-cont8-tab" data-bs-toggle="tab" 
                        data-bs-target="#nav-cont8" type="button" role="tab" aria-controls="nav-cont8" 
                        aria-selected="false">Contenido 8</button>

                        <button class="nav-link text-danger" id="nav-cont9-tab" data-bs-toggle="tab" 
                        data-bs-target="#nav-cont9" type="button" role="tab" aria-controls="nav-cont9" 
                        aria-selected="false">Contenido 9</button>

                        <button class="nav-link text-danger" id="nav-cont10-tab" data-bs-toggle="tab" 
                        data-bs-target="#nav-cont10" type="button" role="tab" aria-controls="nav-cont10" 
                        aria-selected="false">Contenido 10</button>

                        <button class="nav-link text-danger" id="nav-cont11-tab" data-bs-toggle="tab" 
                        data-bs-target="#nav-cont11" type="button" role="tab" aria-controls="nav-cont11" 
                        aria-selected="false">Contenido 11</button>
                        
                        <button class="nav-link text-danger" id="nav-cont12-tab" data-bs-toggle="tab" 
                        data-bs-target="#nav-cont12" type="button" role="tab" aria-controls="nav-cont12" 
                        aria-selected="false">Contenido 12</button>

                    </div>
                    </nav>
                    



                    <div class="tab-content" id="nav-tabContent2">

                    <!--Computo 2 semana7 -->

                    <div class="tab-pane fade show active p-3" id="nav-cont7" role="tabpanel" aria-labelledby="nav-cont7-tab">
                        <h2>Contenido #7 Introducción al desarrollo con PHP</h2>
                        <h5>Introducción al desarrollo con PHP</h5>
                        <p>
                             
                            PHP es un lenguaje de programación de código abierto muy popular para el 
                            desarrollo web que puede ser incrustado dentro de código HTML.
                            Su origen se remonta a 1995 cuando Rasmus Lerdorf comenzó a 
                            desarrollarlo usando algunos script en Perl, a los cuales posteriormente 
                            fue escribiendo más implementaciones usando C para permitir la 
                            comunicación con Bases de Datos y desarrollo de aplicaciones web dinámicas.

                        <br>
                        <br>
                            <b>Como funciona PHP</b><br>
                            El servidor web lee la página PHP y envía un documento compilado en formato HTML.

                        <br>
                        <br>

                        <img src="https://i.imgur.com/i6aMXfS.jpeg" class="img-fluid" alt="partes de una directiva for">

                        <br>
                        <br>

                            <b>¿Qué puede hacer? </b><br>
                            <ul>
                                <li>
                                    Permite ejecución de scripts en la parte del servidor.
                                </li>
                                <li>
                                    Ejecución de scripts desde la línea de comandos 
                                    sin la necesidad de un servidor web o navegador.
                                </li>
                                <li>
                                    Escritura de aplicaciones gráficas clientes por 
                                    medio de una extensión llamada PHP-GTK.
                                </li>
                                <li>
                                    Puede ser utilizado en cualquier sistema operativo de los más populares.
                                </li>
                                <li>Soporta la mayoría de los servidores.</li>
                                <li>
                                    Se necesitan tres elementos: El analizador PHP (CGI o módulo), 
                                    un servidor web y un navegador.
                                </li>
                            </ul>
                            <b>Ventajas de usar PHP</b><br>
                            <ul>
                                <li>
                                    Su curva aprendizaje es muy rápida, comparado con otros lenguajes de programación. 
                                </li>
                                <li>
                                    Con PHP se puede tener un fácil acceso a diferentes sistemas de gestión de bases de datos. 
                                </li>
                                <li>
                                    La programación en este lenguaje se puede hacer desde cualquier editor de texto. 
                                </li>
                                <li>
                                    Existe una comunidad muy grande alrededor del mundo desarrollando en PHP y mejorándolo día a día.
                                </li>

                            </ul>

                            <i>
                                El cliente, hace la petición al servidor, éste ejecuta acciones y 
                                devuelve información al cliente. Es decir, para poder ejecutar php 
                                se debe disponer de un servidor y una conexión hacia un cliente.
                            </i><br><br>

                            <b>Del lado del cliente y del lado del servidor</b><br>
                            Los scripts del lado del cliente son procesados por los navegadores web. 
                            Cuando su navegador, es decir el cliente, solicita una página que contiene 
                            scripts del lado del cliente, el servidor responderá enviando códigos fuente 
                            que son ejecutables para el navegador. Por otro lado, el lenguaje de secuencias 
                            de comandos del lado del servidor significa que las secuencias de comandos 
                            se ejecutan en los servidores antes de enviarse a los navegadores. Entonces, 
                            en lugar de enviar el código fuente, los servidores web procesan (analizan) 
                            los códigos primero convirtiéndolos en un formato HTML simple.

                        <br>
                        <br>

                        </p>

                        <h5>Sintaxis en php</h5>

                        <p>

                            <b>Variables reservadas en PHP</b><br>
                            Son las que PHP define con valores por defecto, están disponibles 
                            sin necesidad de requerir librerías y no se puede cambiar su contenido:
                            <img src="https://i.imgur.com/ZbOc4eh.png" class="img-fluid" alt="partes de una directiva for">

                        <br>
                        <br>

                            <b>Tipos de datos en PHP</b><br>
                            En PHP no es obligatorio indicar el tipo de datos al que pertenece 
                            una variable. Existen los siguientes tipos: 

                            <ul>
                                <li>Integer: enteros positivos, negativos (se pueden representar en hexadecimal). </li>
                                <li>Float, Double: con decimales. </li>
                                <li>String: cadena de caracteres Boolean: tipo lógico, valores true o false.</li>
                            </ul>

                           
                            <b>Operadores de incremento y decremento</b><br>

                            <img src="https://i.imgur.com/LpO5pWh.png" class="img-fluid" alt="partes de una directiva for">
                            <br>
                            <b>Operadores de comparación</b><br>

                            <img src="https://i.imgur.com/e2ERqyk.png" class="img-fluid" alt="partes de una directiva for">
                            <br>
                            <b>Operadores lógicos</b><br>

                            <img src="https://i.imgur.com/55Mz8Mm.png" class="img-fluid" alt="partes de una directiva for">
                            <br>



                        </p>

                    
                    </div>

                    <div class="tab-pane fade p-3" id="nav-cont8" role="tabpanel" aria-labelledby="nav-cont8-tab">
                        <h2>Contenido #8 Loops, Arrays and Function</h2>
                        <h5>Bucles</h5>
                        <p>
                             
                            Un bucle en PHP se usa para ejecutar una declaración o un bloque de declaraciones, 
                            varias veces hasta que se cumpla una condición específica. PHP soporta:


                        <br>
                        <br>
                            
                            <ul>
                                <li><u> For loop</u></li>
                                <p>
                                    Este tipo de bucles se utiliza cuando el usuario sabe de antemano cuántas 
                                    veces debe ejecutarse el bloque. Es decir, el número de iteraciones se 
                                    conoce de antemano. Hay tres parámetros principales para el código: <br>
                                    la inicialización, la condición de prueba y el contador.
                                    <br>
                                    <img src="https://i.imgur.com/xfRVr9z.png" class="img-fluid" alt="partes de una directiva for">

                                </p>
                                <li><u> While loop</u></li>
                                <p>
                                    El ciclo while también es un ciclo de control de entrada como
                                    para los ciclos, es decir, primero verifica la condición al
                                    comienzo del ciclo y, si es verdadero, ingresa al ciclo y ejecuta el bloque de 
                                    instrucciones, y continúa ejecutándolo como siempre y cuando la condición sea cierta.

                                    <img src="https://i.imgur.com/VaUFxQT.png" class="img-fluid" alt="partes de una directiva for">
                                </p>
                                <li><u> Do-While loop</u></li>
                                <p>
                                    Es un bucle de control de salida, lo que significa que primero ingresa al bucle, 
                                    ejecuta las declaraciones y luego verifica la condición. Por lo tanto, una declaración 
                                    se ejecuta al menos una vez al usar el bucle do ... while. Después de ejecutar una vez, 
                                    el programa se ejecuta siempre que la condición sea verdadera.
                                    <img src="https://i.imgur.com/ic6BJCI.png" class="img-fluid" alt="partes de una directiva for">

                                </p>

                                <li><u> Foreach loop</u></li>
                                <p>
                                    Este bucle se utiliza para iterar sobre matrices. Para cada
                                    contador de bucle, se asigna un elemento de matriz y el
                                    siguiente contador se desplaza al siguiente elemento.
                                    <br>
                                    <img src="https://i.imgur.com/wlDZmOn.png" class="img-fluid" alt="partes de una directiva for">

                                </p>
                            
                            </ul>


                        <br>
                        <br>
                            <h3>Arreglos</h3>
                        

                            <b>Matrices indexadas o numéricas:  </b><br>
                                Una matriz con un índice numérico donde los valores se almacenan linealmente.

                            <br><b>Matrices asociativas:</b><br>
                                Una matriz con un índice de cadena donde en lugar de almacenamiento lineal, 
                                a cada valor se le puede asignar una clave específica.

                            <br><b>Matrices multidimensionales: </b><br>
                            Una matriz que contiene una matriz única o múltiple dentro de ella y se 
                            puede acceder a través de múltiples índices
                        <br>
                        <br>

                        </p>

                        <h5>Funciones en PHP</h5>
                        <p>
                            Son bloques de código escritos previamente para realizar una tarea especifica y que se pueden 
                            reutilizar todas las ocasiones que sea necesario. 

                            <br>

                            <br><b>Funciones integradas de PHP</b><br>
                            Las funciones integradas son funciones predefinidas en PHP que existen en el paquete de instalación. 
                            <ul>
                                <li>Funciones de cadena</li>
                                <li>Funciones numéricas</li>
                                <li>Funciones de fecha</li>
                            </ul>



                            <b>Funciones creadas por el usuario</b><br>
                            Las funciones definidas por el usuario son útiles cuando; <br>
                            ▸ Existen tareas de rutina en su aplicación, como agregar datos a la base de datos. <br>
                            ▸ Realizar comprobaciones de validación de los datos. <br>
                            ▸ Autenticar usuarios en el sistema, entre otras.


                        </p>

                    
                    </div>
                    
                    <div class="tab-pane fade p-3" id="nav-cont9" role="tabpanel" aria-labelledby="nav-cont9-tab">
                        <h2>Contenido #9 Introducción a POO con PHP</h2>
                        <p>
                            La programación orientada a objetos se basa en el concepto de crear un modelo del problema 
                            de destino en sus programas. La programación orientada a objetos disminuye los errores y 
                            promociona la reutilización del código.
                            Su uso se popularizó a principios de la década de 1990. Actualmente son muchos los lenguajes 
                            de programación que soportan la orientación a objetos.
                        </p>
                        <h5>Los 4 pilares de la POO son:</h5>

                            <dl> 
                                <dt>Abstracción</dt>
                                <dd>
                                    Definición propia que cada persona hace para la representación de las características sobre 
                                    un objeto. Se refiere a la perspectiva propia de cada persona.

                                </dd>
                                <dt>Encapsulamiento </dt>
                                <dd>
                                    Determina cuales propiedades van a ser accesibles y cales no lo son, permite asegurar 
                                    que la información de un objeto esta oculta del mundo exterior

                                </dd>
                                <dt>Herencia</dt>
                                <dd>
                                    Es la propiedad que permite crear clases a partir de otras ya existentes, obteniendo 
                                    características (métodos y atributos) similares a los ya existentes.

                                </dd>
                                <dt>Polimorfismo </dt>
                                <dd>
                                    Son comportamientos diferentes, asociados a objetos distintos, pueden 
                                    compartir el mismo nombre; al llamarlos por ese nombre se utilizará el comportamiento correspondiente al objeto que se esté usando.

                                </dd>
                            </dl>

                        <p>
                             
                           <h4>Infografia POO</h4><br>

                           <img src="https://i.imgur.com/9gThS0a.png" class="img-fluid" alt="partes de una directiva for">

                        <br>
                        <br>
                            
                            <h3>Ventajas de la Programación Orientada a Objetos:</h3>
                            <img src="https://i.imgur.com/y7LvjnI.png" class="img-fluid" alt="partes de una directiva for">

                            
                        <br>
                        <br>

                        </p>



                    
                    </div>

                    <div class="tab-pane fade p-3" id="nav-cont10" role="tabpanel" aria-labelledby="nav-cont10-tab">
                        <h2>Contenido #10 Clases abstractas e interfaces.</h2>
                        <p>
                            <ul>
                                <li>Tanto las clases abstractas como las interfaces son mecanismos que obligan la herencia.</li>
                                <li>No se pueden instanciar, es decir, no se puede crear objetos de ellas.</li>
                                <li>Son mecanismos para que puedan interactuar varios objetos no relacionados entre sí.</li>
                                <li>Son protocolos o “contratos” que obligan la herencia.</li>
                                <li>Contienen las declaraciones de los métodos, pero no su implementación. </li>
                                <li>Al igual que las clases abstractas, son plantillas de comportamiento que deben ser implementados por otras clases.</li>
                            </ul>

                            <h5>Clases abstractas</h5><br>

                            <img src="https://i.imgur.com/kTnt3jL.png" class="img-fluid" alt="partes de una directiva for">
                            
                        </p>
                        <h5>Interfaces</h5>
                            <p>
                                Nos permiten crear código para especificar que métodos deben ser implementados 
                                por una clase (prototipos), sin definir su implementación. Las interfaces se 
                                definen con la palabra reservada interface.
                            </p>

                            <ul>
                                <li>Los métodos declarados en una interfaz deben ser públicos. </li>
                                <li>Para implementar una interface desde una clase se utiliza la palabra reservada implements. </li>
                                <li>Una clase puede implementar más de una interfaz si se desea.</li>
                                <li>Una clase que herede de una interfase debe implementar todas las definiciones contenidas en ella.</li>
                                <li>Los elementos de la interfase no llevan los modificadores “public” o “abstract”.</li>
                                <li>TODOS los elementos declarados dentro de una inteface se consideran públicos y abstractos.</li>
                            </ul>

                            <img src="https://i.imgur.com/0g7pFUP.png" class="img-fluid" alt="partes de una directiva for">



                        <br>
                        <br>
                    
                    </div>

                    <div class="tab-pane fade p-3" id="nav-cont11" role="tabpanel" aria-labelledby="nav-cont11-tab">
                        <h2>Contenido #11 Introducción a Laravel Conectando a una BD MySQL.</h2>
                        <p>
                            Protocolo que permite la obtención de recursos, como documentos HTML. Es la base de cualquier 
                            intercambio de datos en la Web y es un protocolo cliente-servidor, lo que significa que las
                             solicitudes son iniciadas por el destinatario, generalmente el navegador Web.
                            Utiliza diferentes métodos de solicitud específicos para realizar diferentes tareas.
                            <br>
                            <br>

                            <ul>
                                <li>GET solicita un recurso específico en su totalidad.</li>
                                <li>HEAD solicita un recurso específico sin el contenido del cuerpo.</li>
                                <li>POST agrega contenido, mensajes o datos a una nueva página en un recurso web existente.</li>
                                <li>PUT modifica directamente un recurso web existente o crea un nuevo si es necesario.</li>
                                <li>DELETE se deshace de un recurso específico. </li>
                                <li>TRACE muestra a los usuarios cualquier cambio o adición realizada a un recurso web.</li>
                                <li>OPCTIONS muestra a los usuarios qué métodos HTTP están disponibles para una URL específica. </li>
                                <li>CONNECT convierte la conexión de solicitud en un túnel TCP / IP transparente.</li>
                                <li>PATCH modifica parcialmente un recurso web.</li>
                            </ul>

                        </p>

                            <dl> 
                                <dt>¿Qué es Laravel?</dt>
                                <dd>
                                    Laravel es un Framework con una sintaxis elegante y expresiva. 
                                    Un Framework proporciona una estructura y un punto de partida para crear aplicaciones. 

                                </dd>

                            </dl>

                            <img src="https://i.imgur.com/19uh3T1.png" class="img-fluid" alt="partes de una directiva for">

                            <br>
                            <br>
                        <h5>Características de Laravel</h5>
 
                            <ul>
                                <li>
                                    Un sistema de rutas, mediante las cuales es fácil crear y mantener 
                                    todo tipo de URLs amistosas a usuarios y buscadores, rutas de API, etc. 
                                </li>
                                <li>
                                    Un sistema de abstracción de base de datos, con un ORM potente pero sencillo de manejar, 
                                    mediante el que podemos tratar los datos de la base de datos como si fueran simples objetos. 
                                </li>
                                <li>Un sistema para creación de colas de trabajo, de modo que es posible enviar tareas para ejecución en 
                                    background y aumentar el rendimiento de las aplicaciones. 
                                </li>
                                <li>
                                    Varias configuraciones para envío de email, con proveedores diversos.
                                </li>
                                <li>
                                    Una abstracción del sistema de archivos, mediante el cual podemos escribir datos en proveedores cloud, 
                                    y por supuesto en el disco del servidor, con el mismo código. 
                                </li>
                                <li>Gestión de sesiones.</li>
                                <li>
                                    Sistema de autenticación, con todo lo necesario como recordatorios de clave, 
                                    confirmación de cuentas, recordar un usuario logueado, etc.
                                </li>
                            </ul>

                            <h5>Ecosistema Laravel</h5>
                            <p>
                                Algunos de los servicios y herramientas para el framework Laravel más populares y útiles son los siguientes:
                            </p>
                            <ul>
                                <li>Forge: sistema de administración de servidores, como una especie de panel con el que se 
                                    puede crear dominios, instalar Laravel, desplegar aplicaciones, etc.
                                </li>
                                <li>
                                    Vapor: permite desplegar aplicaciones Laravel sin necesidad 
                                    de tener un servidor. Es decir, es un bakend "serverless".
                                </li>
                                <li>
                                    Nova: sistema de gestión de contenido que permite crear los típicos 
                                    paneles de administración de una manera muy cómoda.
                                </li>
                                <li>
                                    Envoyer: Permite integración continua de las aplicaciones Laravel, simplemente haciendo un push al 
                                    repositorio la aplicación se despliega en su nueva versión, sin interrumpir el servicio.
                                </li>
                                <li>
                                    Spark: Permite crear aplicaciones con una base de código encima del propio Laravel, 
                                    evitando muchas partes que se pueden repetir en muchos de los proyectos.
                                </li>

                            </ul>


                            <h5>Servicios gratuitos del ecosistema.</h5>
                            <ul>
                                <li>Homestead.</li>
                                <li>Valet.</li>
                                <li>Cashier.</li>
                                <li>Scout.</li>
                                <li>Passport.</li>
                                <li>Mix.</li>
                                <li>Echo.</li>
                                <li>Horizon.</li>
                            </ul>

                            <h5>Servidores Laravel</h5>
                            <ul>
                                <li>Servidor Interno.</li>
                                <li>Laravel Valet.</li>
                                <li>Homestead</li>
                                <li>Cualquier otro servicio web habitual.</li>
                            </ul>

                                            
                            <h5>Conexión con Base de datos MySQL | laravel </h5> <br>
                            <img src="https://i.imgur.com/v8d0eI9.png" class="img-fluid" alt="partes de una directiva for">

                            <p>
                                Una vez que se crea la base de datos, debe informar a su proyecto de laravel los detalles 
                                sobre la base de datos. Laravel tiene una forma bastante simple de hacer eso. Toda la configuración 
                                que debe permanecer privada y no debe compartir va al archivo .env de su proyecto laravel.
                                <br>
                                <br>
                                Ejecutar la migración (opcional) Para probar si ha combinado con éxito el proyecto Laravel 
                                con la base de datos, se ejecutará el comando de migración. El proyecto Laravel por defecto 
                                viene con una tabla predeterminada para almacenar usuarios y su solicitud de contraseña. 
                                Una vez que ejecute el comando migrate, debería producir las tablas predeterminadas para usted dentro de la base de datos.

                            </p>
                            <img src="https://i.imgur.com/v2H2px8.png" class="img-fluid" alt="partes de una directiva for">


                        <br>
                        <br>
                    
                    </div>

                    <div class="tab-pane fade p-3" id="nav-cont12" role="tabpanel" aria-labelledby="nav-cont12-tab">
                        <h2>Contenido #12 CRUD y formularios con Laravel. </h2>
                        <p>
                            <br>
                            Para la creación de un CRUD con Laravel se deben seguir los siguientes pasos.
                            <br>
                            <br>

                            <li>
                                Se crea la tabla para la cual se creará el CRUD, 
                                seguido se realizará el proceso de migración.

                            </li>

                  
                            <img src="https://i.imgur.com/7MpKBIP.png" class="img-fluid" alt="partes de una directiva for">
                            
                            <br>
                            <br>                            
                            <li>
                                Agregar ruta de recursos,
                                para las operaciones CRUD, Laravel proporciona una 
                                ruta de recursos que se encargará del CRUD, que es una ruta para Crear, 
                                otra ruta para Recuperar, una ruta separada para Actualizar y finalmente 
                                una ruta para Eliminar.

                            </li>
                  
                            <img src="https://i.imgur.com/7K1gMyN.png" class="img-fluid" alt="partes de una directiva for">
                            
                            <br>
                            <br>                            
                            <li>
                                Crear controlador y modelo. Anteriormente, en el paso 4, el segundo 
                                parámetro para el recurso es AlumnoController, por lo que se debe 
                                crear el controlador y especificar el modelo de recurso agregando model.

                            </li>
                  
                            <img src="https://i.imgur.com/VXpAaep.png" class="img-fluid" alt="partes de una directiva for">
                            
                            <br>
                            <br>                            
                            <li>
                                Editar controlador
                            </li>
                  
                            <img src="https://i.imgur.com/5dHAxDQ.png" class="img-fluid" alt="partes de una directiva for">
                            
                            <br>
                            <br>                            
                            <li>
                                Agregar vistas, Laravel hace uso del sistema de plantillas de hoja 
                                para las vistas, dentro de la carpeta vistas se crearán dos carpetas 
                                Layouts y Alumno.
                            </li>
                  
                            <img src="https://i.imgur.com/jF1IiPA.png" class="img-fluid" alt="partes de una directiva for">
                            
                            <br>
                            <br>                            
                            <li>
                                Prueba, finalmente ejecutar la aplicación, y visualizar la salida en el navegador.
                            </li>
                  
                            <img src="https://i.imgur.com/jd1uYkA.png" class="img-fluid" alt="partes de una directiva for">
                            
                        </p>
                       
                    
                    </div>

                    </div>
                    </div>


                </div>


                <h4 class="mt-0 text-center" style="background-color: coral; color: aliceblue;">Computo 3</h4>
                    <br>

                <div class="container my-5">
                    <nav>
                    <div class="nav nav-tabs" id="nav-tab2" role="tablist">

                        <!--Computo 3 semana 14 en adelante-->
                        
                        <button class="nav-link active text-danger" id="nav-cont14-tab" data-bs-toggle="tab" 
                        data-bs-target="#nav-cont14" type="button" role="tab" aria-controls="nav-cont14" 
                        aria-selected="true">Contenido 14</button>

                        <button class="nav-link text-danger" id="nav-cont15-tab" data-bs-toggle="tab" 
                        data-bs-target="#nav-cont15" type="button" role="tab" aria-controls="nav-cont15" 
                        aria-selected="false">Contenido 15</button>

                        <button class="nav-link text-danger" id="nav-cont16-tab" data-bs-toggle="tab" 
                        data-bs-target="#nav-cont16" type="button" role="tab" aria-controls="nav-cont16" 
                        aria-selected="false">Contenido 16</button>

                        <button class="nav-link text-danger" id="nav-cont17-tab" data-bs-toggle="tab" 
                        data-bs-target="#nav-cont17" type="button" role="tab" aria-controls="nav-cont17" 
                        aria-selected="false">Contenido 17</button>

                        <button class="nav-link text-danger" id="nav-cont18-tab" data-bs-toggle="tab" 
                        data-bs-target="#nav-cont18" type="button" role="tab" aria-controls="nav-cont18" 
                        aria-selected="false">Contenido 18</button>
                        
                        <button class="nav-link text-danger" id="nav-cont19-tab" data-bs-toggle="tab" 
                        data-bs-target="#nav-cont19" type="button" role="tab" aria-controls="nav-cont19" 
                        aria-selected="false">Contenido 19</button>

                    </div>
                    </nav>
                    



                    <div class="tab-content" id="nav-tabContent3">

                    <!--Computo 3 semana14 -->

                    <div class="tab-pane fade show active p-3" id="nav-cont14" role="tabpanel" aria-labelledby="nav-cont14-tab">
                        <h2>Contenido #14 Sistemas de rutas y controladores</h2>
                        
                        <p>
                            Laravel cuenta con un sistema de rutas integrado dentro del proyecto creado, 
                            esta carpeta recibe el nombre de routes y dentro de él tiene una serie de 
                            archivos que ayudan a modificar y configurar diferentes aspectos de los accesos, 
                            entre estos archivos son:

                        <br>
                        <br>
                            <ul>
                                <li>
                                    routes/api.php: En este archivo se definen todas las rutas de las
                                     APIs que puede llegar a tener nuestra aplicación.
                                </li>
                                <li>
                                    routes/channels.php: Aquí definimos los canales transmisión de eventos. 
                                    Por ejemplo, cuando realizamos notificaciones en tiempo real. 
                                </li>
                                <li>
                                    routes/console.php: En el archivo de rutas console.php definimos 
                                    comandos de consola que pueden interactuar con el usuario u otro sistema. 
                                </li>
                                <li>
                                    routes/web.php: En este archivo de rutas es donde definimos todas 
                                    las rutas de nuestra aplicación web que pueden ser ingresadas por la barra de 
                                    direcciones del navegador.
                                </li>
                            </ul>

                        <br>
                        <br>

                        <img src="https://i.imgur.com/EFCrMDv.png" class="img-fluid" alt="partes de una directiva for">

                        <br>
                        <br>

                            <b>Tipos de rutas en Laravel </b><br>
                            <ul>
                                <li>
                                    Route::get($uri, $callback); 
                                </li>
                                <li>
                                    Route::post($uri, $callback); 
                                </li>
                                <li>
                                    Route::put($uri, $callback); 
                                </li>
                                <li>
                                    Route::patch($uri, $callback); 
                                </li>
                                <li>
                                    Route::delete($uri, $callback); 
                                </li>
                                <li>
                                    Route::options($uri, $callback);
                                </li>
                            </ul>
                            <b>Controladores en Laravel</b><br>
                            <br>
                            <br>
                            En Laravel, los controladores son clases que se utilizan para agrupar la 
                            lógica relacionada con la manipulación de solicitudes HTTP. La idea principal 
                            es separar la lógica de la aplicación de la lógica de enrutamiento, lo 
                            que facilita la organización y el mantenimiento del código.
                            <br>
                            <br>
                            Los controladores se pueden considerar como intermediarios entre las rutas y 
                            las vistas. Cuando una solicitud HTTP llega a Laravel, la ruta correspondiente 
                            invoca un método en el controlador que se encarga de procesar la solicitud y 
                            proporcionar la respuesta adecuada. Dentro de un controlador, se pueden tener 
                            varios métodos que corresponden a diferentes rutas y acciones.
                            
                            <br>
                            <br>

                            <img src="https://i.imgur.com/H5tYSmn.png" class="img-fluid" alt="partes de una directiva for">

                            <br>
                            <br>


                            <b>Formularios en Laravel</b><br>
                            En Laravel, los formularios son una manera de recopilar información del usuario a través de una 
                            interfaz gráfica. Un formulario típicamente contiene una serie de campos de entrada 
                            (como cuadros de texto, botones de opción, menús desplegables, etc.) que el usuario 
                            puede completar y enviar al servidor para su procesamiento. 
                            <br>
                            En Laravel, se puede crear fácilmente formularios HTML utilizando la clase Form. 
                            Esta clase proporciona métodos para crear diferentes tipos de elementos de formulario, 
                            como campos de entrada de texto, casillas de verificación, botones de radio, menús 
                            desplegables, etc. Además, Laravel también proporciona la capacidad de validar y 
                            procesar los datos del formulario enviados por el usuario utilizando el sistema de 
                            validación y controladores de Laravel

                        <br>
                        <br>

                        </p>

                        <h5>Validaciones en formularios</h5>

                        <p>

                            <b>
                                Antes de crear la validación, se muestra la migración correspondiente.
                            </b><br>
                            Son las que PHP define con valores por defecto, están disponibles 
                            sin necesidad de requerir librerías y no se puede cambiar su contenido:
                            <img src="https://i.imgur.com/QGAOgNJ.png" class="img-fluid" alt="partes de una directiva for">

                        <br>
                        <br>



                            <img src="https://i.imgur.com/w3uAtTE.png" class="img-fluid" alt="partes de una directiva for">
                            <br>

                            <b>Mostrar errores en formulario</b><br>

                            <img src="https://i.imgur.com/EH8nhQL.png" class="img-fluid" alt="partes de una directiva for">
                            <br>
                            Debajo del input a validar escribir la directiva @error el cual permite imprimir el 
                            mensaje de error que corresponde a este campo.


                        </p>

                    
                    </div>

                    <div class="tab-pane fade p-3" id="nav-cont15" role="tabpanel" aria-labelledby="nav-cont15-tab">
                        <h2>Contenido #15 Validación de datos (RUTAS, VISTAS, FORMULARIOS Y CONTROLADORES) | BLADE | LARAVEL/UI.</h2>
                        <h5>validaciones en Laravel</h5>
                        <br>
                            
                            <ul>
                                <p> 
                                    Existen varias formas de validar una aplicación para cubrir aspectos de seguridad como SQL Injection, ataques XSS o CSRF, algunas de ellas son:

                                </p>
                                <ul>
                                    <li>Validación de lado del cliente (Javascript y etiquetas HTML).</li>
                                    <li>Validación a nivel de base de datos (Migraciones y modelos).</li>
                                    <li>Validación de formularios (Request).</li>
                                </ul>



                                <p>
                                    <b>Validación del lado del cliente</b>

                                    Se puede validar que los campos de un formulario sean requeridos al agregar el atributo required
                                    El atributo required es un atributo booleano. Cuando esta presente, este especifica
                                    que un campo debe ser rellenado antes de ser enviado el contenido del formulario.
                                    
                                    <br>
                                    <img src="https://i.imgur.com/oYmM7No.png" class="img-fluid" alt="partes de una directiva for">

                                </p>
                                
                                <p>
                                    El atributo required trabaja con los siguientes tipos de input:
                                    <br>
                                    
                                    <ul>
                                        <il>text</il>
                                        <il>search</il>
                                        <il>url</il>
                                        <il>tel</il>
                                        <il>email</il>
                                        <il>password</il>
                                        <il>data pickers</il>
                                        <il>number</il>
                                        <il>checkbox</il>
                                    </ul>

                                </p>
                                <b>Validación de formularios con plugins JQuery</b>
                                <p>
                                    El mejor plugin JQuery para validar formularios es formvalidation. Sin embargo
                                    formvalidation es un plugin que tiene un costo dependiendo la licencia que se
                                    requiera utilizar. Formvalidation es compatible con los formularios de los frameworks
                                    css más populares:

                                </p>

                                <ul>
                                    <li>Bootstrap</li>
                                    <li>Foundation</li>
                                    <li>Pure</li>
                                    <li>Semantic UI</li>
                                    <li>Otros</li>
                                </ul>
                            
                            </ul>

                        <br>
                        <br>


                        <h5>BLADE</h5>
                        <p>
                            Blade es un motor de plantillas (template engine) en el framework de PHP Laravel que permite definir la interfaz de usuario de una aplicación web de una manera fácil.
                            Blade proporciona una sintaxis simple y legible para definir vistas, que se compilan en
                            código PHP y se ejecutan en el servidor para generar el HTML que se enviará al
                            navegador.

                            <br>

                            <br><b>Algunas de las características de Blade incluyen:</b><br>
                           
                            <ul>
                                <li>
                                    Herencia de plantillas: permite definir una plantilla base que puede ser extendida por otras plantillas, lo que permite 
                                    reutilizar código y mantener una estructura consistente en toda la aplicación.
                                </li>
                                <li>
                                    Secciones: permiten definir secciones en una plantilla que pueden ser rellenadas por otras vistas que
                                     la extienden, lo que facilita la creación de componentes reutilizables.
                                </li>
                                <li>
                                    Directivas: Blade proporciona una serie de directivas (como @if, @foreach, @include, entre otras) que permiten escribir 
                                    lógica de control de flujo y reutilizar secciones de código.
                                </li>
                            </ul>


                        </p>

                    
                    </div>
                    
                    <div class="tab-pane fade p-3" id="nav-cont16" role="tabpanel" aria-labelledby="nav-cont16-tab">
                        <h2>Contenido #16 API REST con Laravel.</h2>
                        <p>
                            Laravel le permite crear API RESTful de manera fácil y
                            rápida. Este podría ser el back-end de una aplicación
                            front-end, una fuente de datos para una aplicación
                            móvil o un servicio para otras aplicaciones o API.
                            <br>

                            REST significa transferencia de estado representacional y es 
                            un estilo arquitectónico para la comunicación de red entre 
                            aplicaciones, que se basa en un protocolo sin estado 
                            (generalmente HTTP) para la interacción.

                        </p>
                        <h5>Verbos HTTP</h5>

                        <p>
                            Los verbos HTTP representan acciones
                            En las API RESTful, se utilizan los verbos HTTP como acciones y los puntos finales son los recursos sobre los
                            que se actúa.

                        
                            <br><br>

                            <ul>
                                <li>GET: recuperar recursos</li>
                                <li>POST: crear recursos</li>
                                <li>PUT: actualizar recursos</li>
                                <li>DELETE: eliminar recursos</li>
                            </ul>

                            <br>
                            <img src="https://i.imgur.com/duhYnDJ.png" class="img-fluid" alt="partes de una directiva for">


                        </p>
                       

                    
                    </div>

                    <div class="tab-pane fade p-3" id="nav-cont17" role="tabpanel" aria-labelledby="nav-cont17-tab">
                        <h2>Contenido #17 Autenticación API REST con Laravel.</h2>
                        <p>

                            <b>¿Qué es la autenticación de la API?</b>
                            <br>
                            La autenticación de la API es una capa de seguridad utilizada en aplicaciones 
                            para permitir que los usuarios inicien sesión, proteger la privacidad y 
                            controlar los permisos de los usuarios. Su objetivo es proteger información 
                            confidencial y garantizar que solo los usuarios autorizados tengan acceso a 
                            los recursos protegidos.

                            <br>
                            <br>
                            <b>Por qué implementar la autenticación basada en tokens </b>
                            <br>
                            La autenticación de una API basada en tokens es un método efectivo ampliamente 
                            utilizado. Los tokens son utilizados para validar la identidad de un usuario 
                            y permitirles acceder a los recursos protegidos. Este enfoque es fácil de 
                            implementar, proporciona un nivel adecuado de seguridad y es rápido y eficiente.


                            <br>
                            <br>
                            <b>Token de seguridad</b>
                            La autenticación basada en tokens funciona mediante el intercambio de tokens entre 
                            el cliente y el servidor. Los tokens son cifrados y firmados para evitar 
                            manipulaciones o suplantaciones de identidad. Sin embargo, la seguridad de esta 
                            autenticación depende de la implementación adecuada, como el uso de algoritmos de 
                            cifrado y firma seguros, el almacenamiento seguro de los tokens y la consideración 
                            de otros factores de seguridad como la gestión de contraseñas y la protección 
                            contra ataques.

                            <br>
                            <br>
                            <b>Rest API Laravel</b>
                            Muchos puntos de conexión de la API REST necesitan autenticación o devuelven 
                            información adicional si se realiza el proceso de autenticación.
                            Para autenticar la solicitud, envía un token en el encabezado Authorization 
                            de la solicitud. En el ejemplo siguiente, solo basta con reemplazar YOUR_TOKEN 
                            por una referencia al token.

                            <br>
                            curl --request GET \
                            <br>
                            --url "https://api.pets.com/pets" \
                            <br>
                            --header "Authorization: Bearer YOUR-TOKEN" \

                            <br>


                        </p>
                        <h5>Interfaces</h5>
                            <p>
                                Nos permiten crear código para especificar que métodos deben ser implementados 
                                por una clase (prototipos), sin definir su implementación. Las interfaces se 
                                definen con la palabra reservada interface.
                            </p>

                            <ul>
                                <li>Los métodos declarados en una interfaz deben ser públicos. </li>
                                <li>Para implementar una interface desde una clase se utiliza la palabra reservada implements. </li>
                                <li>Una clase puede implementar más de una interfaz si se desea.</li>
                                <li>Una clase que herede de una interfase debe implementar todas las definiciones contenidas en ella.</li>
                                <li>Los elementos de la interfase no llevan los modificadores “public” o “abstract”.</li>
                                <li>TODOS los elementos declarados dentro de una inteface se consideran públicos y abstractos.</li>
                            </ul>

                            <img src="https://i.imgur.com/zI7MVc5.png" class="img-fluid" alt="partes de una directiva for">



                        <br>
                        <br>
                    
                    </div>

                    <div class="tab-pane fade p-3" id="nav-cont18" role="tabpanel" aria-labelledby="nav-cont18-tab">
                        <h2>Contenido #18 Consumo API REST.</h2>
                        <p>
                            Transferencia de estado representacional (REST) es un estilo arquitectónico para compilar servicios web.
                            Normalmente, las solicitudes REST se realizan a través de HTTPS con los mismos verbos HTTP que los
                            exploradores web usan para recuperar páginas web y enviar datos a servidores. Los verbos son: GET,
                            POST, PUT, PATCH, DELETE.

                            <br>
                            <br>

                            <b>
                                Las API de servicio web que cumplen con REST se definen mediante:
                            </b>

                            <ul>
                                <li>Identificador URI base.</li>
                                <li>Métodos HTTP, como GET, POST, PUT, PATCH o DELETE.</li>
                                <li>Tipo de medio para los datos, como notación de objetos JavaScript (JSON).</li>
                            </ul>

                        </p>

                            <b>Consumir API Rest con VueJs</b>

                            <ol>
                                <li>Instalar librería y configurar archivo vite.config.js, importando el plugin de vite vue.</li>
                                <li>Ejecutar los comandos npm install y npm run dev</li>
                                <li>Verificar en el navegador que la aplicación está corriendo.</li>
                                <li>Crear un componente vue el cual permitirá consumir la API del proyecto Laravel, para el ejemplo se llamará ProjectsComponent</li>
                                <li>Configurar app.js</li>
                                <li>Incluir componente creado en la vista welcome.blade.php</li>
                                <li>Finalmente para visualizar los resultados, iniciar el servidor de Laravel</li>
                            </ol>

                        
                    
                    </div>

                    <div class="tab-pane fade p-3" id="nav-cont19" role="tabpanel" aria-labelledby="nav-cont19-tab">
                        <h2>Contenido #19 Registro con proveedores </h2>
                        <p>
                            <b>Autenticación con Facebook</b>
                            <br>
                            <br>
                            <ol>
                                <li>
                                    Instalar el paquete socialite el cual proporciona una API para conectarse con la cuenta de Facebook.
                                    
                                </li>
                                <li>
                                    Crear una aplicación con Facebook
                                    <br>
                                    <img src="https://i.imgur.com/eRwJBAs.png" class="img-fluid" alt="partes de una directiva for">

                                </li>
                                <li>
                                    Agregar variables al archivo services
                                    <br>
                                    <img src="https://i.imgur.com/ZTgIju3.png" class="img-fluid" alt="partes de una directiva for">
                            
                                </li>
                                <li>
                                    Agregar las variables al archivo .env
                                    <br>
                                    <img src="https://i.imgur.com/xSqq2hq.png" class="img-fluid" alt="partes de una directiva for">
                            
                                </li>
                                <li>
                                    Crear la migración para Facebook_id
                                    <br>
                                    <img src="https://i.imgur.com/NlydcYF.png" class="img-fluid" alt="partes de una directiva for">
                            
                                </li>
                                <li>
                                    Modificar el modelo User.php
                                    <br>

                                    <img src="https://i.imgur.com/pUUyKnX.png" class="img-fluid" alt="partes de una directiva for">
                            
                                </li>
                                <li>
                                    Crear el controlador
                                    <br>
                                    <img src="https://i.imgur.com/oj7WzsL.png" class="img-fluid" alt="partes de una directiva for">
                            
                                </li>
                                <li>
                                    Modificar rutas para agregar la autenticación con Facebook
                                    <br>

                                    <img src="https://i.imgur.com/DRpaCDb.png" class="img-fluid" alt="partes de una directiva for">
                            
                                </li>
                                <li>
                                    Modificar la vista login y agregar el botón para loguear con Facebook
                                    <br>
                                    <img src="https://i.imgur.com/iP1asPv.png" class="img-fluid" alt="partes de una directiva for">
                            
                                </li>
                                <li>
                                    Para iniciar sesión, deberá iniciar la aplicación
                                    <br>
                                    <img src="https://i.imgur.com/aKdOTx8.png" class="img-fluid" alt="partes de una directiva for">

                                </li>
                            </ol>
                  
                            
                        </p>
                       
                    
                    </div>

                    </div>
                    </div>


                </div>



            </div>


    </section>

</template>
    
<style>
    

</style>

