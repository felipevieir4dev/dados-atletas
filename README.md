# Dados de Atletas

Este projeto consiste em um sistema de gerenciamento de dados de atletas implementado em JavaScript. O sistema permite cadastrar e consultar informações sobre atletas, como dados pessoais e medições.

## Funcionalidades

- Cadastro de informações de atletas
- Cálculo de categoria do atleta
- Cálculo do IMC (Índice de Massa Corporal)
- Cálculo da média da validade das medições
- Retorno de dados do atleta em formato estruturado

## Como Usar

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/dados-atletas.git
```

2. Abra o arquivo `dados-atletas.js` em seu editor de código preferido.

3. Para utilizar o sistema, crie uma instância da classe Atleta com os seguintes dados:
```javascript
let atleta = new Atleta(
    "Nome do Atleta",
    "2000-01-01",
    75.0,
    1.75,
    [10, 9.5, 9.8, 9.7, 9.9]
);
```

4. Você pode acessar os métodos disponíveis:
```javascript
atleta.calculaCategoria();
atleta.calculaIMC();
atleta.calculaMediaValida();
atleta.obtemNomeAtleta();
atleta.obtemIdadeAtleta();
atleta.obtemPeso();
atleta.obtemAltura();
atleta.obtemNotas();
```

## Estrutura do Projeto

- `dados-atletas.js`: Arquivo principal contendo a implementação da classe Atleta e seus métodos

## Requisitos

- Node.js (para execução do JavaScript)

## Contribuição

Sinta-se à vontade para contribuir com o projeto. Para isso:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`)
3. Faça commit das mudanças (`git commit -m 'Adiciona nova feature'`)
4. Faça push para a branch (`git push origin feature/nova-feature`)
5. Abra um Pull Request

## Licença

Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
