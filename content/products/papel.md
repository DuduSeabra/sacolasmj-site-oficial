---
title: "Sacolas de papel"
date: 2024-02-15T11:45:07-03:00
draft: false
description: Sacolas de papel personalizáveis de diferentes tamanhos.
---


## Sacola semijoias

<img src="/img/products/semijoia.jpeg" alt="Sacola pp" title="Sacola pp" style="width: 450px; height: auto;">

<p>* O preço é o mesmo para todos os tamanhos (15x15x7cm, 15x12x7cm ou 9,5x15x7cm)</p>

<select id="tamanho1" onchange="mostrarPreco1()">
  <option value="" selected>Selecione o tamanho</option>
  <option value="pp">Alça cordinha</option>
  <option value="p">Alça de gorgurão</option>
</select>

<div id="preco1"></div>

<script>
  function mostrarPreco1() {
    var tamanhoSelecionado1 = document.getElementById("tamanho1").value;
    var preco1;

    switch (tamanhoSelecionado1) {
      case "pp":
        preco1 = "1000 unidades R$ 2,40<br>" +
                "500 unidades R$ 2,69<br>" +
                "300 unidades R$ 2,77<br>" +
                "200 unidades R$ 3,09";
        break;
      case "p":
        preco1 = "1000 unidades R$ 2,65<br>" +
                "500 unidades R$ 2,85<br>" +
                "300 unidades R$ 3,15<br>" +
                "200 unidades R$ 3,29";
        break;
      default:
        preco1 = "";
    }

    document.getElementById("preco1").innerHTML = preco1;
  }
</script>


## Sacola branca alça de gorgurão

<img src="/img/products/branca-gorgurao.jpeg" alt="Sacola pp" title="Sacola pp" style="width: 450px; height: auto;">

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
        preco2 = "1000 unidades R$ 3,39<br>" +
                "500 unidades R$ 3,69<br>" +
                "300 unidades R$ 3,89<br>" +
                "200 unidades R$ 4,13";
        break;
      case "p":
        preco2 = "1000 unidades R$ 3,69<br>" +
                "500 unidades R$ 3,99<br>" +
                "300 unidades R$ 4,20<br>" +
                "200 unidades R$ 4,39";
        break;
      case "m":
        preco2 = "1000 unidades R$ 3,96<br>" +
                "500 unidades R$ 4,39<br>" +
                "300 unidades R$ 4,69<br>" +
                "200 unidades R$ 4,99";
        break;
      case "g":
        preco2 = "1000 unidades R$ 4,39<br>" +
                "500 unidades R$ 4,59<br>" +
                "300 unidades R$ 4,79<br>" +
                "200 unidades R$ 4,99";
        break;
      default:
        preco2 = "";
    }

    document.getElementById("preco2").innerHTML = preco2;
  }
</script>


## Sacola duplex alça cordinha

<img src="/img/products/duplex-cordinha.jpeg" alt="Sacola pp" title="Sacola pp" style="width: 450px; height: auto;">

<select id="tamanho3" onchange="mostrarPreco3()">
  <option value="" selected>Selecione o tamanho</option>
  <option value="pp">PP (22x23x10cm)</option>
  <option value="p">P (32x23x10cm)</option>
  <option value="m">M (35x29x11cm)</option>
  <option value="g">G (42x35x12cm)</option>
</select>

<div id="preco3"></div>

<script>
  function mostrarPreco3() {
    var tamanhoSelecionado3 = document.getElementById("tamanho3").value;
    var preco3;

    switch (tamanhoSelecionado3) {
      case "pp":
        preco3 = "1000 unidades R$ 3,39<br>" +
                "500 unidades R$ 3,69<br>" +
                "300 unidades R$ 3,89<br>" +
                "200 unidades R$ 4,13";
        break;
      case "p":
        preco3 = "1000 unidades R$ 3,69<br>" +
                "500 unidades R$ 3,99<br>" +
                "300 unidades R$ 4,20<br>" +
                "200 unidades R$ 4,39";
        break;
      case "m":
        preco3 = "1000 unidades R$ 3,96<br>" +
                "500 unidades R$ 4,39<br>" +
                "300 unidades R$ 4,69<br>" +
                "200 unidades R$ 4,99";
        break;
      case "g":
        preco3 = "1000 unidades R$ 4,39<br>" +
                "500 unidades R$ 4,59<br>" +
                "300 unidades R$ 4,79<br>" +
                "200 unidades R$ 4,99";
        break;
      default:
        preco3 = "";
    }

    document.getElementById("preco3").innerHTML = preco3;
  }
</script>

