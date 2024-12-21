# If-Window
if with window and prompts

var pergunta = window.confirm("Se seu numero for inteiro aperte ok");

if (pergunta == true) {
 
    var n1 = Number.parseInt(window.prompt("Digite um número"));
    var n2 = Number.parseInt(window.prompt("Digite outro número"));
    var s = n1 + n2;
    window.alert("A soma dos números inteiros é: " + s);
} else {

    var n3 = Number.parseFloat(window.prompt("Digite um número"));
    var n4 = Number.parseFloat(window.prompt("Digite outro número"));
    var s = n3 + n4;
    window.alert("A soma dos números float é: " + s);
}
