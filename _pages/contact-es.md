---
permalink: /contactar/
title: "Contactar"
layout: splash
header:
  overlay_color: "#D98E64"
  overlay_image: /assets/images/lqda-header-contactar.png
excerpt: "Si tienes más preguntas, sugerencias... puedes contactar con nosotros"
ref: contact
lang: es
modified: 2017-01-24T09:40:33-05:00
---

<form action="https://formspree.io/libreqda@listas.softwarelibre.edu.uy" method="POST">
  <table width="75%">
    <tr>
      <td>
        Su nombre:
      </td>
      <td>
        <input type="text" name="name">
      </td>
    </tr>
    <tr>
    <td>
    Dirección de Correo:
    </td>
    <td>
    <input type="email" name="_replyto">
    </td>
    </tr>
    <tr>
      <td>
        Asunto:
      </td>
      <td>
        <input type="text" name="_subject" />
      </td>
    </tr>
    <tr>
    <td style="vertical-align:top">
      Su mensaje:
    </td>
    <td valign="top">
      <textarea name="comment" rows="15" cols="45"></textarea>
    </td>
    </tr>
  </table>
    <input type="submit" value="Enviar">
    <input type="text" name="_gotcha" style="display:none" />
    <input type="hidden" name="_next" value="/about/" />
</form>
