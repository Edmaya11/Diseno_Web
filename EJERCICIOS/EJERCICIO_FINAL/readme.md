Aqui subirás tu ejercicio final, carpetas y archivos

![image](https://user-images.githubusercontent.com/91554777/166338740-a813cc76-4668-4bd8-8444-29b24e8451a4.png)

Para este proyecto se utilizaron las siguientes imágenes aunque puedes usar
cualesquiera otras:

Icono maya

https://www.pngwing.com/en/free-png-kjbes

Foto del primer alebrije

https://d36tnp772eyphs.cloudfront.net/blogs/2/2019/02/alebrijes-en-oaxaca-940x626.jpg

De https://matadornetwork.com/es/alebrijes-en-oaxaca-en-busqueda/

Foto del segundo alebrije

https://jacoboymariaangeles.com/wp-content/uploads/2021/07/a3.jpg

de https://jacoboymariaangeles.com/

Iconos de redes sociales

https://iconos8.es/icon/set/social-media/ios-glyphs

![image](https://user-images.githubusercontent.com/91554777/166338957-a14cf520-c2c8-4cdd-b76d-c332e979f79d.png)

Para este proyecto se utilizaron las siguientes imágenes aunque puedes usar
cualesquiera otras:

Primer imagen de PILARES

http://187.216.164.109/~edc/moodle/pluginfile.php/1/theme_academi/slide1image/1630643581/pilares.jpg

Segunda imagen

https://pilares.cdmx.gob.mx/assets/images/ajedrez.jpg

Tercera imagen

https://www.capital21.cdmx.gob.mx/noticias/wp-content/uploads/2021/01/pilares_02.jpg

![image](https://user-images.githubusercontent.com/91554777/166339035-765939bc-362e-408c-9186-5e1775cfc689.png)

Para este proyecto se utilizaron el siguiente video e imágenes aunque puedes usar
cualesquiera otras:

Video de fondo

https://drive.google.com/uc?export=download&id=15c1CVTTzprJLJbcoqVgDvDq-lze_r3TJ

Imágenes de redes sociales

https://i.ibb.co/HrfVRcx/menu.png

https://i.ibb.co/x7P24fL/facebook.png

https://i.ibb.co/Wnxq2Nq/twitter.png

https://i.ibb.co/ySwtH4B/instagram.png

![image](https://user-images.githubusercontent.com/91554777/166339213-46c269fc-77c0-4eeb-8c71-9eb0e9cc061f.png)

Para este proyecto se utilizaron el siguiente video e imágenes aunque puedes usar
cualesquiera otras:
Imagen de fondo
https://images.pexels.com/photos/1763075/pexels-photo-1763075.jpeg
Imágenes de redes sociales

https://raw.githubusercontent.com/WebDevSimplified/Introduction-to-Web-
Development/master/Introduction%20to%20CSS/Lesson%203/Images/Youtube%20Logo.png

https://raw.githubusercontent.com/WebDevSimplified/Introduction-to-Web-
Development/master/Introduction%20to%20CSS/Lesson%203/Images/Spotify%20Logo.png

https://raw.githubusercontent.com/WebDevSimplified/Introduction-to-Web-
Development/master/Introduction%20to%20CSS/Lesson%203/Images/Facebook%20Logo.png


Proyecto 2

          <!DOCTYPE html>
             <html lang="en">
             <head>

                 <meta charset="UTF-8">
                 <meta http-equiv="X-UA-Compatible" content="IE=edge">
                 <meta name="viewport" content="width=device-width, initial-scale=1.0">
                 <title>PILARES</title>
                 <link rel="stylesheet" href="css/estilos.css">
             </head>
             <body>
                 <main>
                      <div class="cuadro">
                         <p> <b>PILARES </b> </p>
                      </div>

                      <div class="blanco">
                          <p> <b>¿Qué es? </b><br>
                          Son puntos de encuentro de y para la ciudadanía, en ellos encontrarás: 
                          ciberescuelas, disciplinas artísticas, actividades deportivas, talleres de emprendimiento y capacitación para el empleo.<br>
                          </p>
                      </div>

                         <div class="recreacion"> 
                             <p><b>RECREACIÓN</b></p>
                         </div>  

                         <div class="negro">
                                 <p> <b>Proyecto</b><br>
                                 Son puntos de encuentro de y para la ciudadanía, en ellos encontrarás:<br>
                                 ciberescuelas, disciplinas artísticas, actividades deportivas, talleres de emprendimiento y capacitación para el empleo. <br>
                                 </p>
                          </div>

                             <div class="conexion">
                                 <p><b>CONEXIÓN</b></p>
                          </div>
                          <div class="negro">
                                 <p><b>¿Qué ofrece?</b><br>
                                 Son puntos de encuentro de y para la ciudadanía, en ellos encontrarás:<br>
                                 ciberescuelas, disciplinas artísticas, actividades deportivas, talleres de emprendimiento y capacitación para el empleo.  <br>
                                 </p>
                          </div>

                         <div class="comunidad">
                             <p><b>EMPODERAMIENTO</b></p>
                         </div>  
                 </main>

             </body>
             </html>


Estilos


                  *{
                      margin: 0;
                      padding: 0;
                  }

                  .cuadro{
                      height: 50vh;
                      width: 100%;
                      margin: auto;
                      background: url(http://187.216.164.109/~edc/moodle/pluginfile.php/1/theme_academi/slide1image/1630643581/pilares.jpg);
                      background-repeat: no-repeat;
                      background-position: center;
                      background-size: cover;
                      background-attachment: fixed;
                      display: flex;
                      align-items: center;
                      justify-content: center;
                      opacity: .8;
                  }
                  .cuadro p{
                      color: white;
                      font-size: 30px;
                      background-color: rgb(7, 7, 7);
                      text-align: center;
                  }

                  .blanco{
                      font-size: 30px;
                      background-color: azure;
                      text-align: center;

                  }

                  .recreacion{
                      height: 50vh;
                      width: 100%;
                      margin: auto;
                      background: url(https://pilares.cdmx.gob.mx/assets/images/ajedrez.jpg);
                      background-repeat: no-repeat;
                      background-position: center;
                      background-size: cover;
                      background-attachment: fixed;
                      display: flex;
                      align-items: center;
                      justify-content: center;
                      opacity: .8;
                  }

                  .recreacion p{
                      font-size: 30px;
                      background-color: azure;
                      text-align: center;
                  }

                  .conexion{
                      height: 50vh;
                      width: 100%;
                      margin: auto;
                      background: url(https://www.capital21.cdmx.gob.mx/noticias/wp-content/uploads/2021/01/pilares_02.jpg);
                      background-repeat: no-repeat;
                      background-position: center;
                      background-size: cover;
                      background-attachment: fixed;
                      display: flex;
                      align-items: center;
                      justify-content: center;
                      opacity: .8;
                  }

                  .conexion p{
                      font-size: 30px;
                      background-color: azure;
                      text-align: center;
                  }

                  .comunidad{
                      height: 50vh;
                      width: 100%;
                      margin: auto;
                      background: url(http://187.216.164.109/~edc/moodle/pluginfile.php/1/theme_academi/slide1image/1630643581/pilares.jpg);
                      background-repeat: no-repeat;
                      background-position: center;
                      background-size: cover;
                      background-attachment: fixed;
                      display: flex;
                      align-items: center;
                      justify-content: center;
                      opacity: .8;
                  }

                  .comunidad p{
                      color: white;
                      font-size: 30px;
                      background-color: rgb(7, 7, 7);
                      text-align: center;
                  }

                  .negro{
                      font-size: 30px;
                      color: white;
                      background-color: rgb(7, 7, 7);
                      text-align: center;
                  }    


