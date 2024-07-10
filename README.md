# desafio-logica-inicial
Desafio do curso de Lógica de Programação da plataforma DIO.me
A linguagem utilizada foi JavaScript
Defini o nome do herói como Caio_heroi
Como este herói me representa nesta jornada de programação e eu ainda estou iniciando nesta, decidi colocar poucos pontos de experiência a este herói, no caso, 900 pontos.
Essa quantidade de pontos faz com que Caio_heroi esteja no nível ferro.

O código foi executado da seguinte maneira:

// Definindo as variáveis
let nome_personagem = "Caio_Heroi";
let quantidade_exp = 900;
let nivel;

// Verificando o nível baseado na quantidade de experiência
if (quantidade_exp < 1000) {
    nivel = "nível ferro";
  console.clear(); // Limpa o console (opcional)
} else if (quantidade_exp >= 1001 && quantidade_exp <= 2000) {
    nivel = "nível bronze";
  console.clear(); // Limpa o console (opcional)
} else if (quantidade_exp >= 2001 && quantidade_exp <= 5000) {
    nivel = "nível prata";
  console.clear(); // Limpa o console (opcional)
} else if (quantidade_exp >= 5001 && quantidade_exp <= 7000) {
    nivel = "nível ouro";
  console.clear(); // Limpa o console (opcional)
} else if (quantidade_exp >= 7001 && quantidade_exp <= 8000) {
    nivel = "nível platina";
  console.clear(); // Limpa o console (opcional)
} else if (quantidade_exp >= 8001 && quantidade_exp <= 9000) {
    nivel = "nível ascendente";
    console.clear(); // Limpa o console (opcional)
} else if (quantidade_exp >= 9001 && quantidade_exp <= 10000) {
    nivel = "nível imortal";
  console.clear(); // Limpa o console (opcional)
} else if (quantidade_exp >= 10001) {
    nivel = "nível radiante";
  console.clear(); // Limpa o console (opcional)
}
// Exibindo a saída
console.log(`O herói de nome ${nome_personagem} está no ${nivel}`);
