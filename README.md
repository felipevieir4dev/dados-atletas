# Dados de Atletas

Este projeto consiste em um sistema desenvolvido em JavaScript para gerenciar e calcular dados de atletas, incluindo IMC, categoria e médias de avaliações.

## Funcionalidades

- Calcula o IMC (Índice de Massa Corporal) dos atletas
- Determina a categoria do atleta
- Calcula a média válida das avaliações
- Fornece informações detalhadas como nome, idade, peso, altura e notas

## Como Usar

1. Clone o repositório:
```bash
git clone https://github.com/felipevieir4dev/dados-atletas.git
```

2. Execute o arquivo JavaScript:
```bash
node dados-atletas.js
```

## Exemplo de Uso

```javascript
let atleta = new Atleta(
    "Nome do Atleta",
    "2000-01-01",
    75.0,
    1.75,
    [10, 9.5, 9.8, 9.7, 9.9]
);

console.log(atleta.calculaIMC());
console.log(atleta.calculaCategoria());
console.log(atleta.calculaMediaValida());
```

## Tecnologias Utilizadas

- JavaScript

## Autor

Felipe Vieira
