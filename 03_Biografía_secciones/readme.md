# Elementos de "sectioning" según el estandar HTML5 #

https://www.w3.org/TR/2014/REC-html5-20141028/sections.html#sections

- 4.3.1. The body element

- 4.3.2.The article element

- 4.3.3.The section element

- 4.3.4. The nav element

- 4.3.5 The aside element

- 4.3.6 The h1, h2, h3, h4, h5, and h6 elements

- 4.3.7 The header element

- 4.3.8 The footer element

- 4.3.9 The address element

## article ##

El Elemento article de HTML (&lt;article>) representa una composición auto-contenida en un documento, página, una aplicación o en el sitio, que se destina a distribuir de forma independiente o reutilizable, por ejemplo, en la sindicación (suscripción). Podría ser un mensaje en un foro, un artículo de una revista o un periódico, una entrada de blog, un comentario de un usuario, un widget interactivo o gadget, o cualquier otro elemento independiente del contenido.

## section ##

El elemento de HTML section (&lt;section>) representa una sección genérica de un documento. Sirve para determinar qué contenido corresponde a qué parte de un esquema. Piensa en el esquema como en el índice de contenido de un libro; un tema común y subsecciones relacionadas.  Es, por lo tanto, una etiquéta semántica. Su funcionalidad principal es estructurar semánticamente un documento a la hora de ser representado por parte de un agente usuario. Por ejemplo, un agente de usuario que represente el documento en voz, podría exponer al usuario el índice de contenido por niveles para navegar rápidamente por las distintas partes.

## nav ##

El elemento HTML (&lt;nav>) representa una sección de una página cuyo propósito es proporcionar enlaces de navegación, ya sea dentro del documento actual o a otros documentos. Ejemplos comunes de secciones de navegación son menús, tablas de contenido e índices.

## aside ##

El Elemento HTML Aside (&lt;aside>) representa una sección de una página que consiste en contenido que está tangencialmente relacionado con el contenido que le rodea, que podría ser considerado independiente de ese contenido. Estas secciones son a menudo representadas como barras laterales o como inserciones y contienen una explicación al margen como una definición de glosario, elementos relacionados indirectamente, como publicidad, la biografía del autor, o en aplicaciones web, la información de perfil o enlaces a blogs relacionados.

## header ##

El elemento de HTML Header (&lt;header>) representa un grupo de ayudas introductorias o de navegación. Puede contener algunos elementos de encabezado, pero también otros elementos como un logo, una sección que aglutine secciones de encabezados, una formulario de búsqueda o cosas parecidas.

## footer ##

El Elemento HTML Footer (&lt;footer>) representa un pie de página para el contenido de sección más cercano o el elemento  raíz de sección (p.e, su ancestro mas cercano &lt;article>, &lt;aside>, &lt;nav>, &lt;section>,&lt;blockquote>, &lt;body>, &lt;details>, &lt;fieldset>, &lt;figure>, &lt;td>). Un pie de página típicamente contiene información acerca de el autor de la sección, datos de derechos de autor o enlaces a documentos relacionados.

&lt;meta http-equiv="content-type" content="text/html; charset=utf-8"/>

## address ##

El elemento HTML &lt;address> aporta información de contacto para su &lt;article> más cercano o ancestro &lt;body>; en el último caso lo aplica a todo el documento.

## main ##

El elemento HTML &lt;main>  representa el contenido principal del &lt;body> de un documento o aplicación. El área principal del contenido consiste en el contenido que está directamente relacionado, o se expande sobre el tema central de un documento o la funcionalidad central de una aplicación. Este contenido debe ser único al documento, excluyendo cualquier contenido que se repita a través de un conjunto de documentos como barras laterales, enlaces de navegación, información de derechos de autor, logos del sitio y formularios de búsqueda (a menos, claro, que la función principal del documento sea un formulario de búsqueda).