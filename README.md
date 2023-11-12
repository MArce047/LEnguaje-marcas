# Cuardeno UD1
## **Que es un lenguaje de marcas**
 Un lenguaje de marcas, también conocido como lenguaje de marcado o markup language en inglés, es un conjunto de etiquetas y reglas que se utiliza para definir la estructura y presentación de documentos, como páginas web o documentos de texto enriquecido. Estos lenguajes se utilizan para dar formato, organizar y etiquetar el contenido dentro de un documento, lo que permite que los navegadores web y otros programas interpreten y muestren el contenido de manera adecuada.
## Evolucion de los lenguaje de marcas
 La evolución de los lenguajes de marcas, incluyendo GML (Generalized Markup Language) y SGML (Standard Generalized Markup Language), ha sido significativa en la historia de la informática y la creación de documentos estructurados. Aquí hay una breve descripción de la evolución de estos lenguajes:
  ### **SGML**
  1.-SGML se desarrolló en la década de 1960 como un estándar para la creación de documentos estructurados. Fue utilizado principalmente en la industria de la publicación y la documentación técnica.
  
2.- SGML es un lenguaje de marcas muy generalizado y extensible que permite la creación de estructuras de marcado personalizadas para documentos. Definió una sintaxis y un conjunto de reglas para la creación de documentos marcados.

3.- A pesar de su versatilidad, SGML era complejo y requería un conjunto extenso de reglas y definiciones. Como resultado, se convirtió en la base de desarrollo para lenguajes de marcas más específicos y fáciles de usar.
   	
### **GML**
  1.- GML es una evolución temprana de SGML que se desarrolló en la década de 1960 para facilitar la creación de documentos estructurados. Aunque GML no se ha vuelto tan ampliamente conocido como SGML, es un antecedente importante en la evolución de lenguajes de marcas.
	
2.- GML se centró en simplificar la creación de documentos marcados al proporcionar una sintaxis más accesible que SGML, pero aún conservando muchas de las capacidades de marcado estructurado.

## **Caracteristicas de los lenguajes de marcas**
  1.- Estructura Jerárquica: Los lenguajes de marcas organizan el contenido en una estructura jerárquica, utilizando etiquetas o marcas que definen cómo se debe mostrar o interpretar cada elemento. Esto permite la representación de relaciones y niveles de anidamiento en el contenido.

2.- Sintaxis Simple: La sintaxis de los lenguajes de marcas es relativamente simple y legible. Utilizan etiquetas o marcadores que son comprensibles para los humanos y se asemejan a etiquetas en forma de texto encerradas entre "<" y ">" (por ejemplo, <p> para un párrafo en HTML).

3.- Autocontenidos: Los lenguajes de marcas pueden ser autocontenidos, lo que significa que los documentos pueden incluir toda la información necesaria para su interpretación. Esto permite la portabilidad y la independencia del contexto.

4.- Extensibilidad: Los lenguajes de marcas son extensibles, lo que permite a los usuarios definir sus propias etiquetas y estructuras de documentos según las necesidades específicas. Esto se logra mediante la definición de Document Type Definitions (DTD) o esquemas.

5.- Separación de Contenido y Presentación: Muchos lenguajes de marcas, como HTML, se centran en la estructura y el contenido, separando la presentación visual. Esto facilita la adaptación del contenido a diferentes medios y dispositivos.

6.- Interoperabilidad: Los lenguajes de marcas se utilizan en una variedad de contextos y aplicaciones, lo que los hace interoperables. Pueden integrarse con otros sistemas y tecnologías, lo que facilita la transferencia de datos y la comunicación entre aplicaciones.

7.- Documentación y Comentarios: Los lenguajes de marcas suelen permitir la inclusión de comentarios y documentación en el código, lo que facilita la comprensión y el mantenimiento del contenido.

8.- Facilidad de Edición: Los lenguajes de marcas son fáciles de editar con herramientas de texto simples, lo que hace que sean accesibles para una amplia gama de usuarios.

9.- Universalidad: Dado que los lenguajes de marcas se utilizan para describir datos y contenido en una forma estructurada y legible por máquina, son ampliamente utilizados en una variedad de aplicaciones, desde la creación de páginas web hasta el intercambio de datos y la documentación técnica.

