---
title: "Sacolas de TNT ecobags"
date: 2023-07-18T10:31:30-03:00
draft: false
description: Sacolas de tnt personalizáveis.
---

<p>* O valor das sacolas inclui a personalização com a sua logo em um único lado e em uma cor.</p>


## Sacola TNT branco ou preto

<img src="/img/products/sacola-tnt.jpeg" alt="Sacola pp" title="Sacola pp" style="width: 450px; height: auto;">

<select id="tamanho1" onchange="mostrarPreco1()">
  <option value="" selected>Selecione o tamanho</option>
  <option value="p">34x40cm</option>
</select>

<div id="preco1"></div>

<script>
  function mostrarPreco1() {
    var tamanhoSelecionado1 = document.getElementById("tamanho1").value;
    var preco1;

    switch (tamanhoSelecionado1) {
      case "p":
        preco1 = "1000 unidades R$ 3,64<br>" +
                "500 unidades R$ 3,84<br>" +
                "300 unidades R$ 3,94<br>";
        break;
      default:
        preco1 = "";
    }

    document.getElementById("preco1").innerHTML = preco1;
  }
</script>

