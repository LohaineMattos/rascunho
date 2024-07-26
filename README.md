alert("Juros Simples");
c = parseFloat(prompt("Digite o valor inicial:"));
i = parseFloat(prompt("Digite a taxa de juros:"));
t = parseFloat(prompt("Digite o período em meses:"));

m = (c * i * t);
console.log("O valor do montante em juros simples é:");
console.log(m);
alert(m);
