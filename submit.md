---
layout: page
title: Enviar
permalink: /submit.html
description: ¿Tienes alguna sugerencia? Envía una buena noticia falsa a nuestros editores
---

<style>
article {
    font-size: 1.3em;

}
.full-width {
  background-color: #0c0c0c;
  color: white;
}

textarea, input {
  color: white;
  font-size: 1.6rem;
}

header {
  border-bottom: 3px solid #BE0712;
}


</style>

*¿Tienes alguna sugerencia? Envía una noticia falsa a nuestros editores.

<form action="https://formspree.io/mail@olifro.st" method="POST">

  <label for="Message">¿Cuál es la historia?</label>
  <textarea type="text" name="description" rows="20" cols="20" id="Message" placeholder="Tu historia" required></textarea>

  <label for="Email">Contacto (opcional)</label>
  <input type="email" name="replyto"  id="Email" placeholder="">
<input type="hidden" name="_next" value="http://olifro.st/nfn/thanks" />
    <input type="submit" value="Submit" class="submit-button">
</form>
