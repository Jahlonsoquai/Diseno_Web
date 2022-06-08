## 5. LENGUAJE CSS

Objetivo: Verificar el dominio de implementación de estilos (CSS) sobre el código html de
una página web.

Indicaciones: Pedir subrayar, encerrar en un círculo, o escribir la respuesta que
consideren correcta.

Preguntas:

1. ¿Qué significa CSS? (valor 0.25)

          a) Cascading Style Sheets
                    
2. ¿Cuál es el HTML correcto para hacer referencia a una hoja de estilo externa?
(valor 0.25)
          
          b) <link rel="stylesheet" type="text/css" href="style.css">
                    
3. ¿En qué parte de un documento HTML es el lugar correcto para hacer referencia a
una hoja de estilo externa? (valor 0.25)

          a) En la sección <head>
                    
 4. ¿Qué etiqueta HTML se utiliza para definir una hoja de estilo interna? (valor 0.25)
 
          c) <style>
          
 5. ¿Qué atributo HTML se usa para definir estilos en línea? (valor 0.25)
          
          b) styles
                    
 6. ¿Cuál es la sintaxis CSS correcta? (valor 0.25)

          b) body {color: black;}
                    
 7. ¿Cómo se inserta un comentario en un archivo CSS? (valor 0.25)

          a) /* esto es un comentario */
                    
8. ¿Qué propiedad se utiliza para cambiar el color de fondo? (valor 0.25)
          
          b) background-color
                    
9. ¿Cómo se agrega un color de fondo para todos los elementos h1 (valor 0.25)
            
          b) h1 {background-color:#FFFFFF;}
            
10. ¿Qué propiedad CSS se usa para cambiar el color del texto de un elemento? (valor 0.25)
  
          c) color
  
 11. ¿Qué propiedad CSS controla el tamaño del texto? (valor 0.25)
                     
          c) font-size
           
 12. ¿Cuál es la sintaxis CSS correcta para poner en negrita todos los elementos p?(valor 0.25)
           
          c) p {font-weight:bold;}
           
13. ¿Cómo hacer que cada palabra en un texto comience con una letra mayúscula? (valor 0.25)
            
          b) text-transform:capitalize
            
14. ¿Qué propiedad se utiliza para cambiar la fuente de un elemento? (valor 0.25)
            
          b) font-family         
  
15. ¿Cómo pones el texto en negrita? (valor 0.25)
                      
          c) font-weight:bold;
  
16. ¿Cómo se muestra un borde como este? (valor 0.25)

El borde superior = 10 píxeles

El borde inferior = 5 píxeles

El borde izquierdo = 20 píxeles

El borde derecho = 1 píxel
  
          a) border-width:10px 1px 5px 20px;
                   
17. ¿Qué propiedad se usa para cambiar el margen izquierdo de un elemento? (valor 0.25)

          b) margin-left
          
18. Al usar la propiedad de relleno (padding); ¿Está permitido usar valores negativos? (valor 0.25)

            a) No
                       
 19. ¿Cómo se selecciona un elemento con id 'demo'? (valor 0.25)
             
            b) #demo                   
            
20.¿Cómo se seleccionan elementos con el nombre de clase 'test'? (valor 0.25)
            
            b) .test     
                        
21. ¿Cómo se seleccionan todos los elementos p dentro de un elemento div? (valor 0.25)
            
            b) div p
                       
22.¿Cómo se agrupan los selectores? (valor 0.25)
            
            c) Separe cada selector con una coma
            
23. ¿Cuál es el valor predeterminado de la propiedad posición? (valor 0.25)

            d) static
            
 24.¿Cómo se hace una lista que enumere sus elementos con cuadrados? (valor 0.25)
             
            c) list-style-type: square;
            
Realiza la maquetación del siguiente ejemplo de página: (se aplica la rúbrica de la
maquetación en código html y css, valor 36)

