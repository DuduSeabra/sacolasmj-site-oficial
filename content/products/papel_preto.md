---
title: "Sacolas de papel preto"
date: 2023-08-21T15:36:07-03:00
draft: false
description: Sacolas de papel preto personalizáveis de diferentes tamanhos.
---

<p>* O valor das sacolas inclui a personalização com a sua logo dos dois lados e em uma cor.</p>

## Sacola preta promoção

<img src="/img/products/kraft-preta.jpeg" alt="Sacola pp" title="Sacola pp" style="width: 450px; height: auto;">

<select id="tamanho3" onchange="mostrarPreco3()">
  <option value="" selected>Selecione o tamanho</option>
  <option value="p">P (18x23x11cm)</option>
  <option value="m">M (24x32x11,5cm)</option>
  <option value="g">G (30x39x13,5cm)</option>
</select>

<div id="preco3"></div>

<script>
  function mostrarPreco3() {
    var tamanhoSelecionado3 = document.getElementById("tamanho3").value;
    var preco3;

    switch (tamanhoSelecionado3) {
      case "p":
        preco3 = "1000 sacolas: R$ 2,02 por unidade<br>" +
                "500 sacolas: R$ 2,12 por unidade<br>" +
                "300 sacolas: R$ 2,22 por unidade<br>" +
                "200 sacolas: R$ 2,42 por unidade";
        break;
      case "m":
        preco3 = "1000 sacolas: R$ 2,10 por unidade<br>" +
                "500 sacolas: R$ 2,20 por unidade<br>" +
                "300 sacolas: R$ 2,30 por unidade<br>" +
                "200 sacolas: R$ 2,50 por unidade";
        break;
      case "g":
        preco3 = "1000 sacolas: R$ 2,22 por unidade<br>" +
                "500 sacolas: R$ 2,32 por unidade<br>" +
                "300 sacolas: R$ 2.42 por unidade<br>" +
                "200 sacolas: R$ 2,62 por unidade";
        break;
      default:
        preco3 = "";
    }

    document.getElementById("preco3").innerHTML = preco3;
  }
</script>

