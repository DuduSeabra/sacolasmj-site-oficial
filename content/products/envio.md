---
title: "Sacos de envio"
date: 2024-02-21T22:25:07-03:00
draft: false
description: Sacos de envio com a sua logo.
---

<p>* O valor dos sacos de envio inclui a personalização com a sua logo em um único lado e em uma cor.</p>

<img src="/img/products/envio.jpeg" alt="Sacola pp" title="Sacola pp" style="width: 450px; height: auto;">

<select id="tamanho1" onchange="mostrarPreco1()">
  <option value="" selected>Selecione o tamanho</option>
  <option value="pp">32x40cm</option>
  <option value="p">40x50cm</option>
</select>

<div id="preco1"></div>

<script>
  function mostrarPreco1() {
    var tamanhoSelecionado1 = document.getElementById("tamanho1").value;
    var preco1;

    switch (tamanhoSelecionado1) {
      case "pp":
        preco1 = "500 unidades R$ 1,66<br>" +
                "350 unidades R$ 1,79<br>" +
                "250 unidades R$ 1,99<br>";
        break;
      case "p":
        preco1 = "500 unidades R$ 2,60<br>" +
                "350 unidades R$ 2,70<br>" +
                "250 unidades R$ 2,90<br>";
        break;
      default:
        preco1 = "";
    }

    document.getElementById("preco1").innerHTML = preco1;
  }
</script>

