INDICE 
20:00 -
________________________________________
1) index.html
2) Estructura Carpetas
3) Llenar carpeta IMG con recursos 
└──(NOTA: LLEVA TIEMPO BUSCAR IMAGENES: PREGUNTAR A IA PARA AHORRAR TIEMPO...
    PRODUCTOS: ?JPG, IMAGENES TRANSPARENCIA, !JPG)
3.1) OPCIONAL: Crear carpetas pasra productos y para Iconos
4) + paginas CONTACTO Y CARRITO
5) index =>Estruct HMF
6) crear css/styles.css
7) crear 	link a CSS (linea 10)
7.1) crear link a CSS Google font (linea 7)
=============BODY!!!===================
8)Div>a"logo"
8.1) +class="div-logo"
8.2) +class="logo"
9)NAV>UL>li*3>a
9.1) +class="header-nav"
=============MAIN!!!===================

10) section>h1+p
10.1)section.inicio>h1{Bienvenido a la tienda}+p{lorem}

11) section>h2+div>article>img+h3+p+p+button
11.1)NO RECOMENDADO
h2.titulo-productos_text-secondary
div.contenedor-tarjetasarticle.card_text-dark
button.btn_bg-secondary_text-dark{Agregar al carrito}

==========FOOTER!!==============

12)footer>p>nav>ul>li*2>img

============CSS!!===============


=========CSS PRINCIPAL==========
13) *     {M:0;P:0;BS:BB}
14) html  {font-size:62,5%;} === 1 REM = 10px
15) body{font-family: "Poppins", sans-serif;
  font-size:1.6rem;
  background-color: #6e5a8e;
  color: #fff7fb;

  display:flex;
  flex-direction:column;
  min-height:100vh;
}

  display:flex;
  flex-direction:column;
  min-height:100vh;}

16)main{
  width:80%;
  margin: auto;
  padding-bottom: 2rem;


  flex:1;
  display: flex;
  flex-direction:column;
  align-items: center;

}

=========CSS COLORES==========

.bg-primary{
  background-color: #6e5a8e;
}

.bg-secondary{
  background-color: pink;
}

.text-light{
  color: #ffffff;
}

.text-dark{
  color: #2a1e35;
}

.text-secondary{
  color:#f2c66d;
}

====CSS SELECTORES H1, H2======
________________________________________
1) index.html

2) Estructura Carpetas
css
img
paginas

3) Llenar carpeta IMG con recursos 
6 IMG
├──4 Productos
└──2 Social & WhatsApp

3.1) OPCIONAL: Crear carpetas para productos y para Iconos
img
├──productos
└──iconos

4) + paginas CONTACTO Y CARRITO
Solo poner estructura !

5) index =>Estruct Header Main Footer

6) crear css/styles.css

7) crear link a CSS 
    (linea 10)
	<link rel="stylesheet" href="css/estilos.css">
    NOTA: poner despues de estilos importados desde fuentes externas, como backup
_______________________________________

NOTAS extra

las paginas solo contienen el html con sus Clases.
Esto significa que el CSS y las imagenes per-se estan en otro lado

Navegacion
Etiquetas
Enlaces
Demás

_______________________________________

Nota para profesora.
Agregué estructura extra a carpetas img.

