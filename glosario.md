# Glosario
Aquí mostramos un glosario de términos que toda Adalaber debería conocer antes de empezar a hacer entrevistas de trabajo. No todos son términos propiamente de front, por eso con tener una idea general de lo que significan sería suficiente. Os animamos a buscar estos términos y entender lo que son:

- a11y
- **Axios:** Axios es una librería  JavaScript que puede ejecutarse en el navegador y que nos permite hacer sencillas las operaciones como cliente HTTP, por lo que podremos configurar y realizar solicitudes a un servidor y recibiremos respuestas fáciles de procesar.
Es una alternativa que nos brinda multitud de ventajas:
 La API es unificada para las solicitudes Ajax.
 Está optimizado para facilitar el consumo de servicios web, API REST y que devuelvan datos JSON.
 De fácil utilización y como complemento perfecto para las páginas convencionales.
 Pesa poco, apenas 13KB minimizado. Menos aún si se envía comprimido al servidor.
 Compatibilidad con todos los navegadores en sus versiones actuales.
Para trabajar **Axios** utilizaremos el API de las denominadas promesas, las herramientas de los lenguajes de programación que sirven para tramitar fases venideras en el flujo de ejecución de un programa. Es decir, cuando recibamos respuesta del servidor, se llamará a un callback configurada en then y en el momento que arroje un error, se correrá la misma función, pero definida por catch.
- **Babel:** Para solucionar la problemática de compatibilidad entre estándares y navegadores se utilizan compiladores que convierten el código JavaScript de un estándar a otro estándar más antiguo y, por lo tanto, más compatible. Entonces, Babel es un compilador que convierte un estándar nuevo en una versión totalmente compatible de JavaScript. Así, tenemos la ventaja de poder programar en un estándar nuevo sin renunciar a la compatibilidad entre navegadores.
- **Base de datos relacional, SQL:** Es un tipo de base de datos que almacena y proporciona acceso a puntos de datos relacionados entre sí siguiendo el modelo relacional. Se basan en la organización de la información en trozos pequeños, que se relacionan entre ellos mediante la relación de identificadores o índices. Habitualmente los datos son almacenados en tablas existiendo la posibilidad de enlazar los datos de una tabla con los de otra.
La interfaz estándar de programa de usuario y aplicación a una base de datos relacional, es el Lenguaje de Consultas Estructuradas (SQL:Structured Query Language). Los comandos SQL se utilizan tanto para consultas interactivas como para obtener información de una base de datos y la recopilación de datos para informes.
La base de datos relacional más usada y conocida es MySQL junto con Oracle, seguida por SQL Server y PostgreSQL, entre otras.
¿Cuándo utilizar SQL?
-Cuando el volumen de datos no crece o lo hace poco a poco.
-Cuando las necesidades de proceso se pueden asumir en un sólo servidor.
-Cuando no tenemos picos de uso del sistema por parte de los usuarios más allá de los previstos. (Bea)
- **Base de datos no relacional, a veces llamado NoSQL (Not Only SQL),MongoDB:** Este tipo de base de datos a diferencia de las relacionales, no tienen un identificador que sirva de relación entre un conjunto de datos y otros. No usan SQL como lenguaje principal de consultas, se denominan a veces "no solo SQL" para subrayar el hecho de que pueden soportar lenguajes de consulta SQL. Los datos están almacenados normalmente en documentos (no tablas) sino colecciones de documentos que son objetos json= bson (binarijason). Son muy útiles cuando no se tiene un esquema exacto de lo que se va a almacenar.
MongoDB es la base de datos no relacional que  más popularidad ha ganado en los últimos años seguida por Redis,Elasticsearch y Cassandra.
¿Cuándo utilizar NoSQL?
-Cuando el volumen de mis datos crece muy rápidamente en momentos puntuales.
-Cuando las necesidades de proceso no se pueden preveer.
-Cuando tenemos picos de uso del sistema por parte de los usuarios en múltiples ocasiones. (Bea)
- BDD (Bea)
- C Delivery
- C Deployment
- ** Callback** : Un callback es una función que recibe como argumento otra función y la ejecuta. Es importante tener en cuenta que cuando pasamos un callback solo pasamos la definición de la función y no la ejecutamos en el parámetro. Así, la función contenedora elige cuándo ejecutar el callback. Un ejemplo muy común de callback es como función escuchadora de un evento. Los callbacks pueden ayudar a no repetir código y a su mantenimiento, a conseguir funciones más específicas y, en ciertos casos, a mejorar el nivel de abstracción y la lectura del código. Son muy útiles para manejar la asincronía en JS y a través de ellos podemos hacer que una función no tenga conocimiento de la otra función que ejecuta invertiendo así la dependencia a nivel de conocimiento.
- Changelogs
- Code scopes / blocks
- Continuous Integration
- **Desplegar / deployar:** Subir una versión de software o paquete de datos normalmente a producción. Una practica recomendada es no desplegar los viernes.
- **Deuda técnica:** Una de las definiciones de deuda técnica es cuando se realiza una solución rápida y a corto plazo a un problema
con el fin de entregarlo en la fecha prevista  y te comprometes a refactorizarlo en un futuro. Cuando este problema no se refactoriza
porque surjen otros o por falta de tiempo y se queda como está se produce deuda técnica. Post sobre más información de deuda técnica : https://www.federico-toledo.com/deuda-tecnica/
- **DevOps:** DevOps es una metodología de desarrollo software basada en la integración entre desarrolladores y administradores de sistemas, que permite que los desarrolladores puedan enfocarse sólo en desarrollar y puedan desplegar su código en segundos. (para ampliar más ver [este artículo](https://www.paradigmadigital.com/techbiz/que-es-devops-y-sobre-todo-que-no-es-devops/)).
- **Docker:** Es un programa de código abierto que permite que una aplicación Linux y sus dependencias se empaqueten como un contenedor usando estos como máquinas virtuales permitiendo que las aplicaciones se ejecuten con total seguridad pero, a diferencia de las máquinas virtuales, son extremadamente más livianos (significativamente más pequeños) y modulares(capacidad de tomar una parte de una aplicación, para actualizarla o repararla, sin necesidad de tomar la aplicación completa) otorgándole mayor independencia.
- **End to end test:** Tipo de testeo del proyecto que consiste en probar todo el flujo del software desde el punto de vista del usuario final. Se realiza desde la interfaz de usuario y no desde el código y está enfocado en detectar posibles problemas que pudieran encontrar nuestros usuarios en su interacción con el flujo general del programa.
- Firebase (Bea)
- FP (Programación Funcional)
- Gitflow / Hotfix / Bugfix
- Graphic libraries: Recharts, Nivo, Victory
- HOC (High Order Components)
- Imágenes / contenedores
- **Integration testing:** En castellano *pruebas de integración*, permiten comprobar el comportamiento y posibles fallos en la interacción entre componentes en sí, y demás elementos del software.
- Jenkins / Pipelines
- Minify / Uglify / Terser
- Node / Deno (Eva)
- OOP (Programación Orientada a Objetos)
- Patrón de diseño en programación
- Patrón de diseño MVC
- **Polyfill:** Es un fragmento de código más o menos extenso que se utiliza para proporcionar una funcionalidad moderna (CSS, HTML, JavaScript) en navegadores antiguos que no lo admiten de forma nativa. En la mayoría de los casos, los polyfills están escritos en JavaScript, pero se pueden usar otros lenguajes de programación de base para estos scripts de llenado. Polyfilla (masilla en español) es una pasta que se puede colocar en las paredes para cubrir grietas. 
- Prettier / Lint
- Prod version x Dev version
- Programación reactiva RxJs
- Pure Functions
- React - context
- React - ErrorBoundary
- React - Hooks
- React - Pure components
- Release
- **Redux:** Redux es un contenedor predecible del estado de aplicaciones JavaScript. Te ayuda a escribir aplicaciones que se comportan de manera consistente, corren en distintos ambientes (cliente, servidor y nativo), y son fáciles de probar. Además de eso, provee una gran experiencia de desarrollo, gracias a edición en vivo combinado con un depurador sobre una línea de tiempo. Puedes usar Redux combinado con React, o cual cualquier otra librería de vistas. Es muy pequeño (2kB) y no tiene dependencias.
Todo el estado de tu aplicación esta almacenado en un único árbol dentro de un único store. La única forma de cambiar el árbol de estado es emitiendo una acción (action), un objeto describiendo qué ocurrió.
Para especificar cómo las acciones transforman el árbol de estado, usas reducers puros.
En vez de modificar el estado directamente, especificas las modificaciones que quieres que ocurran con objetos planos llamados acciones. Entonces escribes una función especial llamada reducer que decide cómo cada acción transforma el estado de la aplicación.
¡Eso es todo! 
Enlaces: 
https://dev.to/bouhm/react-redux-flow-terminologies-and-example-104b 
https://es.redux.js.org/
- Redux Saga
- Server side rendering
- **Snippets:** Fragmentos de código que suelen solucionar un problema que aparece de manera ocasional. Esos fragmentos se suelen anotar 
para usarlo en futuras ocasiones.
- Software versioning
- SPA (Simple Page Application)
- **Stagings:** (puesta en escena) El entorno de staging es una copia del entorno de producción ( el sitio web funcionando), en un servidor privado. Este entorno es una vista previa del trabajo donde se puede revisar, realizar test y cambios de una manera segura, sin que afecte a la web en uso.  Una vez aprobados los cambios se trasladan al entorno de producción. Migraciones de bases de datos, y actualizaciones de versiones se hacen en el staging. Flujo de trabajo “development-staging-production”.
- Storybook (Belen)
- Styled components / emotion
- TDD (Test drive developement)(Bea)
- Unity testing
- User-Agent
- **Versión beta:** Es una versión de software que ha pasado la etapa de prueba interna y ha sido lanzada a los usuarios para pruebas públicas. Suele ser un prototipo del producto final, inestable y que se lanza para que los usuarios puedan testar sus funcionalidades, detectar fallos y sugerir mejoras de cara a la versión final. 
- **Vue:** Se pronuncia "view" y también se suele llamar Vue.js. Es open source, como Angular y React. Imita a React en cuanto a al virtual DOM, cómo hace el render declarativo (automático, o ‘reactividad’) y la estructura a través de componentes que pueden ser reutilizables. De Angular coge cómo manipula el DOM a través de eventos. Es sencillo de utilizar, sobre todo si conoces React. Es escalable e incorporable a proyectos existentes que ya usen React, Angular o Jquery.
- Web components
- Webpack




