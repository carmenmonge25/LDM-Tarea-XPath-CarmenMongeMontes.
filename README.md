# LDM-Tarea-XPath-CarmenMongeMontes.
En primer lugar abrimos Visual Studio con la carpeta que contiene el xml y el xsd. 
Creamos un Notepad del xml y le ponemos de título "XPath Notebook- Navegando por el árbol del documento"
**Reto 1:**
Comenzamos con el primer reto añadiendo un Markdown con el enunciado.
Añadimos el código: /bibliotecaTecnica/recurso[categoria="CSS" and disponible=true()]/titulo /string()
De esta forma solo tenemos los títulos de los recursos con categoría CSS y que estén disponibles
Como los datos que nos salen son correctos, pasamos a la siguiente actividad.
**Reto 2:**
Metemos el enunciado en un Markdown
Añadimos el código: /bibliotecaTecnica/recurso[@formato!="PDF" or not (@formato)]/@id /string()
De esta forma nos proporciona los id de los recursos que no tengan formato o que no sean PDF, así te da todos los recursos que no son PDF.
Como los datos que nos salen son correctos, pasamos a la siguiente actividad.
