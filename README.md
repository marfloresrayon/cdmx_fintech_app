# Rediseño de aplicación bancaria

## Objetivos iniciales del proyecto

El banco más importante del país me ha encomendado, como UX designer, el proyecto de rediseño 
de su nueva aplicación móvil, donde sus usuari@s pueden visualizar sus gastos mensuales y llevar
a cabo metas de ahorro.  Es necesario llevar a cabo un diagnóstico del estado actual de la aplicación, 
evaluar su desempeño y proponer los cambios necesarios para optimizar el producto. 

## Problemas encontrados

El proceso de rediseño de esta aplicación implica el análisis del trabajo previo, el cual inevitablemente
tendrá áreas de mejora a ser resueltas con una nueva propuesta e iteración continua de la mano del cliente
y los usuarios. 

Para llevar a cabo este proceso es primordial tener el feedback de los usuarios, identificar los cambios 
y mejoras priorizando aquellos que agregan mayor valor a la experiencia de los usuarios y empatan con los 
objetivos del cliente. 

Después del análisis heurístico realizado a la landing page y al flujo actual de la aplicación desarrollada en 
iOS, así como el análisis llevado a cabo sobre la data proporcionada, se identifican los **siguientes problemas**: 

![Funnel de conversión](img/funnel.png)

* Durante los 6 meses que la aplicación ha estado disponible en el mercado el porcentaje de conversión entre la 
fase de adquisición (por medio de Facebook Ads) y la fase de activación (usuarios que han descargado la app y se 
han registrado para hacer uso) se traduce en un 0.0040903%. Lo cual sugiere lo **poco recomendable** que sería 
**duplicar el presupuesto destinado a generar anuncios de Facebook**. En cambio **se sugiere segmentar los anuncios 
de acuerdo al público que se intenta adquirir, especificando en los anuncios el sistema operativo con el cual opera
la aplicación y las funcionalidades que ésta contiene**. 

He identificado las **fases de activación y recomendación** como aquellas **prioritarias** para cumplir con los objetivos 
propuestos por el negocio, es decir, **fidelizar a sus cuentahabientes y fomentar el ahorro por medio de la aplicación**.

## Análisis heurístico

### Landing Page
El anuncio de Facebook lleva al usuario a la Landing Page de la aplicación, misma que contiene 2 CTA, el primero 
"Descárgala ahora" lo lleva a un formulario de llenado con la instrucción "Déjanos tus datos y recibe el link de 
descarga." Mismo que no se hace llegar al usuario, en cambio le redirecciona a una página de agradecimiento y
posteriormente a la App Store donde el usuario podrá descargar la aplicación. 

Hasta este punto **no existe un onboarding claro para el usuario, no se le informa en qué consiste la aplicación
y qué valor podría aportarle su uso.** Sobre el **branding, no se encuentran elementos diferenciadores de la 
identidad del banco al que pertenece la aplicación o de una experiencia distintiva que se sostenga a lo 
largo de la aplicación.** 

Verbalizaciones obtenidas durante el testeo con usuarios:
- *"Me gusta que la landing sea muy sencilla, que sea muy fácil de detectar, los colores son muy de banco,* 
   *van de acuerdo al banco."*
- *"¿Es en esta parte o en la de arriba? Veo que tienes dos veces el mismo botón para hacer la operación,* 
   *y el de arriba me dirige abajo."*
- *"Me gusta más que las cosas que son la función de la aplicación las vea apenas entre y eso no está.* 
   *Me invitas a descargarla pero no   me das el cómo hacerlo, controla tu dinero, pero algo que me diga de* 
   *una vez qué es lo chingonsísimo de una aplicación y por qué la tengo que bajar."* 

### App Store  
Dentro de la App Store nos encontramos con un eslogan distinto al usado dentro de la Landing Page, los colores y 
el logo de la aplicación son consistentes. Aunque es la séptima aplicación financiera, su rating es de 2.64 
estrellas lo cual denota una **falta de satisfacción con el producto, ya que este rating se basa en la calificación 
generada por cada usuario, por lo que me parece prioritario mejorar este rating** y cambiar la edad de uso sugerida
a 18+, ya que por el momento se encuentra en personas mayores de 9 años. Hasta este punto no ofrece más información
de la ya mostrada en la landing page, el onboarding no queda claro para los usuarios.

