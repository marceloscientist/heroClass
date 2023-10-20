# Resumo: Classe Hero em JavaScript

## Objetivo
Este código em JavaScript cria a classe `Hero` para representar heróis de uma aventura. Cada herói possui propriedades como nome, idade e tipo, além de um método chamado `atacar` que exibe mensagens de ataque com base no tipo do herói.

## Propriedades
- `nome`: O nome do herói.
- `idade`: A idade do herói.
- `tipo`: O tipo do herói (ex: mago, guerreiro, monge, ninja).

## Método atacar
- O método `atacar` determina o ataque adequado com base no tipo do herói e exibe uma mensagem com o tipo e o ataque usado.
- Mensagens de ataque de acordo com o tipo:
  - Se o tipo for "mago", o ataque é "usou magia".
  - Se o tipo for "guerreiro", o ataque é "usou espada".
  - Se o tipo for "monge", o ataque é "usou artes marciais".
  - Se o tipo for "ninja", o ataque é "usou shuriken".

## Exemplo de Uso
```javascript
// Exemplo de uso da classe Hero
const heroi1 = new Hero("Herói1", 25, "mago");
heroi1.atacar();  // Resultado: "o mago atacou usando magia"

const heroi2 = new Hero("Herói2", 30, "guerreiro");
heroi2.atacar();  // Resultado: "o guerreiro atacou usando espada"
