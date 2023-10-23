<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>Cuidado Personal</title>
  <link rel="stylesheet" href="https://github.com/googlefonts/roboto.git">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/css/bootstrap.min.css">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/js/bootstrap.min.js"></script>

  <style type="text/css">
    body {
      font-family: "roboto", sans-serif;
      line-height: 1.5;
      background-color: rgb(253, 237, 239, 1.0);
      overflow: auto;
    }

    header, .cabecera {
      top: 0px;
      position: fixed;
      margin: 0;
      width: 100vw; /* 100% el ancho de la pantalla*/
      text-align: left;
      overflow: auto;
      display: flex;
      align-items: center;

    }
    img {
      width: 85px;
      margin-left: 0px;
      position: absolute;
      left: 92vw;

    }

    header, h1 {
      color: rgb(160, 70, 104, 1.0) ;
      font-size: 50px;
      background-color: rgb(224, 184, 199, 1.0);
      margin: 0;
      height: 100px;
      flex: 1;

    }

    .menu {
      justify-content: space-around; 
      position:fixed;
      text-align: right;
      top: 100px;
      width: 100vw; /* 100% el ancho de la pantalla*/
      padding-bottom: 20px;
    }

    .articulos{
      display: flex;
      flex-direction: column; /* o row, dependiendo de la orientación que desees */
      padding-top: 20px;
      gap: 20px;
    }

    ol, li, a:visited, td{
      color: rgb(160, 70, 104, 1.0);
    }

    nav a {
      text-decoration: none;
    }

    h2, a:link, #colegio-pie {
      color: rgb(92, 92, 107, 1.0);
    }

    a:visited {
      color: rgb(160, 70, 104, 1.0);
    }

    a:hover,ul,ol,th, #gmail-pie {
      color: rgb(132, 135, 174, 1.0);
    }



    em {
      color: rgb(206, 109, 139, 1.0);
    }

    table {
      width: 80%;
      margin: 0 auto;
    }

    th, td {
      padding: 10px;
      text-align: center;
      border: 1px solid #ccc;
    }

    th {
      font-size: 23px;
      background-color: rgb(193, 195, 215, 1.0);
    }

    .pie-de-pagina {
      background-color: rgb(224, 184, 199, 1.0);
      text-align: center;
    }



    #list-menu-ul {
      margin: 0px 20px 0px 0px;
      background-color: rgba(189, 189, 199, 0.5);
    }

    .list-menu-li {
      list-style: none;
      display: inline-block;
      padding: 15px;
    }

    #strong-rosado, #nombre-pie {
      color: rgb(206, 109, 139, 1.0);
    }

    #importante {
      font-size: 25px;
    }

    .parrafo-inf-bas {
      font-size: 22px;
    }
    

    .indice {
      margin-top: 160px;
      width: 50vw;
      padding: 10px;
      border-style: dotted;
      border-color: rgb(206, 109, 139, 1.0);
      background-color: whitesmoke;
    }

  </style>

</head>

