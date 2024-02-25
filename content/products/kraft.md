---
title: "Sacolas de papel kraft"
date: 2024-02-21T22:22:07-03:00
draft: false
description: Sacolas kraft de diversos tamanhos e finalidades.
---

## Sacola kraft alça cordinha

<img src="/img/products/kraft-cordinha.jpeg" alt="Sacola pp" title="Sacola pp" style="width: 450px; height: auto;">

<select id="tamanho1" onchange="mostrarPreco1()">
  <option value="" selected>Selecione o tamanho</option>
  <option value="pp">PP (22x23x10cm)</option>
  <option value="p">P (32x23x10cm)</option>
  <option value="m">M (35x29x11cm)</option>
  <option value="g">G (42x35x12cm)</option>
</select>

<div id="preco1"></div>

<script>
  function mostrarPreco1() {
    var tamanhoSelecionado1 = document.getElementById("tamanho1").value;
    var preco1;

    switch (tamanhoSelecionado1) {
      case "pp":
        preco1 = "1000 unidades R$ 2,99<br>" +
                "500 unidades R$ 3,29<br>" +
                "300 unidades R$ 3,59<br>" +
                "200 unidades R$ 3,75";
        break;
      case "p":
        preco1 = "1000 unidades R$ 3,05<br>" +
                "500 unidades R$ 3,44<br>" +
                "300 unidades R$ 3,64<br>" +
                "200 unidades R$ 3,78";
        break;
      case "m":
        preco1 = "1000 unidades R$ 3,38<br>" +
                "500 unidades R$ 3,64<br>" +
                "300 unidades R$ 3,84<br>" +
                "200 unidades R$ 3,99";
        break;
      case "g":
        preco1 = "1000 unidades R$ 3,77<br>" +
                "500 unidades R$ 3,99<br>" +
                "300 unidades R$ 4,17<br>" +
                "200 unidades R$ 4,53";
        break;
      default:
        preco1 = "";
    }

    document.getElementById("preco1").innerHTML = preco1;
  }
</script>

## Sacola kraft alça gorgurão

<img src="/img/products/kraft-gorgurao.jpeg" alt="Sacola pp" title="Sacola pp" style="width: 450px; height: auto;">

<select id="tamanho2" onchange="mostrarPreco2()">
  <option value="" selected>Selecione o tamanho</option>
  <option value="pp">PP (22x23x10cm)</option>
  <option value="p">P (32x23x10cm)</option>
  <option value="m">M (35x29x11cm)</option>
  <option value="g">G (42x35x12cm)</option>
</select>

<div id="preco2"></div>

<script>
  function mostrarPreco2() {
    var tamanhoSelecionado2 = document.getElementById("tamanho2").value;
    var preco2;

    switch (tamanhoSelecionado2) {
      case "pp":
        preco2 = "1000 unidades R$ 2,99<br>" +
                "500 unidades R$ 3,29<br>" +
                "300 unidades R$ 3,59<br>" +
                "200 unidades R$ 3,75";
        break;
      case "p":
        preco2 = "1000 unidades R$ 3,05<br>" +
                "500 unidades R$ 3,44<br>" +
                "300 unidades R$ 3,64<br>" +
                "200 unidades R$ 3,78";
        break;
      case "m":
        preco2 = "1000 unidades R$ 3,38<br>" +
                "500 unidades R$ 3,64<br>" +
                "300 unidades R$ 3,84<br>" +
                "200 unidades R$ 3,99";
        break;
      case "g":
        preco2 = "1000 unidades R$ 3,77<br>" +
                "500 unidades R$ 3,99<br>" +
                "300 unidades R$ 4,17<br>" +
                "200 unidades R$ 4,53";
        break;
      default:
        preco2 = "";
    }

    document.getElementById("preco2").innerHTML = preco2;
  }
</script>


## Sacola kraft promocional

<img src="/img/products/kraft-promo.jpeg" alt="Sacola pp" title="Sacola pp" style="width: 450px; height: auto;">

<select id="tamanho4" onchange="mostrarPreco4()">
  <option value="" selected>Selecione o tamanho</option>
  <option value="p">P (18x23x11cm)</option>
  <option value="m">M (24x32x11,5cm)</option>
  <option value="g">G (31x39x13,5cm)</option>
</select>

<div id="preco4"></div>

<script>
  function mostrarPreco4() {
    var tamanhoSelecionado4 = document.getElementById("tamanho4").value;
    var preco4;

    switch (tamanhoSelecionado4) {
      case "p":
        preco4 = "1000 unidades R$ 1,47<br>" +
                "500 unidades R$ 1,57<br>" +
                "300 unidades R$ 1,67<br>" +
                "200 unidades R$ 1,87";
        break;
      case "m":
        preco4 = "1000 unidades R$ 1,55<br>" +
                "500 unidades R$ 1,65<br>" +
                "300 unidades R$ 1,75<br>" +
                "200 unidades R$ 1,95";
        break;
      case "g":
        preco4 = "1000 unidades R$ 1,65<br>" +
                "500 unidades R$ 1,75<br>" +
                "300 unidades R$ 1,85<br>" +
                "200 unidades R$ 2,05";
        break;
      default:
        preco4 = "";
    }

    document.getElementById("preco4").innerHTML = preco4;
  }
</script>