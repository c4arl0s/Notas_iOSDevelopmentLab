Utilizar XIB para poder dicidir nuestro codigo.
por defoult todos los parametros de las funciones son constantes

stack de compiladores.

var = valor = 4

func cambiaValor(param: inout int) -> Int {
	param += 1
return param
}

print(cambiaValor(param: &valor)
print(valor)

Comparacion con C

int valor = 5

int cambiaValor(int *param){
	*param = *param +1;
	return *param;
}

cambiaValor(&valor);

int *param
param = &valor

# structs in swift

1.- swift autoinicializa una struct
2.- podemos decirle a una estructura que se inicialice
3.- son tipos de datos que van por valor
4.- no manejan herencia.
5.- permite tener metodos
6.- permite tener variables computadas.
7.- las propiedades dentro de una struct son inmutadbles

 struct Alumno {
 var nombre : String
 var edad : Int
 var carrera : String {
 willSet {
 			print("Esre sera el nuevo valor \(newValue)")
 				}
                  didSet {
                  print("este fue el valor asifnado \(oldValue)")
              }
      }
 
              }

# Class
1.- son tipos de datos por referencia.
2.- herencia unica
3.- en java la herencia multiple se esconde en .... interfaces.
4.- optimizacion de memoria
5.- sobre carga de método.

# tuplas
1.- son inmutables

# arrays
1.- mismo tipo de datos

arrays
1.- los arrays son genericos
2.- son del mismo tipo
3.- importa su orden.

# En swift todo es un objeto, en exception las tuplas que no son mutables.

diccionarios.

1.- son conjuntos de pares, cadena : entero,  llave:valor.
2.- los diccionarios no pueden hacer para guardar datos ordenados.
Design patterns
Agile mythologies

Elexir

German, parte empresarial, lenguajes de programación, El programador pragmatico- (arboles vs pilas)
Luis, variables en inglés, código en ingles.
Norberto: investigar Rust. 

Elixir de 5 a 7 en la semana, curso gratis. Conocer Elixir.

Norberto. Conoce varios lenguajes de programación. Compildores, memoria, sistema operativo. Maestro en ciencias.

========
Marduk.fi@
=========

Ejercicio:

empresa de seguros

Alta de poliza de seguros, petición por sistema, se ha detectado que crece el riesgo, seguros para Uber 
Detectar cuando se trata de un carro Uber o auto de lujo, clásico,
Se ha hecho un análisis de marcado, peticiones , evaluar 9200 unidades al mes. 
El proceso se detona a partir del alta. Mpnt e la factura, año del motor, detonar alerta, proceso de revision extra.
Por medio de fotografías o ciertas areas del motor, se pueda integrar un reporte fotográfico. Se revisan estos datos para negar la póliza.

Partes del motor, desgastes, numero de serie del motor. Kilometraje. Detectar si es Uber.

Faltantes.
Que no haga fraude,  validar las fotos y la privacidad de la información.

Siempre pregunten, que tipo de cliente es el que esta haciendo la requisición.
2 meses 

===

1.-software tiene mucha dependencia.

* fusion, nuevo sistema operativo.
* swift esta creciendo dentro del mercado de desarrollo para tesla, mercedez benz, etc.
* filosofia vertical, el logo no se expone, el piso es especialmente traido de san francisco.
* lenguajes y herramientas nativas:  
* El papa de Objective-C esta trabajando en Google para android.

Flujo de de

ANALISIS
- mercado, usuarios
tiempo
costos
requerimientos
DISEÑO
- maqueta de interfaces
- organizacion de tareas
- arquitectura de codigo.
- Servicios
- modelo de negocios.
- mercadotecnia. 

Que es codigo espaguetti ?
cliente servidor !
Distribuicion: pago de 99 USD 

Investigar Cordova.?

LEGAL 

Investigar que es una VPN.
Bajar estadistica: asociacion de internet.mx

LLVM low level virtual machine. 
swift
C
C++
C#
gcc

Cargador ABI - Application Binary Interface.

Proyecto mazapan.

cammel notation			laCasaDeJuanito
squeleton notation	la_casa_de_juanito_que(?)
snake notation			la-casa-de-juanito-que(?)

nombres de metodos, funciones y variables

estudiar tuplas en swift.

infografia de desarrollo nativo, nativo y crossplataform.
 
framework !
interpolacion     " hola \(nameVariable)"

concatenacion e interpolación.
\"Comillas"\""

Use core data, cuando deseas almacenar informacion.
preguntar diferencua entre version and build

hector zarate, spotify

=============
# Filosofia en swift: Todos tienen propiedades y métodos, todos !!!

enumerador, estrutcura o es un objeto ??? todo en swift

# A veces es un objeto puede ser muy complejo y es por eso que crea una estructura, es lo que debemos definir.

=============

el tipo de datos string, cambia mucho entre versiones,

Ver propiedades calculadas, las propiedades se actualizan, cuando actualizas las propiedades

las estructuras estan vitaminadas o con esteroides en swift, no heredan nada,

SO and dispositivos.

high sierra entorpece los equipos con disco duro mecánico.

nos muestra video de pixeles.

==

arreglos
funciones,
estructuras

===

herramienta sketch, genera iconos apra que puedan ser desplegados en su aplicacion.

trabajar en pdf, trabaja con vectores.

notas: general VM

bajar marzipan 

marzipan => LLVM ABI vs WINDOWS 

# programacion oreintada a protocolos

GPA nueva manera de cuidar sus datos, 

con los conocimientos basicos podemos salir a las empresas que maquilan aplicaciones.


servidor de integracion continua.:wq


usar gitflow para procesos en los que no hemos automatizado
usando bitrise podemos automatizar las tareas de pruebas y minimizar el worflow
aplicacion musica a alamofire para quitalr el URLSession
register nib del UITableView cell.



Inside the machine Book
Meldown and Spectre, branch predictivo    if( ) else { } Cuesta como 1500 pesos
Las ejecuciones se guardan en chaché.
La seccion de data esta bloqueada contra escritura, por si alguien quiere modificar el programa.
Las variables estaticas estan en el heap.

Creating Secure Applications.

# what is security ?
CIA triad

+-----------------+-----------+--------------+
| Confidenciality |           |              |
+-----------------+-----------+--------------+
|                 | Integrity |              |
+-----------------+-----------+--------------+
|                 |           | Availability |
+-----------------+-----------+--------------+i

# Security Controls
+----------------+----------------+
| Identification | Authentication |
+----------------+----------------+
| Authorization  | Accountability |
+----------------+----------------+

# Security Principles

+-----------------+------------------+----------------------+
| least Privilege |                  |                      |
+-----------------+------------------+----------------------+
|                 | Defense in Depth |                      |
+-----------------+------------------+----------------------+
|                 |                  | Compartmentalization |
+-----------------+------------------+----------------------+

# basics

+-------------------+--+--+
| Steganography     |  |  |
+-------------------+--+--+
| Cryptology        |  |  |
|     Cryptography  |  |  |
|     Cryptanalysis |  |  |
+-------------------+--+--+
| Encryption        |  |  |
+-------------------+--+--+

Code & Cipher
	Transposition & Substitution
Cryptosystemi: Piezas de lego

Libro the Code Book: The Science of Secrecy from Ancient Egyp to Quantum Cryptopgraphy.

+-----------------------------------+
| Pseudo Random Numbers             													|
+-----------------------------------+---------------------------------------------------------------------------------+
| Digests (SHA-3) : FUnciones que no tienen inversa (no se pueden cifrar con estas por que no tienen funcion inversa) |
+-----------------------------------+---------------------------------------------------------------------------------+
| Symetric Keys (AES, estandar americano, algoritmo recomendado para cifrado simetrico) Cuando la llave para cifrar y descifrar es la misma                               |
+-----------------------------------++--------------------------------------------------------------------------------+
| Asymetric Keus (RSA) LLave publica y privada              |
+-----------------------------------+
| Certificates (X.509)              |
+-----------------------------------+
| Key Derivation Functios (PBKDF2)  |
+-----------------------------------+

"las contrasenas jamas se guardan, se guarda la digesyion de la contrasenia"
no tiene funcion inversa.
para intregridad de los datos.
hace poco salieron de colisiones de SHA-2
md5 ya esta destruido.
Se recomienda SHA-256 o SHA-512
Un sha-256 es lo mas recomendable.

Simetric keys, inconveniente de transportar la llave.
asymetric keys, mas lento para descigrar que AES. Existe otro que se llama curvas elipticas, tambien son asimetricas.

# Cryptosystema.

Certificados. Adentro vienen llaves publicas y privadas. Quien autentica que el certificsdo es valido, viene datos personales.

Llaves o tokens

iOS Fundamentals

iOS Platform Security
Users upgrading their SW
Developers building secure apps.

CommonCrypto: viene todas las llaves, numeros pseudoaleaotorios, funciones de direccion, estan ahi. No esta sencillo como deberia de ser.
keychain: es una vil base de datos de SQlite. Por cada aplicacion que se instala en el telefono, se crea yna tabla de SQL.
data protection: 
secure transport: 


Sanboxing

application


var clasifications: [Clasification]
var items: [[Mark]]


# para guardar los modelos de valvulas usar el protocol NSCoding


norberto, 1993 al 1996, 
misael Perez es un experto en coregraphics. empresa Bunsan.

@misaelpc
guthub misaelpc
gitlab misaelpc

como probar la aplicacion automaticamente ?


# prueba unitaria
# prueba de interface
validar de estilo swiftlint


### las pruebas unitarias van enfocadas al codigo, cada linea puede probarse.
las de interface puedes generarlas tu o lo puedes hacer junto con el equipo de testers.

https://gitlab.com/misaelpc/bunsan_members
https://github.com/realm/SwiftLint
https://app.bitrise.io/users/sign_up
builds de manera interna.

inspeccionando 

pueden haber vistas sin controlador.

hacer una subclase con el xib para reusar vistas o en otros casos las celdas prototipo de una tabla.



Core Graphics
quartz 2D programming guide
painters model: drawing order
the graphics context: printer, window, layer, bitmap, PDF
Sistema de coordenadas: es diferente al del iphone. CoreGraphics nos ayuda a que se use el sistema del iphone, y nos hara el cambio de coordenandas automaticamente.
.
Norberto recomienda Designed for use
Treat: representa el flujo de ejecucion.

stack trace: 

# Core fundation esta hecho en C
# UIKitCore esta hecho en objective-C

Razon para no usar prints: se contamina la historia del repositorio con basura. Si insertamos 10 prints, hay diez cambios, y no podemos notar cual es el cambio.

. Si insertamos 10 prints, hay diez cambios, y no podemos notar cual es el cambio.
# Usando breakpoints no tenemos que volver a compilar.
Usando prints tenemos problemas de performance. 

debugger: 

move breakpoint 
share breakpoint en un proyecto

hay varios tipos de breakpoints
DataSource for test.
network layer
en el stack van los enums, estructuras.
clases van en el heap.
does not recognize object, no encuentra el metodo, por lo que no incluidomos el UIVIewcontroller.
o escribimos mal el nombre.


# CICLO DEL RUN LOOP

while () {
revisarCola()
rutearEvemto()
ejecturaViewController()
marco vistas que tengo quepintar()
lasvuelvoaPintarVistas()
liberoLaBasuraMemoria()
}

tambien pueden ver autorelease anidados, una vez que entra en uno, libera, pero no se entera el primer autorelease.

# Clase de Norberto.

- integracion con Objective-C
- debugger.
- apuntadores 
- GDB
- CLANG
- eventos
- arquitecturas, MVC
- criptografia.
- instruments
- core data
- Sistemas operativos y redes.
- Servicios.
- generics

Objective-C tenia algunas restircciones de aquellos años.
Graydon escribio Rust, para reemplazar C y C++. Ahora entró a apple y trabaja en el equipo de Swift.

# Emuladores, Simuladores. Diferencia entre ellos.

- Compiladores:
- LEXER, analizador lexico.
- PARSER, analizador sintactico
- analizador semantico  Ejemplo:    if(false){ micodigo },   it make sense ?
- OPTIMIZADOR. funcion() {f1; f2; f3}  inline, jumps. Hay banderas de optimizacion. (performance -> inline => crece el binario): se llena la cache, no cabe y baja el performance, tiene que ocupar memoria en ram. 1000x, se trada mas en traer los datos de memoria.
- LINKER (juntarlo en un solo binario, mach (binario iOS)), archivo ipa es un zip o tar, en donde vienen todos los assets.
- Package manager.

Cada etapa reporta errores diferentes.
Sabiendo quien reporta el error, tenemos una ventaja.

Integracion continua, cuando estamos haciendo proyectos, el tema de pruebas. es vital que se este viendo en todo momento.

Objective C y swift y verificar el tamaño de los ejecutables.
Proceso: es una estructura de datos a nivel de sistema operatuvo. Tiene ciertos metadatos, almacena un programa. Es un mecanismo

metadatos: 
priodad
estado
esta en pausa etc.

tamaños de procesos en Sistemas Operativos.
en macOS	8MB
linux			4MB
windows 	2MB

tread tambien es una estructura de datos.
en macOS	4MB
linux			2MB
windows 	1MB

Cuesta tiempo para crearlos.

para entender el modelo de seguridad de iOS es necesario conocer un proceso.

procesos aislados y por seguridad. 

Modos en los que puede correr el hardware.

Rings (anillos) Es del hardware.

modo0	hipervisors
modo1 maximo privilegio. Aqui corre el sistema operativo y puede controlar la RAM
modo2
modo3 usualmente aqui ejecuta el usuario normal
modo
La memoria virtual es la que mapea con la MMU para saber accesar a la memoria RAM.
la memoria virtual solo trabaja con la RAM, la cache funciona de otra forma.

en iOS no hay swap.
android tiene swap.
En iOS si se queda sin memoria, mata las aplicaciones bajo un criterio.

Como gestiona el sistema operativo los procesos. 1 se congela y le da permiso de usar la CPU al proceso A, y lo deja accesar (trabajar) 

erlang es prograado en erlang
Conferencia 1 diciembre de elixir.

Proyecto con Erlang del internet delas cosas: Build with Nerves.
webserver: cowboy
pheonix para crear web services.

navegar hasta ~/Library/Developer/Xcode/DerivedData/ProjectInObjectiveC-gaszpevxwduoahaftjenvqrclsbd/Build/Products/Debug-iphonesimulator

aun no hay compatibilidad Binaria en Swift, por eso tiene que cargar los dylib
para la compilacion en swift tiene que cargar todas las bibliotecas que depende.
, por eso tiene que cargar los dylib
para la compilacion en swift tiene que cargar todas las bibliotecas que depende.
Problemas de compatibilidad Binaria.
swift ocupa mas memoria en RAM.

LLVM: es un tool kit para construir compiladores. dentro de el incluye generadores de codigo para diferentes arquitecturas de procesadores. PPC, x86, ARM. ademas incluye una definicion de BitCode (especie de ensamblador). hay dos etapas de generacion de codigo. la ultima es el Bitcode.

Swift tiene como 3 niveles de optimizacion.

A nivel de bitcode tambien tiene optimización.

ARM32
ARM64, en este binario metieron cosas de cryptografia.

simbolo no reconocido, tiene que ver con el linker.

Todas las bibliotecas tambien tienen que estar en ARM64.

Que sucede cuando le das tu tapped a la pantalla.

ps -fea | grep Window
   88   199     1   0 Sun12AM ??       215:28.90 /System/Library/PrivateFrameworks/SkyLight.framework/Resources/WindowServer -daemon

windowserver recibe todos los eventos.

los eventos pueden ser el teclado, el cursor. 

todas las aplicaciones tienen una cola de mensaje o un buzon.

wimdow server deposita el proceso en la cola.

algo tiene que checar el mailbox, y es el UIApplication. Solo crea una instancia por cada aplicaicon.

el applicationdelegate es el chalan de UIApplication.

AppDelegate hereda de UIResponder (recibe la logica de como recibe eventos y los procesa)

UIView hereda de UIResponder.
UIWindow hereda de UIView

meter el main en el proyecto de swift y que se ejecute.

emulador: 
simulador:

ISA: instruction set arquitecture.

UIKit

controlador de vista delega funciones.
brain-ding the strategy. francisco J Serrano.
facebook google twitterr
como manejar cache ?

Core Location
Mapkit
Core Motion

server de testing.
Pruebas de integracion son las pruebas UI Text
keychange pod
el sensro de presion no es de core motion

Core Motion:

acelerometro, giroscopio, 

tarea moral, ubicacion en grados.

GET
POST
PUT
DELETE

TOKEN
OAUTH		TWITTER, servidores.

tres ejercicios de tarea:

restaurant
todo list
scrooll view

leer gran central dispatch

import PlaygroundSupport 
PlaygroundPage.current.needsIndefiniteExecution = true
extension URL {
    func withQueries(_ queries: [String: String]) -> URL? {
        var components = URLComponents(url: self, resolvingAgainstBaseURL: true)
     			components?.queryItems = queries.flatMap { URLQueryItem(name: $0.0, value: $0.1) }
        return components?.url
    }
}
let baseURL = URL(string: "https://api.nasa.gov/planetary/apod")!
 
let query: [String: String] = [
    "api_key": "DEMO_KEY",
]
 
let url = baseURL.withQueries(query)!
let task = URLSession.shared.dataTask(with: url) { (data,
response, error) in
    if let data = data,
        let string = String(data: data, encoding: .utf8) {
 
        print(string)
    }
}
task.resume()XIB para reutilizar codigo

Storyboards: flows

Autolayout: 

Por codigo: 

los objetos se hacen en xml.

Por codigo: 

dismissPresenter viene un complition closure, 

cada quien trabajar en xib 

:wq


el proyecto que crea:
borrar los storyboard y viewcontrollers
aggrega CocoaTooch, view controlleres, los nombra y tambien tableviewcontrollers. 
Despues se va al appdelegate e ingresa codigo para poder llamar

// 
self.window = UIWindow(frame: UIScreen.main.bounds)
        let viewController = FishesTableViewController(nibName: "FishesTableViewController", bundle: nil)
        let navController = UINavigationController.init(rootViewController: viewController)
        self.window?.rootViewController = navController
        self.window?.makeKeyAndVisible()
        return true
// 

// nota acerca de como cambiar de vista al dar push
navigationController?.pushViewController(viewController, animated: true)

closures para tareas sincronas.


Proceso

Secciones del proceso:

DATA	es el binario
STACK	lleva el control, el flujo de la ejecuciion del programa. En el stack se guarda todo aquellos datos que sabemos 
HEAP	dinamica

start es la primer funcion que se manda llamar en cualquier programa en C.
stack:  
64 bits		tamaño del apuntador 
32 bits 

tipos de manejo de memoria.
- manual
- conteo de referencias. POr cada apuntador que apunte a un objeto, se incrementa un valor 1,2,3. Si el valor es 0, se libera en memoria. Se realizar en tiempo de ejecucion. Swit y Objective-C tienen este tipo.
- ownership o pertenencia. Rust. Mientras tu sigas estas reglas, yo tengo mi mecanismo para liberar memoria. Se realiza en tiempo de compilacion, se rumora que 
- Collector de Basura.

el singletone es una variable global.


- conteo de referencias
* alloc
* retain (+)----> release (-)         para evitar un memory leak retain = release
	aquel que haga un alloc o un retain ese es responsable de hacer el release.


weak:		
strong:	

Ciclos de retencion.


Ciclos de retencion.



Notas 24 de agosto 2018.

- Leer el libro para hacer examenes prototipo para la certificación. Resolver problemas.
- Dar empuje para poder crear el proyecto.
- El proyecto debe resolver un problema social.
- Opcionales.
-  

		struct Book {
			let name: 
			
* cualquier otro lenguaje puede hacer identificador null.

* en este tipo de programación no es una ejeccion lineal, si no que puede ocuirrir eventos asincronos y cambiar las variables.

creacion de ciertas instancias.
inicializador falible (o que puede fallar)

Toddle example, write the code.
Type inspection with is
type casting with as?  			si falla podemos regresar un opcional.
Type any

var items : [Any] = [5, "bill", 6.7, Dog()]
// Dog() es un inicializador de tipo Dog.
if let firstItem = items[0] as? Int {
		print(firstItem + 4)
}

* guard 
* guard with optionals 

Tarea: leccion 3.9 Construir flujos de navegacion Simple.

mañana tablas y persistencias de datos.


Cyclical References:
- ciclos de retencion: evitarlos.
En swift es muy facil generar ciclos de retención con los closures.
Analyzer puede detectar estos ciclos de retención y podrá reportarlos.
Otra herramienta que no falla es el instruments y que puede detectar ciclos de retención.
Parent-Child Relationships: when objects are arranged in parentChild relationships, parents should own the childre, but children should not own the parents.
Avoiding retain Cycles
Dialog tiene que mandar el release a NSarray
Por default si no se especifica weak, son strong.
Manual Reference Counting
	before ARC, the programmer was responsible for managing an Objects, reference counts.
// essential messages inherted from NSObject:
[anObject retain]; 
[anObject release];
tanto swift como Objective-C usan ARC.

Class AppDelegate: IUResponder, UIApplicationDelegate {
	}

* la vista raiz es negra.
* C no es concurrente. (solo con licencia)
* Python no es concurrente.
+ Elixir si es concurrente.
* Herencia multiple no existe en swift. 

protocolos: 

- a veces nos permite ejecutar metodos

- nos permite acce


metodos:
pktpub.com

JSON : Java Script Object Notation


let jsonEnconder = JSONEncoder()
if let jsonData = try? jsonEncoder.encode(godin1), let jsonString = String(data: jsonData, encoding: .utf8) {
print(jsonString)
}

protocol NombreCompleto {
procesos asincronos y concurrentes.
no pensar de manera secuencial.
no hay que meter muchos pots.

API
htpp://wather.com/get/today
XML
JSON (javascript Object Notation)

{ type: "sunny"
	
}

crea bases de datos ficticias: mockaroo.com




fastlane: scripts en ruby.
dio de alta 3 testers para probar la aplicacion.

estudiar ruby y elixir para backend, microservicios.
hacer pagina gitHub
Metodos para cache.

MD5
SHA1
SHA2
SHA256
BASE64

git usa SHA1

usar un pod de objective-C para no hacer tanto mantenimiento.
no usar takens dentro de UserDefaults.

dineros y centavos en enteros.
viistar la pagina 0.300000000000000004.coviistar la pagina 0.300000000000000004.comm

CoreData no dará coredata
luis usa SAMkeyChain
userDefaults ahi se ponen las cinfiguraciones del usuario.
en keychain guardar pedazos de información.

var url = FileManager.default.urls(for: SearchPathDirectory, in: .userDomainMask).first!
let subfolder = "my-subfolder"
url.appendPathComponent(subfolder)



Se vio unidad 6, brevemente.

closures
extensiones
protocolos
herencia circular.
Herencia de java.
herencia -> por eso C creo las estructuras, y evolucionó a C++

void suma (int x, int y) {
}
void suma (int x, int y) {
}

swift usa las etiquetas para ejecutar las funciones.

((UIAlertAction) -> Void?)


var cadena = "holla"
type(of: cadena)
cadena = "Hello"
//cadena = 8
let saludo="good morning"
print(saludo)
//saludo = "como estas?"
// python java y php si lo hace pero es interpretado.
// segundpo punto en swift todo es un objeto.
"alumnos".underestimatedCount

/* hola mundo
    no todos son ingenieroos
 */
dump("hola mundo")
// % modulo
// + - * / %
3%2
3+4 // operador binario
/*
 string
 int
 double
 float
 bool
 */

var numero = 4 / 3
type(of: numero)
print(4/3)

var otro = 4.3
type(of: otro)
print(otro)
// sobrecarga de operadores !!

// Shift left
1 << 3
// Shift right
1 >> 3

(2.0).squareRoot()

// como se declara un tipo de dato
var num : Int = 3

var sonrie = "😄"
print(sonrie)

var contador : Int = 0
contador += 1
contador -= 1
contador *= 3
contador /= -2  // binario, unario

var entero : Int = 100
var decimal : Double = 12.5
entero = Int(decimal)
var letra : Character = "A"
print(letra)

var cadena : String = "Esto es una cadena"

// Concatenacion
var mensaje = "hola" + "me llamo: "
var nombre = "German"
print("\(mensaje) + nombre)














api flags.
completion
los protocolos trabajan con swift
datasource trabaja con cocoatouch.
la multiherencia no existe en swift
programación orientada a protocolos.



crear licencia
hacer commits
incluir commits
se pueden crear commits con fechas anteriores a las actuales.
hicimos pruebas implementando crypto SHA1,
TEMARIO

que es UX
diseño centrado en el usuario
diseño para moviles
patrones de diseño de UX

Que es UX ?
todo lo que experimenta una persona al interactuar con un prodyctor o servicio

Interaccion Designer
UX designer
Visual designer
information architect: 
usability analysis
user research

UI	User interface
UX	user experience

UX es respossabilidad de todos
Una buena experiencia de usuario ocure cuando todos los miembros de un equipo trabajan en hacerla realidad.

La importancia del enfoque de UX

- wireframing permite enfocarnos en UX primero y panorama General sin meterle a detalles de la UI
- Cual es la tarea que el usuario va a realizar?
- Cuales son los pasos que el usuario debe realizar para completar la tarea ?


Puntos para discutir el diseño de una app.

Selecciona una aplicacion que te guste mucho
que es lo que hace esa app ?
que es lo que amas de esa app ? Enfocate en aquellos aspectos visuales y no visuales de la app.

4 myths about Apple Design, from an ex-apple designer.

Diseño centrado en el usuario.

- quien es el usario final de mi aplicacion. 
	Ingenieros de Proyectos, Ingenieros de mantenimiento.

- para quien estamos creando esta aplicacion.
	*Firmas de ingenieria. Deparmanentos de mantenimiento.
	*Ingenieros de ventas.
	*Product Champions.


- diseñar aplicaciones para un tipo especifico de usuario o personas y casos de uso.
- como crear una lista de features que cubran las necesidades de mis usuarios y los casos de uso que identifique previamente.

Pizza App.
	
* 3 features para que una app funcione.

	1.- presentacion eficiente de la lista de diferentes sabores de pizza.
	2.- nuevos productos, descuentos, y promociones en notificaciones.
	3.- Formas de pago rapido.

Estrategias para elegir los top features para tu app.

Combinar features o ideas -> cuando tratas de complacer a todos los usuarios terminas complaciendo a ninguno.
elegir una idea -> el usuario no eres tu.

Parte tecnica
parte enfocada a usuarios, empatizar usuarios.
Parte del tema del negocio.

BIAS APPROACH

APIs
viabilidad tecnica    DEVELOPER   <> tuú <>  Designer       Empatizar con el usuaio. To,ar en cuenta restricciones.

user != tu

Como empieza tu dia 1 en un proyecto ?

Hago una lista de features
Empiezo a programar
Investigo las APIs que voy a utilizar
Hago mockcups de la UI
crea wireframes de baja resolucion -> 
pienso acerca de las necesidades de mi usuario.

wireframes: permiten crear estructuras que representan en una pantalla a nivel de cajas.
mockup: ya viene empatado en la plataforma en la que vas a desarrollar.

PERSONAS
Proxy para un grupo de usuarios actuales de nuestro producto y para quienes nuestro proceso de UX sera optimizado.

CASO DE USO.

Cuando + Donde + Como una persona utiliza nuestro producto para cumplir con una tarea.

Persona Luis Hernández

-Estudiante de universidad
-No tiene mucho dinero $$
-VIve en un dormitorio
-No tiene auto
- no sabe cocinar.

Cuales de las siguientes atributos desnaturalizan a nuestra persona?
- Quiere comuda rapido ?
- Le importa que los ingredientes de la comida sean locales ?
- Se acuesta tarde ?

Actualmente tenemos dos casos de uso identificados:
- ordena a las 4 am
- Ordena junto con amigos.

Buscar un tercer caso de uso:

- espera promociones, ya que no tiene dinero.

UX Research
- entrevistas
- observacion de comportamiento.

Que hacen las personas ?
que tareas del dia a dia realizan con ayuda de la tecnologia ?
Que esperan de las tecnologías ?

Iceberg 

WHAT	Product features	VISIBLE
HOW	user experience			HIDDEN
WHY	value of product		HIDDEN

Entrevista Rich Fulcher

CASO EJEMPLO

cuales features amara Luis de una app?

CONCLUSIONES

- Es importante considerar iemprre ala persona y los casos de uso.
- priorizar lista de features
- definir que vamos a construir
- como construirlo
- Cuando construirlo ?

CREAR APLICACIONES PARA TODOS Y PARA NADIE.

==========================================

DISEÑO PARA MOVILES:

- Como es el usuario MObile ?
- diferencias entre mobil, desktop, web
- 4 restrucciones importantes cuando diseñamos aplicaciones moviles.
- wirefreaming. Como estructurar nuestros flujos de pantallas.

Usuario WEB and DESKTOP
Restricciones del usuario mobil: bateria finita, atencion dividad, handednness, pantalla pequeña, conexion limitada a interet.

OW ZONE	Iphone to iphone 4, etc.

PATRONES DE DISEÑO DE UX (solucions a problemas recurrentes)

- Ahorro de costos
- Reduccion de riesgos
- Familiaridad.

SKELETON VIEWS

Objetivo: hacer qye tu app "se sienta" mas rapida para los usuarios que la utilizan.

- utiliza elementos con figuras geometricas para reemplazar los elementos principales de tu pantalla.
- priorizar las pantallas con mas accesos de tus usuarios que dependan de la red y velocidad de procesamiento.
- crea skeleton views para elementos como imagenes y listas para que puedan ser reusados en itras secciones de la app.

TWO-STEP AUTHENTICATION

* puede ser atraves de un formulario, facebook, etc.
- Mejorar la seguirdad de las cuentas de los usuarios.
- Los usuaiors no actualizan sus contraseñas muy seguido.
- utilizan la misma contraseña para varios servicios.

 Como utilizarlo ?
Registro aplazado. Consiste en mostrarle a un usuario un On Boarding de la appa y lanzar la opcion de Login o Registro para ciertas acciones/funcionaliades.

Magic links. Nombre nice para una URL que contiene una contraseña de una sola vez.
-Deep links para Android
-Universal Links para iOS
-Enviarlos por Email o SMS
Acceso por SMS. Envio de contraseñas de una sola vez a través de Mensajes SMS.

Tips de como utiizarlo:
- Da varias alternativas de contacto a tus usuarios.
- Piensa muy bien en que momento pediras cierta informacion de contacto.
- Evalua tu stack tecnologico y costos de acuerdo al volumen de usuarios que tengas.
- Ocupa lineamientos de Chunking para que los codigos que envíen sean faciles de leer para tus usuarios.

ACCELERATOR

- atajos escondidos que le permiten a los usuarios ejecutar acciones o ver contecnido de manera más eficiente (power user)
- estan pensados en ser una alternativa que complemente la forma en que los usuaiors usan tu app.
Se mostró un ejemplo de ascelerador de Instagram.

Cuando utilizarlo ?

NOVATO  UX   EXPERTO

TIS PARA USAr ACELERADORES

- los aceleradores no deben ser la unica forma para cesar a un feature o contenido de tu app.
- utiliza metricas para decidir cuales features y que contenido vale la pena tener un acelerador.
- edica a tus usuarios para que los utilicen.
- Conoce el kit que puedes utilizar:

- Tap, double-tap, long-press, 3D tocuh, Swipe navigation, Swipe actions.
- onserva como otras apps inorporan aceleradores
- evita utilizar dos partones que puedan entrar en conflogcto (long-opress- vs 3Dtocuh)
- define el objetivo de tu acelerador para que haga sentido.

ONE-HANDED USAGE

la navegacion y los elementos primarios de tu aplicacion deben ser posibles sin la necesidad ed que el usario 
Uso con una mano, 94%  one hand, 6% portrail mode.

TIPS 

- prueba los elementos predeterminado del UIKit antes de implementar algo custom.
- analiza el objetivo de cada pantalla de tu app.
_ Brinda On Boardings para usos no tan frecuentes en una app.
- usa badges en la tabbar par notificar novedades
- educa a los usuarios sobre las pantallas adyacentes.

INTELLIGENCE

"a computer should never ask the user for any information that it can auto-detect, copy or deduce"
Eric Raymond

cuando utilizarlo ?
- cuando necesite presentarle informacion a tu usuario en un contecto que le gaga mas sencillo ejecturar una tarea.
- ayudate de sensores para presentar sugerencias elevantes.

Tips.
- no es necesario ser el master de machine learning
- dale oportunidad a tu usuario de revisar y aceptar las sugerencias.
- explota los sensores y fuentes de datos que tienes disponibles en los dispositibvos.
- Elige que esquema de permisos le dan una mejor experiencia a tus usuarios.
- Investiga las tecnologicas dispibles para hacer cosas más sofisticadas.

CONCLUSIONES:
- la velocidad importa cuendo se trata de retener usuarios.
- 2-step authentication imcremeyta las metricas de registro y segurodad ede las cuentas.
- los aceleradores dan la opcion de ejecutar las tareas en menos tiempo.
- fuera de casa, usar la app con una sola mano se vuelve crucial.
- la inteligencia en apps nos hace la vida mas facil y es un valor agreado para matar a tu competencia.
- pon atencion en como los usuarios utilizan tu app.
- enfócate en problemas freucnetes.
- no reinventes la rueda.


Notas el sabado 8 de diciembre.

APLICACIONES DEL DISEÑO EN iOS

- Contexto historico
- apple Human Interface Guidelines
- UX in Motion
- Seguimiento del Producto

Computacion Obicua:

Dispositivos Disponibles
Como y por que se utilizan estos dispositivos.

Ubiquitous Computing IT
Server: Stores and process information
Workstation: edit and manague information
Device: create and access information
Services: infrastructure
Standards.: interoperability: xhtml, GSM, HTTP, Bluetooth.

Por que e volvio importante ser creativos ?
- volatilidad de los hechos
- hay qye encarar una epoca de cambios
- lo que antes funcionaba no tiene por que funcionar mañana
- epoca de cambio exponencial.

VUCA

Termino que surge para explicar el sentido de las plataformas que se comen a otras.

Volatibility
Uncertainty
Complexity
Ambiguity

Insight: ofertas que disminuyen la asimetria de la informacion.
vienen de la parte de marketing, 

Diseño Responsivo vs Adaptativo

Responsivo: el contenido se adapta al tamaño de las pantallas.

Adaptativo: aparte del layut es que tiene controles especificos que estan pensabadas para usarse en ese modo.

APPLE HUMAN INTERFACE GUIDELINES

- Recomendaciones para el desarrollador.
- describe reglas visuales (iconos, diseño de ventanas, y estilos)
- especifican como funcionan los mecanismos de entrada e interaccion que ocupan los usuarios.
- le brinda contexto a las funciones de una app.
- se basa en politicas basadas en HCI - human computer interaction
- podemos "romper" una regla siempre y cuando esto signifique una ventaja para el contexto de nuestra app.

APPLE PRODUCT DESIGN

APPLE DESIGN PERSPECTIVE

Claridad: 
- text legible en cualquier temañ
- iconos precisos y lucidos
- importancia del contenico
- la funcionalidad del contenido.
- la funcionalidad gui al disñeo
- siempre se cubre la interactividad.

DEFERENCE

- El contenido es el rey.

PROFUNDIDAD

- jerarquia de contenido
- capas visuales.

Interace Essentials

El menu hamburguesa nacio en iOS

UI Animation

DESIGN THINKING

Empathize -> Define -> ideate -> prototype -> tes
 -|
												^														|
												|---------------------------|

"Dont build it, Fail it first"

Lean UX Cycle

							think ----------> Make ----------> check ---|
								^																					|
								|-----------------------------------------|

think: research, ideation, test Results
make: Sketch, prototypes, hypothesis
check: Analytics, A/B testing, Sign ups, Usage metrics.

"no se puede mejorar algo que no se puede medir"

Google tap manager - Pod para iOS.

Para quien vas a construir tu siguiente aplicacion ?


Pruebas unitarias
pruebas de interfaz
XCteste case
XCtest
ASSERTS

probar codigo Itunes Songs App

Siempre traten de moldear la logica d enegocio y de los modelos que se van a ocupar.

cliente Paw, nos da el codigo en swift o objective-C

en vez de usar cocoapods carthage, embebe un binario y se evitan errores de compilacion.

