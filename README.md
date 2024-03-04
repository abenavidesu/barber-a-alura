<h1><strong>Pagina de la Barbería Alura</strong></h1>
<p><strong>Aplicar conocimientos de GitHub y Git</strong></p>
<p> <strong>Nota:</strong> En este proyecto La pagina web de la Barbería Alura puse en  practica todo lo aprendido en el curso de HTML5 y CSS3 de Alura. Ahora utilizo GitHub para seguir aplicando y practicando conocimiento</p>

-**Bases del poyecto**: Se realizo todos los cambios para adoptar un comportamiento responsivo de la pagina Home y esta pendiente aplicar lo mismo para Productos y contacto. 

-El uso de Github esta destinado ahora para documentar y realizar el commit de lo que se tiene que hacer con las paginas Productos y Contactos aplicando los codigos aprendidos de HTML y CSS de un buen coomportamiento responsivo de la pagina al abrirla desde un dispositivo celular, es decir Voy usar Github, ya que me permite unificar los cambios de todo lo que realice en el procyecto en un solo lugar el repositorio. 

-Estado del proyecto: pendiente modificar las paginas con un buen comportamiento responsivo usando  Meta etiqueta de Viewport Media Queries revisar el comportamiento en el simulardor o consola del programador.

Inciamos:  Abrir Index.html y Style.css desde carpeta que contine todo los archivos de la pagina : 1768-HTML5 y CSS3 parte3-aula0
En Html se relizo lo siguiente para que esta relacionado al comportamiento responsivo:

se incluye el  <meta name="viewport" content="width=device-width">  dentro del head:
<head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width"> 
        <title>Barbería Alura</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
        <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300&display=swap" rel="stylesheet">     
    
    </head>

Y en css se hace uso de  media queris:
@media screen and (max-width:480px) {
    h1{
        text-align: center;
    }
    nav{
        position: static;
    }
    .caja,.principal, .mapa-contenido, .contenido-diferenciales,.video{
        width: auto;
    }  
    .lista-diferenciales, .imagen-diferenciales{
        width: 100%;
    }   
}/*Las media queris lo que hacen es permitirnos trabajar con excepciones o, dada una condición, aplicar algo diferente La forma de definirlas es @ y colocamos media asi @media screem (proque vamos atrabajar con la pantalla seguido de un and ( la medida de la pantalla)  */ 
