<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vacunacion</title>
    
</head>
  /*generales*/
.titulo{
    color: rgba(83, 91, 228, 0.76);
    font-family: Georgia, 'Times New Roman', Times, serif;
}

p{
    margin: 10px;
    color: rgba(33, 33, 209, 0.594);
}

body{
    background-image: url(bg.png);
    background-size: contain;
    width: 100%;
}
h2{
    color: rgba(34, 34, 111, 0.915);
}
/*todo lo que involucra al header*/
header{
    height: 100px;
    width: 100%;
}
ul.cabezera{
    list-style-type: none;
    margin: -45px 540px;
    padding: 0;
    width: 550px;
    background-color:rgba(128, 128, 128, 0.038);
    
}
li.cabezera{
    display: inline;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    font-size: 22px;
    border-right: 1px solid black;
    min-width: 15px;
    padding: 15px;
    
}
li#li_cabezera4{
    border-right: none;
}


/*Todo lo que involucra el parrafo 1*/
div.parrafo1{
    font-family: Arial, Helvetica, sans-serif; 
    border:none solid black;
    height: 400px;
    text-align:left;
    width: 100%;
}
#img1{
    margin: -150px 830px;
    background-color: rgba(0, 0, 255, 0.568); 
    
}

#formularioCitas{
    margin: -130px 10px;  
    background-color: rgba(0, 162, 255, 0.067);
    height: 200px;
}
#sec_form2{
    margin: -47px 180px;
}
#sec_form3{
    margin: 1px 390px;
}
#boton_form1{
    margin: -15px 5px;
}
#imgformulario_cita{
    height: 20px;
    width: 20px;
}
#imgformulario_cita_1{
    height: 20px;
    width: 20px;
}
#imgformulario_cita_2{
    height: 23px;
    width: 23px;
}
#imgformulario_cita_3{
    height: 23px;
    width: 23px;
}

/*Todo lo que involucra el parrafo 2*/
div.parrafo2{
    font-family: Arial, Helvetica, sans-serif;
    border:none solid black;
    height: 600px;
}
.ul_parrafo2{
    list-style-type: none;
    margin: 0;
    padding: 0;
    
}
.li_parrafo2_1{
    margin:10px ;
}
#imgparrafo2_1{
    height: 40px;
    width: 40px;
    margin:0 100px;
}

.li_parrafo2_2{
    margin:-107px 400px ;
}
#imgparrafo2_2{
    height: 40px;
    width: 40px;
    margin:0 100px;
}

.li_parrafo2_4{
    margin: -265px 10px;
}
#imgparrafo2_4{
    height: 40px;
    width: 60px;
    margin:0 60px;
}

#img_vacunacion{
    margin: -295px 760px; 
    height: 500px;
    width: 500px;
}


/*Todo lo que involucra el parrafo 3*/
.parrafo3{
    font-family: Arial, Helvetica, sans-serif;
    border:none solid black;
    text-align: left;
    height:630px;
    
}
#imgparrafo2_3{
    height: 60px;
    width: 60px;
    margin:0 100px;
}
#ul_parrafo3{
    margin: -350px 450px;
    width: 700px;
}
.li_parrafo2_3{
    margin: 190px 400px
}

/*todo lo que involucra el parrafo 4*/
div.parrafo4{
    font-family: Arial, Helvetica, sans-serif;
    border: none solid black;
    text-align: left;
}

.ul_parrafo4{
    list-style-type: none;
    margin: -45px 540px;
    padding: 0;
    width: 550px;
}
#liparrafo4{
    display: inline;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}

/*Todo lo que involucra el futter*/
footer{
    border: none solid black;
    max-height: 25px;
}

