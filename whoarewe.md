---
layout: page
title: "Somos Anonynice"
permalink: /whoarewe.html
description:  "Un grupo de hackers rusos que difunden noticias falsas agradables. Compartimos solo las mentiras más entrañables e inspiradoras. Y las propagamos por cualquier medio necesario..."
image: /img/nfn-1.jpg
---

<style>
article {
    font-size: 1.3em;

}
hr {
  border-color: #BE0712;
}
.content {
  min-width: 100%;
}
.full-width {
  background-color: #0c0c0c;
  color: white;

}
header {
  border-bottom: 3px solid #BE0712;
}

strong {
  color: #BE0712;
}

h1 {

  font-weight: 500;
  letter-spacing: -0.1;
}

a {
  color: #BE0712;
}

/*article img {
  border: 1px solid white;
}*/

</style>


Somos un grupo de hackers rusos que difunden <a href="" >noticias falsas agradables</a>.

Compartimos sólo las mentiras más entrañables e inspiradoras.

Y las propagamos por <a style="cursor: pointer;" onclick="window.scrollTo(0, 700);">cualquier medio necesario...</a>.


Las historias se publican primero en NFN (Nice Fake News)

Después, se promocionan en vuestras redes sociales corruptas <a href="{{ "/donate " | relative_url }}">empleando financiación offshore</a>.

Y finalmente, se difunden por nuestras redes <a href="{{ "/joinus" | relative_url }}">bot y cuentas verificadas secuestradas</a>.

![Nice Fake News](/img/NFN6.jpg)

Lo que exigimos es muy sencillo.

Damos a las agencias de noticias <strong id="thecountdown"></strong> para publicar una historia inspiradora y real en su portada.

De lo contrario, difundiremos otra noticia falsa.

Hasta entonces, comparte un artículo y reparte un poco de alegría.

Atentamente,
<a href="" class="russian">Оли Фрост</a>  
El simpático hacker ruso

<script type="text/javascript">

var countDownDate = new Date("Aug 02, 2018 11:00:00").getTime();


var x = setInterval(function() {


  var now = new Date().getTime();


  var distance = countDownDate - now;


  var days = Math.floor(distance / (1000 * 60 * 60 * 24));
  var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  var seconds = Math.floor((distance % (1000 * 60)) / 1000);


  document.getElementById("thecountdown").innerHTML =  horas + ":"
  + minutos + ":" + segundos;


  if (distance < 0) {
    clearInterval(x);
    document.getElementById("thecountdown").innerHTML = "24 horas";
  }
}, 1000);
</script>
