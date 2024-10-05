
# Comparador de Preços de Combustíveis

Este desenvolvimento se baseou no 1° problema apresentado da displina MI-Algoritmos, da UEFS(Universidade Estadual de Feira de Santana), que tinha como intuito a absorção do conteudo básico de algoritmos, afim de compreender lógica e sintaxe de programação por meio da metodologia PBL(Problem Based Learning). Este programa foi desenvolvido para comparar os preços de combustíveis (gasolina, etanol e diesel) entre três postos diferentes. Ele permite ao usuário inserir os preços dos combustíveis e calcular o melhor custo-benefício para abastecer, além de fornecer um relatório detalhado dos postos.

## Sumário

- [Instalação](#instalação)
- [Uso](#uso)
- [Funcionalidades](#funcionalidades)
- [Contribuição](#contribuição)
- [Licença](#licença)

## Instalação

Este programa foi desenvolvido em Python 3.11.4 e pode ser executado em sistemas Windows. Para utilizá-lo, siga os passos abaixo:

1. Certifique-se de ter o Python 3.11.4 ou superior instalado em seu sistema.
2. Baixe o código-fonte do programa.
3. Execute o script Python.

```bash
python comparador_combustivel.py
```

## Uso

Ao rodar o programa, o usuário deverá inserir os seguintes dados:

1. Nome e preços da gasolina, etanol e diesel em três diferentes postos.
2. Quantidade de litros que deseja abastecer.
3. O programa fornecerá o melhor posto para abastecimento de acordo com o tipo de combustível selecionado e os preços informados.

Exemplo de execução:

```bash
Insira o nome do 1° posto: Posto A
Insira o preço da gasolina no 1° posto: 5,39
Insira o preço do etanol no 1° posto: 3,79
Insira o preço do diesel no 1° posto: 6,29
...
O melhor custo benefício está no posto Posto A, pagando R$ 53,90 pelo abastecimento.
```

## Funcionalidades

- **Comparação de preços de gasolina, etanol e diesel**: o programa compara os preços entre três postos de combustível diferentes.
- **Validação de dados**: assegura que os valores inseridos são válidos e numéricos.
- **Melhor custo-benefício**: calcula e apresenta ao usuário a melhor opção de posto para abastecer.
- **Relatório detalhado**: exibe um relatório final com as informações de qual posto tem o melhor preço para cada combustível.

### Fluxo do Programa

1. Solicitação de dados do primeiro, segundo e terceiro postos (nome e preços dos combustíveis).
2. Validação de todos os preços inseridos pelo usuário.
3. Exibição de um menu de opções:
    - **1**: Exibir o melhor custo-benefício para abastecimento.
    - **2**: Mostrar a lista de todos os postos e suas informações.
    - **3**: Sair do programa.
4. Cálculo de custos com base no tipo de combustível e quantidade de litros.
5. Exibição de resultados detalhados.

## Contribuição

Contribuições são bem-vindas! Se você deseja sugerir melhorias ou correções, por favor, envie um pull request ou abra uma issue.

## Licença

Este código foi desenvolvido por **João Marcelo Nascimento Fernandes** como parte do componente curricular de **Algoritmos (MI)** e está sob a licença de uso acadêmico. Qualquer uso fora deste contexto deve ser autorizado.

---

**Declaração de Autoria**: Declaro que este código foi elaborado por mim de forma individual e não contém nenhum trecho de código de outro colega ou de outro autor sem a devida citação.