table{
    width: max-content;
    margin: 50px 800px;
    text-align: center;
    font-family:Arial, Helvetica, sans-serif ;
    font-size: 15px;
    
}
#tdfooter{
    padding: 15px;
}
#thfooter{
    text-align: center;
}
<body>
  <!--todo lo que involucra al header-->  
    <header>
        <h1 class="titulo">Vacunas</h1>
        <nav clas="navegacion">
            <ul class="cabezera">
                <li class="cabezera" id="li_cabezera1"><a href="#">Base de Datos</a></li>
                <li class="cabezera" id="li_cabezera2"><a href="#">Educacion</a></li>
                <li class="cabezera" id="li_cabezera3"><a href="#">Noticias</a></li>
                <li class="cabezera" id="li_cabezera4"><a href="#">Regulacion</a></li>
            </ul>
        </nav>
    </header>
    <hr>
    <br>
    <section>
 
        <!--todo lo que involucra a los articulos-->  
        <article>
            <!--todo lo que involucra al parrafo 1-->  
            <div class="parrafo1">
                <h2>No olvidemos lo que hemos consegido,<br>
                    Sigamos actuando frente a la COVID</h2>
                    <p class="PDparrafo1">Pongamos fin a esta pandemia, detengamos el virus <br>
                    no ponga en reigo a su famila, vaunese!.
                    </p>
                    <br>
                    <img src="parrafo1.png" alt="mujer conn jeringa" height="400px" width="400px" id="img1">
                    
                    <!--formulario para solicitar cita-->
                <section id="formularioCitas">
                    <form action="/action.js" id="agendaCita" class="soliCita">  
                            <h3><img src="formulario_cita.png" alt="reloj" id="imgformulario_cita">Agende su cita</h3>
                            
                            <section id="sec_form1">
                                <label for="ciudades"><img src="formulario_cita_1.png" alt="ubicacion" id="imgformulario_cita_1">Cual es su ciudad?</label> <br>
                                    <select id="ciudades">
                                        <option value="San Jose">San Jose</option>
                                        <option value="Cartago">Cartago</option>
                                        <option value="Guanacaste">Guanacaste</option>
                                    </select>
                            </section>
                            <section id="sec_form2">
                                <label for="date"><img src="formulario_cita_2.png" alt="calendario" id="imgformulario_cita_2"> cuando quiere su cita?</label><br>
                                <input type="date" id="fecha1" name="fecha1">
                            </section>
                            <section id="sec_form3">
                                <label for="vacuna"><img src="formulario_cita_3.png" alt="vacuna" id="imgformulario_cita_3"> Cual vacuana desea ponerse?</label><br>
                                <select name="vacuna" id="vacuna">
                                    <option value="astrazeneca">Astrazeneca</option>
                                    <option value="spuknik">Spuknik</option>
                                </select>
                            </section>
                        <br>
                        <br>
                        <input type="submit" value="enviar" id="boton_form1">
                    </form>
                </section>
            </div>
        <hr>
            
        </article>
        
        <br>
        <article>
            <!--todo lo que involucra al parrafo2-->  
            <div class="parrafo2">
                <h2>Porque vacuanrse?</h2>
                <p class="PDparaffo2">De acuerdo con la OMS la vacunación es una forma sencilla, <br>
                     inocua y eficaz de protegerse contra las enfermedades dañinas antes de entrar <br>
                      en contacto con ellas, pues activa las defensas naturales del organismo para <br>
                       que aprendan a resistir infecciones específicas y fortalezcan el sistema <br>
                    En ese sentido, la vacunación contra el COVID-19, permitirá reducir el riesgo <br>
                     de enfermar de forma grave y morir, pues se estará mejor protegido. No se alcanzará <br>
                      la inmunidad al 100% ya que igual se puede contraer la enfermedad, sin embargo, <br>
                       las consecuencias en el organismo serán mucho menores. <br>
                    Los principales beneficios son: </p>
                    <br>
                    <img src="parrafo2.png" alt="persona siendo vacunada" id="img_vacunacion">

                <ul class="ul_parrafo2">
                    <li class="li_parrafo2_1">
                        <p><img src="parrafo2_1.png" alt="estadistica" id="imgparrafo2_1"><br> Las vacunas contra el COVID-19 también pueden<br>
                            evitar que se enferme gravemente <br>
                            aunque contraiga el virus.</p>
                    </li>
                    <li class="li_parrafo2_2">
                        <p><img src="parrafo2_2.png" alt="escudo" id="imgparrafo2_2"><br>Todas las vacunas contra el Covid-19<br>
                            son seguras y efectivas.</p>
                    </li>
                    <li class="li_parrafo2_3">
                        <p><img src="parrafo2_3.png" alt="comunidad" id="imgparrafo2_3"><br> Al vacunarse uno mismo también <br>
                            protege a las personas que lo rodean.</p>
                    </li>
                    <li class="li_parrafo2_4">
                        <p><img src="parrafo2_4.png" alt="grupo" id="imgparrafo2_4"><br>Es una forma más segura <br>
                        de desarrollar la inmunidad.</p>
                    </li>
                </ul>
            </div>

        </article>
        <hr>
        <br>
        <article>
            <!--todo lo que involucra al parrafo3-->  
            <div class="parrafo3">
                <h2>Preparaciones antes de ir a vacunarse</h2>
                <p class="PDparrafo3">Preparativos antes de la vacuna:
                El éxito de las vacunas está <br>
                fuertemente influenciado por la fortaleza del sistema inmunológico <br>
                del cuerpo.Por lo tanto, hay varias cosas
                que se pueden intentar <br>
                para que la vacuna contrabr
                el COVID-19 funcione:</p>
                <img src="parrafo3.png" alt="enfermero" id="img_parrafo3">
                <div id="ul_parrafo3">
                    <ul>
                        <li>
                            Evite las bebidas alcohólicas 
                        </li>
                
                        <li>
                            Evitar el estrés
                        </li>
                        <li>
                            El estrés tiene un efecto profundo en el trabajo inmunológico.
                        </li>
                        <li>
                            Además, el estrés prolongado puede aumentar <br>
                            la producción de cortisol y el estrés oxidativo en el                   
                            Comer comida sana 
                        </li>
                        <li>
                            Dormir lo suficiente <br>             
                            Ejercicio o actividad física
                        </li>              
                        
                    </ul>
                </div>
            </div>
        </article>
        <hr>

        <br>
        <article>
            <!--todo lo que involucra al parrafo4r-->  
            <div class="parrafo4">
                <h2>Contacto de emergencia</h2>
                <br>
                <p id="PDparaafo4">Contacto de emergencia
                    Comuníquese con uno de los contactos a continuación si usted o su familia se sienten mal y tienen síntomas similares, <br>
                    como Covid-19, asegúrese de cuidarse también antes de informarnos.
                </p>
                <br>
                <ul class="ulparrafo4">
                    <li>
                        <div id="liparrafo4">
                            <P>telefono : 123456789</P>
                            <button>llamar ahora</button>
                        </div>
                    </li>
                    <li id="liparrafo4">
                        <p>Chat bot</p>
                        <button>chatear ahora</button>
                    </li>
                    <li id="liparrafo4">
                        <p>Email</p>
                        <button>enviar correo</button>
                    </li>
                </ul>
            
            </div>
        </article>
    </section>
    <hr>
    <!--todo lo que involucra al footer-->  
    <footer>
        <table> 
            <tr>
                <th id="thfooter">Nosostros</th>
                <th id="thfooter">Ayuda</th>
                <th id="thfooter">Empresa</th>
            </tr>
            <tr>
                <td><a href="#" id="tdfooter">Sobre nosotros</a></td>
                <td><a href="#" id="tdfooter">Contactenos</a></td>
                <td><a href="#" id="tdfooter">FAQs</a></td>
            </tr>
            <tr>
                <td><a href="#" id="tdfooter">Noticias / Blog</a></td>
                <td><a href="#" id="tdfooter">Centro de soporte</a></td>
                <td><a href="#" id="tdfooter">Tabaja con nosotros</a></td>
                
            </tr>
            <tr>
                <td><a href="#" id="tdfooter">Caracteristicas</a></td>
                <td><a href="#" id="tdfooter">Capital</a></td>
                <td><a href="#" id="tdfooter">Seguridad</a></td>
            </tr>
        </table>

        

    </footer>
</body>
</html>