Verbalizaciones obtenidas durante el testeo con usuarios:
- *"Me estás dirigiendo a la app de la aplicación. Uso un teléfono de gama media, Android."*
- *"¿Si no tengo cuenta no importa? ¿Es exclusiva para Iphone?"*

### Sign Up
Dentro del sign up, de acuerdo al testeo realizado con usuarios, es necesario **mejorar la visibilidad del estado 
del proceso, prevenir posibles errores, reconocer y recuperarse de errores, y ofrecer ayuda al usuario** 
sobre lo que debe hacer en cada etapa del sign up mejorando los formularios y las instrucciones de llenado, 
así como la acción necesitada en uno de los pasos. 

Verbalizaciones obtenidas durante el testeo con usuarios:
- *"¿No hay un paso antes de hacer un registro? ¿O cómo sabe tu aplicación que soy un usuario del banco?* 
     *Te piden cierto registro en el banco para solo llegar e ingresar ciertos datos."*
- *"Agregar foto, está bien pero nunca lo hago, no le veo sentido para qué el banco lo tiene, suficientes* 
   *datos personales tienen, no veo qué uso puedan darle."*
- *"Creo que podría ser más inseguro que la felicidad que tendría el poner mi foto allí."*
- *"Me llegó un código en mi teléfono y debería salir aquí mismo. No había visto la letrita."*
- *"¿Número de cuenta es mi CLABE o qué? ¿Cuál cuenta, la de la aplicación o de mi cuenta bancaria?* 
   *¿Cómo sabe qué banco es?"* 
- *"¿Me llegó un mail de confirmación? Me gustaría, es mi cuenta bancaria, no tengo problema en meter* 
    *más mis datos, pero es la primera vez que uso algo así."*
- *"A lo mejor otra tipografía, se pierde un poco, yo soy muy ciega. No quiero poner mi foto, hacerlo más tarde.*
   *Eso de la huella me gusta, yo que soy muy paranoica, el que puedas poner tu huella para acceder a tu cuenta* 
   *me da más seguridad y confianza. Yo sé que no todos los teléfonos lo tienen, pero que tengan para identificarla* 
   *es un punto extra, da mucha confianza."*
- *"No sé cómo se llama esta app."*
- *"¿Por qué otra vez me dice que acepto los términos, son distintos cada vez? No me queda claro."* 
- *"No me parece ese avatar porque tiene género, o que lo tuviera de acuerdo a mi género, no me lo pide entonces*
   *no sé cómo va a saber."* 
- *"Me gustaría que todos los campos tuvieran datos dummie para saber cómo tiene que ser. Quisiera una ayuda* 
   *que me dijera cómo tiene que ser la contraseña, que me diga de qué tiene que estar hecha esa contraseña."* 
- *"Me abre el carrete, no pide permiso para acceder a mi carrete ¿puedo elegir la que sea? Si no lo lleno* 
   *ahorita espero que más adelante pueda hacerlo de manera fácil, vamos a hacerlo después, ah no puedo,* 
   *porque en tu flujo de navegación no puedo arrepentirme."*
- *"¿Llené mi nombre? ¿De dónde lo saca? ¿De sus datos de cuenta?"*

### Patalla de inicio. HOME
Muestra un mensaje de bienvenida con el nombre del usuario, una imagen de la tarjeta del mismo ocupa 3/4 
de la pantalla, una campana en la esquina superior derecha anuncia las notificaciones de la app, el saldo 
disponible se encuentra abajo de la tarjeta sin especificar la moneda o un desglose del mismo. 
En la parte inferior se muestra un **botón con tres puntos que da acceso al menú con los distintos apartados
de la aplicación, mismos que no conoce el usuario**, en la navbar se encuentra un menú hamburguesa que 
incluye la foto del usuario, si la ha agregado, además de su nombre, la fecha y hora de su última conexión. 
**Hasta este punto no se ha ofrecido un onboarding para el usuario.**

