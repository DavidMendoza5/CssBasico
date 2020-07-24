# Curso básico de CSS
CSS (Cascading Style Sheets) es un lenguaje utilizado para estilizar elementos escritos en HTML.
## Conceptos del curso
User agent: Son los estilos predeterminados del navegador.

Conceptos básicos de CSS: Selectores, especificidad, herencia y cascada.
- Especificidad: Hace referencia al algoritmo que contienen los navegadores para elegir el estilo que se le va a aplicar a los elementos, siempre toman
    el más específico, de ahí su nombre. Es a nivel de selectores. Url para calcular especificidad: [Especificidad](https://specificity.keegan.st/)
- Cascada: Lo que viene después sobreescribe lo que está antes, viene de la mano con la especificidad. Es decir, si tienes dos elementos con el mismo nombre
    (mismp valor de especificidad) en el css, el navegador va a usar el segundo elemento declarado.
- Selectores: Indican el elemento al que se le va a aplicar un estilo en el archivo css, existen diferentes tipos:
    - Sencillos.
    - De ID.
    - De clase
    - Universales.
    - Agrupados.
    - Descendientes.
    - Hijo directo.
    - Hermano siguiente.
    - Hermanos siguientes.
    - De atributos.
- Herencia: Indica que lo hijos heredan los atributos del padre.

Layout: Se refiere a la geometría de los elementos, es decir, en dónde van a estar puestos, sus márgenes, etc.

Existe elementos inline y de bloque tanto en css como en HTML.
- Inline: 
    - No crean nuevas líneas para cada elemento.
    - Tienen ancho y alto pero es relativo a su contenido y no se les puede definir otros valores.
    - Se ajustan al conetnido.
- Bloque:
    - Crean una nueva línea para cada elemento.
    - Ocupan todo el espacio horizontal disponible.
    - Tienen ancho y alto.

Box model: Contiene 4 elementos (cajas):
- Contenido.
- Paddind box.
- Border.
- Margin.

Unidades em y rem:
- em: Tamaño de fuente del contexto (es variable). 1em = 16 px. Es decir, dependiendo del texto va ir variando el tamaño del elemento.
- rem: Tamaño de fuente de root (HTML, nunca va a variar a menos que cambies la raíz).