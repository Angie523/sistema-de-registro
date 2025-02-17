// El principal objetivo de este desafío es fortalecer tus habilidades en lógica de programación. Aquí deberás desarrollar la lógica para resolver el problema.
let input = document.getElementById("amigo");
let lista = document.getElementById(listaAmigos);
let amigoAleatorio = document.getElementById("button-add");


function sortearAmigo() {
    if (amigos.length !== 0) {
       let amigoAleatorio = Math.floor(Math.random() * amigos.length);
       
       let amigo = amigos[amigoAleatorio];

       let li = document.createElement('li');

       li.textContent = `Tu amigo secreto es ${amigo}`;

       document.getElementById('resultado').append(li);

       eliminarAmigoDeListaYArray(amigo);

       setTimeout(() => {
         li.remove();
        },4000);
        actualizarBoton();
    } else {
      actualizarBoton();
        alert("Por favor, ingresa un nombre válido.");
        return;
    }
}