Verbalizaciones obtenidas durante el testeo con usuarios:
- *"Estaría bien un ícono donde pudieras regresar a la pantalla principal, porque con el atrás llega* 
    *un momento en el que te sales de la aplicación."*
- *"Los tres puntos no me dicen realmente qué son, no me agradó. En vez de ser unos puntos, algo que de*
   *a entender que te lleva o te regresa a tu menú."*
- *"¿En el menú no tienes nada verdad? El menú está vacío, sólo puedo ver mi cuenta. Pensé encontrar editar* 
    *mi perfil, notificaciones, ayuda en línea, teléfono de la aplicación por si hay algo que no esté viendo* 
    *aquí y me pueda comunicar con mi banco, no tenga que ir a buscar en internet el número de mi banco, o*
    *algo así como preguntas frecuentes."*
- *"Pensé que el botón (de tres puntos) era para arrastrarlo."*
- *"Monto total en la parte de inicio, a lo mejor cuenta con la parte de ahorro, que aparte diga la *
   *cantidad real para gastar y la real total que se tiene."*
- *"Menú hamburguesa no hay nada que me sea útil de aquí. La última conexión no me importa. Me gusta que me* 
   *ponga la tarjeta, me hace claro que esta es mi tarjeta."*
   
### Movimientos
Se muestra el saldo disponible para el usuario sin especificar la moneda, **existe un buscador del cual no 
puede hacerse uso dentro del prototipo, no quedan claros cuáles son los parámetros para realizar una búsqueda.**
Pueden visualizarse los gastos por mes, se diferencian los gastos con color rojo y en verde los depósitos, 
puede realizarse un desglose del cargo donde **la app se comunica con el usuario en inglés y español.**

Verbalizaciones obtenidas durante el testeo con usuarios:
- *"Movimientos, me gusta la transición, puedo elegir el mes, el saldo disponible me gusta."*
- *"Esto sí es muy importante, los movimientos como cuando uso tarjeta, no llevo un control de lo que gasto,*
   *está padre ver en qué gastaste, de hecho hasta ahí te puedes dar cuenta en las tonterías que gastas tu dinero."*
- *"Verificar si hay un cobro que no reconozcas para saber cuándo y en qué tienda se realizó. Esa parte me gusta."* 
- *"Ponen el gasto como en rojo negativo, me causa un poco de ansiedad ¿Es tarjeta de débito? ¿es un saldo a favor* 
   *no? Está bien la diferencia de color, pero no sé si sea la opción el rojo, diferencia de ganancia y pérdida."*
- *"Movimientos ¿por qué está en medio (el botón de 3 puntos)? No sé por qué está en medio, no puedo regresar ¡ah!"*

### Ahorros
Al igual que en cada uno de los apartados **1/4 de la pantalla se encuentra ocupada por una imagen y color** que 
los distinguen, se encuentra un buscador que tampoco aclara la manera en la que se puede realizar una búsqueda.
**Cada meta de ahorro muestra la cantidad meta y el porcentaje logrado**, además de un botón con un ícono de 
monedas con la leyenda **"Crear cuenta" el cual no aclara al usuario su función de crear una nueva meta de ahorro**, 
al hacer clic muestra un formulario con los datos de título, donde **por primera vez el usuario puede agregar
texto y emojis, monto**, **fecha que no aclara si es de inicio o finalización**, y periodicidad, sólo **al terminar
de llenar los campos el botón de "Continuar" se enciende**. 

**En la siguiente pantalla la app se comunica con el usuario con texto y emojis, se le informa al usuario 
sobre la cantidad que ahorrará, misma a la que no ha accedido en ninguna parte del flujo**, así como la 
cantidad de semanas en las que cumplirá su meta. Por otra parte se le informa al usuario cuándo y en qué horario 
se realizará el ahorro, así como la cuenta de la cual se deducirá. **No indica la moneda del monto total a ahorrar
o una opción donde poder modificar los datos proporcionados en caso de error o cambio de opinión**, sólo
muestra una opción afirmativa a la pregunta "¿deseas confirmar?" Después de crear la meta de ahorro **no existe
opción para poder suspenderla momentáneamente, por cierto periodo de tiempo o cancelación de la misma.** 

