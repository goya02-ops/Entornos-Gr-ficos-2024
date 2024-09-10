1. Qué es HTML, cuando fue creado, cuáles fueron las distintas versiones y cuál es la última?

HTML (HyperText Markup Lenguage - Lenguaje marcado de hipertexto) es el lenguaje de marcado principal de la World Wide Web, creado en el año 1990,
que define la estructura básica y un código para la definición de contenido de una web.

Sus versiones son:
- HTML 1.0
- HTML 2.0
- HTML 3.0
- HTML 3.2
- HTML 4.01
- XHTML 1.0
- XHTML 2.0
- HTML 5.0 siendo esta la última versión

2. ¿Cuáles son los principios básicos que el W3C recomienda seguir para la creación de documentos 
con HTML?
-  Separar estructura y presentación
- Considerar la accesibilidad universal a la Web
- Ayudar a los agentes de usuario con la representación incremental

3. En las Especificaciones de HTML, ¿cuándo un elemento o atributo se considera desaprobado? ¿y 
obsoleto?

- Atributo desprobado: aquel que ha quedado anticuado por la presencia de estructuras nuevas. 
Los elementos desaprobados se definen en el manual de referencia en los lugares apropiados, pero claramente marcados como desaprobados. 
Los elementos desaprobados pueden declararse obsoletos en versiones futuras de HTML.

- Atributo obsoleto: aquél para el cual no hay garantía de soporte por parte de un agente de usuario.

4. Qué es el DTD y cuáles son los posibles DTDs contemplados en la especificación de HTML 4.01?

DTD (document type definition - definición del tipo de documento) define la sintaxis de las estrucuturas de formato. Puede incluir definiciones adicionales, 
tales como referencias a entidades de caracteres.
HTML 4.01 especifica tres DTDs, de modo que los autores deben incluir una de las siguientes declaraciones del tipo de documento en sus documentos. Los DTDs varían en cuanto a los elementos que soportan.

El DTD HTML 4.01 Estricto (Strict DTD) incluye todos los elementos y atributos que no han sido desaprobados o que no aparecen en documentos con marcos. Para los documentos que usen este DTD, utilice esta declaración del tipo de documento:
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN"
        "http://www.w3.org/TR/html4/strict.dtd">

El DTD HTML 4.01 Transicional (Transitional DTD) incluye todo lo que incluye el DTD estricto más los elementos y atributos desaprobados (la mayoría de los cuales están relacionados con la presentación visual). Para los documentos que usen este DTD, utilice esta declaración del tipo de documento:
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN"
        "http://www.w3.org/TR/html4/loose.dtd">

El DTD HTML 4.01 para Documentos con Marcos (Frameset DTD) incluye todo lo que incluye el DTD Transicional más los marcos. Para los documentos que usen este DTD, utilice esta declaración del tipo de documento:
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Frameset//EN"
        "http://www.w3.org/TR/html4/frameset.dtd">

5. Qué son los metadatos y cómo se especifican en HTML?

Metadatos: información sobre un documento más contenido del propio documento
Por ejemplo, para especificar el autor de un documento, puede utilizarse el elemento META como sigue:

<META name="Author" content="Dave Raggett">