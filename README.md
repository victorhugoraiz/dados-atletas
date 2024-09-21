Este projeto implementa uma classe Atleta em JavaScript capaz de gerenciar informações de atletas, calcular parâmetros importantes e exibi-los para o usuário. Foi desenvolvido como parte de um desafio de programação para demonstrar habilidades em orientação a objetos e manipulação de dados em JavaScript.

A classe Atleta possui os seguintes atributos:

Nome
Idade
Peso
Altura
Notas

E os seguintes métodos:

calculaCategoria(): Determina a categoria do atleta com base na idade
calculaIMC(): Calcula o Índice de Massa Corporal (IMC) do atleta
calculaMediaValida(): Calcula a média válida das notas do atleta
Métodos para obter cada um dos atributos e cálculos

Como Usar

Clone este repositório:
Copygit clone https://github.com/seu-usuario/dados-atletas.git

Navegue até o diretório do projeto:
Copycd dados-atletas

Abra o arquivo dados-atletas.js em seu editor de código 
Para usar a classe Atleta, crie uma instância com os dados do atleta:
javascriptCopyconst atleta = new Atleta("Nome do Atleta", idade, peso, altura, [nota1, nota2, nota3, nota4, nota5])