Verbalizaciones obtenidas durante el testeo con usuarios:
- *"Me gusta que cambia el fondo para diferenciar cada apartado."* 
- *"Son como metas específicas para cosas, crear una cuenta ¿cómo crear una cuenta? ¿es un nuevo ahorro o qué?*
   *No me parece que se debería llamar cuenta, sino crear meta, me gusta que el botón está apagado cuando lo lleno.*
   *Porque para mí es cuenta de dinero."*
- *"Yo no decidí eso, porque no tenía claridad de que fueran a ser 75 pesos, no me gusta cómo me habla la aplicación.* 
    *Me gustaría que me dijera para llegar a tu meta tienes que ahorrar 75 pesos en 16 semanas, me gustaría que me *
    *presentara la cantidad que voy a ahorrar según la periodicidad."* 
- *""*

### Gastos

Verbalizaciones obtenidas durante el testeo con usuarios:
- *""
- "Si es solamente de budget no me da tiempo de llevarla, si estás tranquilo la llevas, pero entras en un rush 
   de trabajo y olvidas usar la aplicación. Cualquier cosa que se maneje lo más solita posible y me diga qué hacer, 
   más que tener que llevar todos los días los gastos."

A continuación las herramientas metodológicas usadas para comprender las necesidades del negocio y los usuarios. 


| Herramientas metodológicas (valor) | Finalidad |
|--|--|
|Entendimiento del problema, la industria y el contexto (15)| Entender el contexto y necesidades del negocio, así como los objetivos del producto.|
|Entrevista con el cliente (25)  | Establecimiento de metas y objetivos. Feedback sobre el proceso de diseño. |
|Benchmark (20)  | Revisión de features y valor agregado de la competencia. |
|Entrevistas con usuarios (60)  | Entrevistas con usuarios para obtener insights accionables, profundizar en sus motivaciones, necesidades y preocupaciones. |
|Flujo/Árbol de contenidos (20) | Flujo de navegación de la aplicación, conocimiento de sus contenidos. |
|Card Sorting (15) | Entendimiento del modelo mental de los usuarios para plantear una arquitectura de la información acorde a su razonamiento. |
|Testeos de prototipos (60)| Sesiones de testeo con la solución propuesta con 5 usuarios. |
|A/B Testing (50) | Testear dos versiones de un elemento para medir cuál funciona mejor con 5 usuarios. |
|Sketching y Wireframing (30) | Elaboración de prototipos de baja y mediana fidelidad. |
|Prototipado de alta fidelidad (80)| Elaboración de prototipo de alta fidelidad con el diseño propuesto. |
|Prototipado clickable (85)| Elaboración de prototipo de acuerdo al flujo de usuario propuesto. |
|Pruebas de usabilidad sobre prototipado (60)| Testeo del rediseño de la aplicación, identificación de pain y gain points del diseño propuesto para una siguiente iteración. |
|Total| 520 |

## Recomendaciones de próximos pasos para el banco con respecto al app 
### Qué modificaciones se deberían hacer
### Cuáles deberían ser los próximos desarrollos
### En qué se debería invertir el presupuesto de marketing

## Prototipo de alta definición con cambios y desarrollos nuevos
### Link de Marvel Hand-offs para compartir los diseños con desarrolladores

## Video de Loom de máximo 5 minutos
Explicar los puntos indicados en el README.md y hacer un demo de la solución propuesta.

En las otras carpetas del repositorio o en las carpetas de Google Drive podrás agregar los documentos complementarios que sustenten tu proceso.

### Anexos

**Hacker edition**
* Lista cuáles fueron tus aprendizajes durante el proyecto 1 y en qué cosas te gustaría mejorar durante el proyecto 2. Al terminar el proyecto 2 vuelve a esta lista y chequea cómo te fue con esos retos, ¿los cumpliste? Muestrános esta lista y esta reflexión en un documento adicional (en el formato que prefieras).
* Investiga sobre chatbots y sustenta si sería bueno incluir uno en alguna parte del journey del uso del producto. Si crees que un chatbot añadiría valor, prototípalo usando Botsociety.
* En lugar de usar Github para documentar tu proceso de trabajo, documéntalo en su propia web (Google Sites).
* Escribe un post en Medium contando tu proceso de investigación.