## **Caracteristicas de los siguientes lengujes de marcas** 
  ### **XML**
 1. Extensibildad XML: XML permite definir etiquetas personalizadas para estructurar datos de manera especifica.
     
 2. Jerarquia: Los datos se organizan en una estructura jerarquica de elementos anidados.
     
3. Legibilidad La sintaxis de XML es legible por humanos y utiliza etiquetas en formato de inicio y cierre. 
   
 4. Versatilidad: Se utiliza en una variedad de aplicaciones , incluyendo intercambio de datos , configuracion y 
      descripcion de documentos.
Ejemplo:

             <libro>
             <titulo>El Gran Gatsby</titulo>
              <autor>F. Scott Fitzgerald</autor>
              <publicacion>1925</publicacion>
              </libro>

### **HTML**
1. Estructura de Página Web: HTML se utiliza para estructurar el contenido de páginas web, definiendo elementos como encabezados, párrafos, enlaces, imágenes y más.
2. Presentación Visual: HTML también se encarga de definir cómo se presenta el contenido en un navegador web.
3. Sintaxis Simple: Utiliza etiquetas que se asemejan a <etiqueta> y <etiqueta /> para elementos autocontenidos.
4. Separación de Contenido y Presentación: HTML se centra en la estructura y el contenido, mientras que el CSS se utiliza para la presentación visual.

Ejemplo:

        <h1>Título de la Página</h1>
        <p>Este es un párrafo de ejemplo.</p>
        <a href="https://www.ejemplo.com">Enlace a un sitio web</a>

### **JSON**
1. Ligereza: JSON es un formato de intercambio de datos ligero y fácil de leer.
2. Utilizado en Programación: Es ampliamente utilizado en la programación para representar datos estructurados.
3. Sintaxis Clara: Utiliza pares de clave-valor separados por comas, y los datos pueden ser objetos o arreglos.
4. Ideal para Datos No Estructurados: JSON es adecuado para datos no estructurados o semi-estructurados.

Ejemplo:

        {
          "nombre": "Juan Pérez",
          "edad": 30,
          "ciudad": "Ejemplolandia"
        }

### **YAML**
1. Legibilidad: YAML se enfoca en ser fácil de leer y escribir para los humanos.
2. Jerarquía mediante espacios: Utiliza espacios o sangría para indicar la jerarquía y las relaciones entre los datos.
3. Comentarios: Permite incluir comentarios para documentación y clarificación.
4. Utilizado en Configuración: YAML es comúnmente usado en configuración de software y archivos de configuración.

Ejemplo:

        nombre: Juan Pérez
        edad: 30
        ciudad: Ejemplolandia


### **XML : definición y características del metalenguaje**
El XML es un lenguaje de marcas que se utiliza para representar y estructurar datos en un formato legible tanto por humanos como por máquinas. Fue diseñado para ser extensible y adaptable a una amplia variedad de aplicaciones.

1. Metalenguaje: En el contexto de XML, el término "metalenguaje" se refiere al conjunto de reglas y definiciones que especifican cómo se deben crear y estructurar documentos XML. Estas reglas incluyen la forma en que se deben utilizar las etiquetas, los atributos, y cómo se deben anidar los elementos.

2. Prologo: El prolog de un documento XML es una sección opcional que proporciona información sobre el documento. Puede contener detalles como la versión de XML utilizada, la codificación de caracteres, y en algunos casos, la definición de un Document Type Definition (DTD) o un esquema XML. Un prolog típico se ve de la siguiente manera:

        <?xml version="1.0" encoding="UTF-8"?>

 3. Etiquetas:  Las etiquetas son elementos fundamentales en XML y se utilizan para definir elementos y estructurar datos. Cada etiqueta tiene un nombre que identifica el elemento y se coloca entre "<" y ">" o "</" y ">" para marcar el inicio y el final del elemento.

 4. Atributos: Los atributos son información adicional que se puede adjuntar a los elementos mediante el uso de pares clave-valor dentro de las etiquetas. Los atributos permiten proporcionar metadatos o detalles específicos sobre un elemento.

Ejemplos de XML :

        <?xml version="1.0" encoding="UTF-8"?>
        <libro>
          <titulo>El Gran Gatsby</titulo>
          <autor>F. Scott Fitzgerald</autor>
          <publicacion>1925</publicacion>
        </libro>






