<body id="ini">

  <div class="cabecera"> 
    <header>
        <img src= "https://cdn.picrew.me/shareImg/org/202309/1108773_nloS03Dk.png" alt="Este es mi avatar">
        <h1>Cuidado Personal</h1> 
    </header>
  </div>

  <div class="menu">
      <nav>
        <div class="lista">
          <ul id="list-menu-ul">
            <li class="list-menu-li"><a href="#ind-tem">Temas</a></li>
            <li class="list-menu-li"><a href="#inf-bas-art">Informacion basica</a></li>
            <li class="list-menu-li"><a href="#lis-pro-art">Lista de productos</a></li>
            <li class="list-menu-li"><a href="#pag-sob-tem-art">Paginas sobre el tema</a></li>
            <li class="list-menu-li"><a href="#pie-pag">Contacto</a></li>
          </ul>
        </div>
    </nav>          
  </div>

  <div class ="articulos">
    
    <div class="indice">
      <section> 
          <h2 id="ind-tem">Temas</h2>
            <ul>
              <li>Higiene personal</li>
              <li>Cuidado facial</li>
              <li>Cuidado del cabello</li>
              <li>Cuidado de la piel</li>
              <li>Cuidado bucal</li>
              <li>Cuidado de las manos y pies</li>
              <li>Cuidado de la ropa</li>
              <li>Cuidado de la alimentación</li>
              <li>Cuidado del sueño</li>
              <li>Cuidado emocional y mental</li>
            </ul>

      </section>
    </div>  
    
    <section>
      <article id="inf-bas-art">
        <h2>Informacion basica</h2>
        <p class="parrafo-inf-bas">
          El cuidado personal es un conjunto de hábitos 
          y prácticas destinadas a <strong id="strong-rosado">mantener y promover la 
          salud y el bienestar de una persona.</strong id="strong-rosado"> Incluye 
          actividades como la higiene personal, el cuidado 
          de la piel y el cabello, la nutrición equilibrada, 
          el ejercicio regular y el descanso adecuado.
        </p>
        <p class="parrafo-inf-bas">El cuidado personal no solo afecta nuestra apariencia 
          física, sino también nuestra <strong id="strong-rosado">salud mental y 
          emocional</strong id="strong-rosado">, ya que puede ayudar a <em>aumentar</em> la 
          autoestima y la confianza en uno mismo. Es esencial 
          incorporar una rutina de cuidado personal en la vida 
          diaria para mantener un estilo de vida saludable y 
          sentirse bien consigo mismo.
        </p>
      </article>
      
      <article id="lis-pro-art">
        <h2>Lista de productos</h2>
        <table cellspacing="0">
          <tr>
              <th>higiene personal</th>
              <th>cuidado facial</th>
              <th>cuidado cabello</th>
              <th>cuidado de piel</th>
              <th>cuidado bucal</th>
              <th>cuidado manos y pies</th>
              <th>cuidado ropa</th>
          </tr>
          <tr>
              <td>Jabón o gel de baño.</td>
              <td>Limpiador facial.</td>
              <td>Champú para tu tipo de cabello.</td>
              <td>Protector solar corporal.</td>
              <td>Cepillo de dientes.</td>
              <td>Crema de manos.</td>
              <td>Detergente para ropa.</td>
          </tr>
          <tr>
              <td>Jabón de manos.</td>
              <td>Tónico facial.</td>
              <td>Acondicionador.</td>
              <td>Crema hidratante corporal.</td>
              <td>Pasta dental.</td>
              <td>Lima de uñas.</td>
              <td>Suavizante de telas.</td>
          </tr>
          <tr>
              <td>Esponja o lufa para la ducha.</td>
              <td>Crema hidratante facial.</td>
              <td>Mascarilla capilar (para un cuidado adicional).</td>
              <td>Exfoliante corporal.</td>
              <td>Hilo dental.</td>
              <td>Cortauñas.</td>
              <td>Quitamanchas (según sea necesario).</td>
          </tr>
          <tr>
              <td>Toallas limpiadoras para el cuerpo.</td>
              <td>Protector solar facial.</td>
              <td>Aceite capilar (para cabello seco o dañado).</td>
              <td>Aceite o loción para masajes (opcional).</td>
              <td>Enjuague bucal.</td>
              <td>Crema hidratante para pies.</td>
              <td>Plancha y tabla de planchar.</td>
          </tr>
          <tr>
              <td></td>
              <td>Exfoliante facial.</td>
              <td>Cepillo para desenredar.</td>
              <td>Cremas antienvejecimiento(según necesidades individuales).</td>
              <td>Raspador de lengua (opcional).</td>
              <td></td>
              <td>Perchas o organizadores de armario.</td>
          </tr>
          <tr>
              <td></td>
              <td>Mascarillas faciales.</td>
              <td></td>
              <td>Tratamientos para el acné(según necesidades individuales).</td>
              <td></td>
              <td></td>
              <td>Bolsas de lavado para prendas delicadas (opcional).</td>
          </tr>
          <tr>
              <td></td>
              <td>Sérum facial (opcional).</td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
          </tr>
        </table>
      </article>
      
      <article id="pag-sob-tem-art">
        <h2>Paginas sobre el tema:</h2>
        <p>Estas paginas externas te ayudaran a informarte mas sobre el tema y descubrir mas información.<br></p>
        <p id="importante"><strong id="strong-rosado">IMPORTANTE:</strong> <em>Antes de usar algun producto, tip, etc que leeas en internet, investiga bien para que no tengas un resultado contraproducente.</em></p>
        <ol>
          <li><a href="https://theskincareedit.com/">The Skincare Edit</a><br></li>
          <li><a href="https://www.allure.com/">Allure</a><br></li>
          <li><a href="https://www.makeupalley.com/">MakeupAlley</a><br></li>
          <li><a href="https://dermnetnz.org/">DermNet NZ</a></li>
        </ol>
      </article>
    </section>
  </div> 

  <div class="pie-de-pagina">
    <footer id="pie-pag">
      <button class="btn btn-primary"><a href="#ini">Volver al inicio</a></button>
      <strong><p id="nombre-pie" class ="centrado">Martina Hidalgo Clavero</strong>
      <strong><p id="gmail-pie" class ="centrado">martinahid@gmail.com</p></strong>
      <strong><p id="colegio-pie" class="centrado">Skolmi</p></strong>
      <p class="text-muted">© 2023 Sitio Web de Martina Hidalgo. Todos los derechos reservados</p>
    </footer>
  </div>

</body>
</html>
