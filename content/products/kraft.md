---
title: "Sacolas de papel kraft"
date: 2024-02-21T22:22:07-03:00
draft: false
description: Sacolas kraft de diversos tamanhos e finalidades.
---

<p>* O valor das sacolas inclui a personalização com a sua logo dos dois lados e em uma cor.</p>

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
  <option value="g">G (30x39x13,5cm ou 30x31x19cm)</option>
</select>

<div id="preco4"></div>

<script>
  function mostrarPreco4() {
    var tamanhoSelecionado4 = document.getElementById("tamanho4").value;
    var preco4;

    switch (tamanhoSelecionado4) {
      case "p":
        preco4 = "1000 unidades R$ 1,57<br>" +
                "500 unidades R$ 1,67<br>" +
                "300 unidades R$ 1,77<br>" +
                "200 unidades R$ 1,97";
        break;
      case "m":
        preco4 = "1000 unidades R$ 1,65<br>" +
                "500 unidades R$ 1,75<br>" +
                "300 unidades R$ 1,85<br>" +
                "200 unidades R$ 2,05";
        break;
      case "g":
        preco4 = "1000 unidades R$ 1,75<br>" +
                "500 unidades R$ 1,85<br>" +
                "300 unidades R$ 1,95<br>" +
                "200 unidades R$ 2,15";
        break;
      default:
        preco4 = "";
    }

    document.getElementById("preco4").innerHTML = preco4;
  }
</script>

<br>

<button id="whatsapp-button" class="bg-green-500 hover:bg-green-600 text-black font-semibold py-2 px-4 rounded flex">
  Faça um Pedido!<svg xmlns="http://www.w3.org/2000/svg" width="40" height="30" fill="currentColor" class="bi bi-whatsapp whatsapp-logo" viewBox="0 0 16 16">
    <path d="M13.601 2.326A7.85 7.85 0 0 0 7.994 0C3.627 0 .068 3.558.064 7.926c0 1.399.366 2.76 1.057 3.965L0 16l4.204-1.102a7.9 7.9 0 0 0 3.79.965h.004c4.368 0 7.926-3.558 7.93-7.93A7.9 7.9 0 0 0 13.6 2.326zM7.994 14.521a6.6 6.6 0 0 1-3.356-.92l-.24-.144-2.494.654.666-2.433-.156-.251a6.56 6.56 0 0 1-1.007-3.505c0-3.626 2.957-6.584 6.591-6.584a6.56 6.56 0 0 1 4.66 1.931 6.56 6.56 0 0 1 1.928 4.66c-.004 3.639-2.961 6.592-6.592 6.592m3.615-4.934c-.197-.099-1.17-.578-1.353-.646-.182-.065-.315-.099-.445.099-.133.197-.513.646-.627.775-.114.133-.232.148-.43.05-.197-.1-.836-.308-1.592-.985-.59-.525-.985-1.175-1.103-1.372-.114-.198-.011-.304.088-.403.087-.088.197-.232.296-.346.1-.114.133-.198.198-.33.065-.134.034-.248-.015-.347-.05-.099-.445-1.076-.612-1.47-.16-.389-.323-.335-.445-.34-.114-.007-.247-.007-.38-.007a.73.73 0 0 0-.529.247c-.182.198-.691.677-.691 1.654s.71 1.916.81 2.049c.098.133 1.394 2.132 3.383 2.992.47.205.84.326 1.129.418.475.152.904.129 1.246.08.38-.058 1.171-.48 1.338-.943.164-.464.164-.86.114-.943-.049-.084-.182-.133-.38-.232"/></svg>
</button>

<script>
  document.getElementById('whatsapp-button').addEventListener('click', function() {
      window.location.href = 'https://api.whatsapp.com/send?1=pt_BR&phone=5524999043166';
  });
</script>