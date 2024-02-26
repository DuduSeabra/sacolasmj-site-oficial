---
title: "Sacolas de plástico"
date: 2024-02-15T11:45:07-03:00
draft: false
description: Sacolas plásticas personalizáveis de diferentes modelos e tamanhos.
---


<p>* O valor das sacolas inclui a personalização com a sua logo em um único lado e em uma cor.</p>


## Sacola alça cadeado

<img src="/img/products/alca-cadeado.jpeg" alt="Sacola pp" title="Sacola pp" style="width: 450px; height: auto;">

<select id="tamanho1" onchange="mostrarPreco1()">
  <option value="" selected>Selecione o tamanho</option>
  <option value="pp">30x55x0,12</option>
  <option value="p">40x60x0,12</option>
</select>

<div id="preco1"></div>

<script>
  function mostrarPreco1() {
    var tamanhoSelecionado1 = document.getElementById("tamanho1").value;
    var preco1;

    switch (tamanhoSelecionado1) {
      case "pp":
        preco1 = "1000 unidades R$ 0,86<br>" +
                "500 unidades R$ 0,97<br>";
        break;
      case "p":
        preco1 = "1000 unidades R$ 1,03<br>" +
                "500 unidades R$ 1,14<br>";
        break;
      default:
        preco1 = "";
    }

    document.getElementById("preco1").innerHTML = preco1;
  }
</script>


## Sacola alça camiseta

<img src="/img/products/alca-camiseta.jpeg" alt="Sacola pp" title="Sacola pp" style="width: 450px; height: auto;">

<select id="tamanho2" onchange="mostrarPreco2()">
  <option value="" selected>Selecione o tamanho</option>
  <option value="pp">45x50x0,07</option>
  <option value="p">45x60x0,07</option>
  <option value="m">60x75x0,07</option>
  <option value="g">45x50x0,10</option>
  <option value="xg">45x60x0,10</option>
  <option value="xxg">60x75x0,10</option>
</select>

<div id="preco2"></div>

<script>
  function mostrarPreco2() {
    var tamanhoSelecionado2 = document.getElementById("tamanho2").value;
    var preco2;

    switch (tamanhoSelecionado2) {
      case "pp":
        preco2 = "1000 unidades R$ 0,75<br>" +
                "500 unidades R$ 0,86<br>";
        break;
      case "p":
        preco2 = "1000 unidades R$ 0,84<br>" +
                "500 unidades R$ 0,95<br>";
        break;
      case "m":
        preco2 = "1000 unidades R$ 1,07<br>" +
                "500 unidades R$ 1,18<br>";
        break;
      case "g":
        preco2 = "1000 unidades R$ 0,88<br>" +
                "500 unidades R$ 0,99<br>";
        break;
      case "xg":
        preco2 = "1000 unidades R$ 0,95<br>" +
                "500 unidades R$ 1,06<br>";
        break;
      case "xxg":
        preco2 = "1000 unidades R$ 1,25<br>" +
                "500 unidades R$ 1,36<br>";
        break;
      default:
        preco2 = "";
    }

    document.getElementById("preco2").innerHTML = preco2;
  }
</script>


## Sacola boca de palhaço

<img src="/img/products/boca-palhaco.jpeg" alt="Sacola pp" title="Sacola pp" style="width: 450px; height: auto;">

<select id="tamanho3" onchange="mostrarPreco3()">
  <option value="" selected>Selecione o tamanho</option>
  <option value="pp">15x20x0,07</option>
  <option value="p">20x30x0,07</option>
  <option value="m">25x30x0,07</option>
  <option value="g">30x40x0,07</option>
  <option value="xg">40x50x0,07</option>
  <option value="xxg">15x20x0,12</option>
  <option value="xxxg">20x30x0,12</option>
  <option value="xxxxg">25x30x0,12</option>
  <option value="xxxxxg">30x40x0,12</option>
  <option value="xxxxxxg">40x50x0,12</option>
</select>

<div id="preco3"></div>

<script>
  function mostrarPreco3() {
    var tamanhoSelecionado3 = document.getElementById("tamanho3").value;
    var preco3;

    switch (tamanhoSelecionado3) {
      case "pp":
        preco3 = "1000 unidades R$ 0,51<br>" +
                "500 unidades R$ 0,62<br>";
        break;
      case "p":
        preco3 = "1000 unidades R$ 0,56<br>" +
                "500 unidades R$ 0,67<br>";
        break;
      case "m":
        preco3 = "1000 unidades R$ 0,58<br>" +
                "500 unidades R$ 0,69<br>";
        break;
      case "g":
        preco3 = "1000 unidades R$ 0,71<br>" +
                "500 unidades R$ 0,79<br>";
        break;
      case "xg":
        preco3 = "1000 unidades R$ 0,76<br>" +
                "500 unidades R$ 0,88<br>";
        break;
      case "xxg":
        preco3 = "1000 unidades R$ 0,55<br>" +
                "500 unidades R$ 0,66<br>";
        break;
      case "xxxg":
        preco3 = "1000 unidades R$ 0,63<br>" +
                "500 unidades R$ 0,74<br>";
        break;
      case "xxxxg":
        preco3 = "1000 unidades R$ 0,67<br>" +
                "500 unidades R$ 0,78<br>";
        break;
      case "xxxxxg":
        preco3 = "1000 unidades R$ 0,75<br>" +
                "500 unidades R$ 0,86<br>";
        break;
      case "xxxxxxg":
        preco3 = "1000 unidades R$ 0,94<br>" +
                "500 unidades R$ 1,05<br>";
        break;
      default:
        preco3 = "";
    }

    document.getElementById("preco3").innerHTML = preco3;
  }
</script>