![image](https://user-images.githubusercontent.com/91554777/166742177-b3cc2bfc-7768-42e4-b4f0-dcc2a1473935.png)

● Este ejercicio lo deberás realizar con las etiquetas de HTML5, haciendo uso de los elementos semánticos de HTML5.

● Deberás, en un bloc de notas, colocar todo el código html5 y guárdalo con extensión .html

● Lo mismo harás con el código CSS3, deberás guardar en un bloc de notas el código css3 con extensión .css.

● Guardar ambos archivos, el código html5 y css3, en una misma carpeta.

● Recuerda usar el elemento link para llamar dentro del código html5 los estilos guardados en el archivo con extensión .css.

-Hay tres imágenes que utilizarás para realizar esta actividad:
Imagen del logo institucional.
https://escuelasdecodigo.cdmx.gob.mx/wp-content/themes/escuelasdecodigo/assets/images/logo.svg

Imagen del vector blanco que se encuentra antes del texto “Aprende a programar”. https://escuelasdecodigo.cdmx.gob.mx/wp-content/themes/escuelasdecodigo/dist/assets/hero-vector.svg

Imagen paisaje de la Ciudad de México
https://escuelasdecodigo.cdmx.gob.mx/wp-content/themes/escuelasdecodigo/dist/assets/hero.jpg

-El texto alternativo para la primer imagen imagen debe ser “Gobierno de la Ciudad de México”


## INGRESA AQUI EL CÓDIGO HTML

          <!DOCTYPE html>
          <html lang="en">
          <head>
              <meta charset="UTF-8">
              <meta http-equiv="X-UA-Compatible" content="IE=edge">
              <meta name="viewport" content="width=device-width, initial-scale=1.0">
              <title>Escuelas de Cógido CDMX</title>
              <link rel="stylesheet" href="css/estilos.css">
              <link rel="preconnect" href="https://fonts.googleapis.com">
              <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
              <link href="https://fonts.googleapis.com/css2?family=Source+Code+Pro&family=Spline+Sans+Mono&display=swap"
                  rel="stylesheet">
          </head>
          <body>
              <header>
                  <img src="https://escuelasdecodigo.cdmx.gob.mx/wp-content/themes/escuelasdecodigo/assets/images/logo.svg" alt="Gobierno de la Ciudad de México"><hr>
                  <nav>
                      <ul>
                          <a class="sd" href="#"><li>Residentes</li></a>
                          <a class="sd" href="#"><li>Negocios</li></a>
                          <a class="sd" href="#"><li>Visitantes</li></a>
                          <a class="sd" href="#"><li>Gobierno</li></a>
                      </ul>
                  </nav>
              </header>

              <main>
                  <div class="boxo">
                     <div class="boxi">
                      <p id="p0"><img src="https://escuelasdecodigo.cdmx.gob.mx/wp-content/themes/escuelasdecodigo/dist/assets/hero-vector.svg" alt="Vector" width="80px" height="80px"><b>APRENDE A PROGRAMAR</b></p>
                      <p id="p1"><b>EN LAS</b><span><b>ESCUELAS</b></span></p>
                      <p id="p2"><b>DE CÓDIGO</b></p>
                      <p id="p3"><b>DE LA CDMX</b></p>
                      </div>
                  </div>
              </main>

              <footer>
                  <h2>¿Quién se puede inscribir?</h2>
                  <p><b>Cualquier persona que quiera aprender a programar código y cuente con 4-8 horas disponibles a la semana</b></p>
                  <p>*Menores de edad deberán entrar a las instalaciones acompañados de un adulto</p>
              </footer>
          </body>
          </html>         
          
## INGRESA AQUI EL CSS
          
          * {
              margin:0;
              padding: 0;
          }

          main{
              background: url(https://escuelasdecodigo.cdmx.gob.mx/wp-content/themes/escuelasdecodigo/dist/assets/hero.jpg);
              background-repeat: no-repeat;
              background-position: center;
              background-size: cover;
              height: 60vh;
              width: 100%;
          }

          nav{
              display: flex;
              justify-content: flex-end;

          }

          ul{
             display: flex;
          }

          li{
              margin-left: 20px;
              padding: 10px;
              color:green;
              font-family: 'Spline Sans Mono', monospace;
              list-style-type: none;
          }

          .sd{
              text-decoration-line: none;
          }


          .boxo{
              position: fixed;
              height: 60vh;
              width: 70%;
              padding-top: 20px;
              padding-bottom: 20px;
          }

          .boxi{
              padding-top: 30px;
              padding-bottom: 30px;
          }

          #p0{
              left: 60px;
              font-family: 'Spline Sans Mono', monospace;
              font-size: 4.2em;
              color: white;
              letter-spacing: 8px;

          }

          div span{
              font-family: 'Spline Sans Mono', monospace;
              font-size: 110px;
              color: white;
              font-weight: bold; 
              letter-spacing: 1px;
          }

          #p1{
              text-indent: 180px;
              font-family: 'Spline Sans Mono', monospace;
              color: white; 
              font-size: 4.2em;
              text-indent: 208px;
              letter-spacing: 8px;
              word-spacing: -25px;  

          }


          #p2{
              font-family: 'Spline Sans Mono', monospace;
              color: white; 
              font-size: 110px;
              font-weight: bold;
              text-indent: 490px;
              word-spacing: -50px;

          }

          #p3{
              font-family: 'Spline Sans Mono', monospace;
              color: white; 
              font-size: 4.2em;
              text-indent: 490px;
              letter-spacing: 8px;
          }

          footer h2{
              color:goldenrod;
              font-weight: bold;

          }

          footer{
              text-align: center;
              font-size: 20px;
              font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;

          }

          
          
## Ingresa el link a tu página del proyecto final
 
 https://jahlonsoquai.github.io/Proyecto_EvaluacionCSS/
 
 
