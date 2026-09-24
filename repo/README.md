# Organizador de Declaração de Imposto de Renda

Projeto feito para o desafio "Organizador de Declaração de Imposto de Renda" da DIO. A proposta do desafio era construir, usando apenas recursos do Excel, uma ferramenta para organizar as informações necessárias para a declaração de IR, com menu de navegação e validações.

## Sobre o projeto

A planilha tem um menu lateral fixo com logo e botões de navegação, e três abas principais de preenchimento:

- TÍTULAR: dados pessoais do declarante (nome, CPF, contatos, endereço).
- INFORMES: rendimentos bancários, um bloco por banco (nome, valor, anexo do informe).
- NOTAS: extratos e holerites, com tabela de entradas mês a mês.

A navegação entre as abas é feita pelos botões do menu e pelos botões "Próximo"/"Anterior", todos com hyperlink interno. Não usei macro nem VBA, só formas, hyperlinks e formatação nativa do Excel.

## Aba RESUMO

Ao final do desafio, o Felipão sugeriu ir além. Adicionei então uma aba RESUMO, que reúne em uma única tabela os valores das três abas anteriores (tudo por fórmula, referenciando INFORMES e NOTAS, sem número fixo) e um gráfico de colunas mostrando a distribuição das fontes de renda.

## Estrutura do repositório

```
├── README.md
├── images/
│   └── (capturas de tela do projeto)
└── planilha/
    └── Organizador_de_Declaracao_de_Imposto_de_Renda_DIO.xlsx
```

## Créditos

Desafio de projeto proposto pela DIO.

Meu LinkedIn: www.linkedin.com/in/marcio-tarcisio-barros-santos-09b220161