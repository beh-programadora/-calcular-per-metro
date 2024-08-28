# Calculador de Perímetro de Retângulo

Este projeto é um script em Python que define uma função para calcular o perímetro de um retângulo com base em suas dimensões fornecidas pelo usuário e exibe o resultado.

## Objetivo

O objetivo deste projeto é criar uma função em Python que:
1. Receba a largura e a altura de um retângulo como argumentos.
2. Calcule o perímetro do retângulo.
3. Exiba o perímetro formatado com duas casas decimais.

O script solicita ao usuário que insira a largura e a altura do retângulo, utiliza a função para calcular o perímetro e exibe o resultado.

## Código

O código consiste em uma função chamada `calcular_perimetro` que calcula o perímetro do retângulo e um trecho de código que lê as dimensões do retângulo, chama a função e exibe o perímetro.

```python
def calcular_perimetro(largura, altura):
    return 2 * (largura + altura)

# Leitura das dimensões 
largura = float(input("Digite a largura do retângulo: "))
altura = float(input("Digite a altura do retângulo: "))

# Chamada da função
perimetro = calcular_perimetro(largura, altura)

# Exibição do perímetro
print(f"O perímetro do retângulo é: {perimetro:.2f}")
Como Executar
1. Certifique-se de ter o Python instalado em seu sistema.

2. Salve o código acima em um arquivo chamado calcular_perimetro.py.

3. Execute o código usando o seguinte comando:
python calcular_perimetro.py
4. Insira a largura e a altura do retângulo quando solicitado e veja o perímetro calculado.

Contribuição
Sinta-se à vontade para fazer sugestões ou melhorias. Se encontrar um problema ou tiver uma ideia para aprimorar o projeto, por favor, abra uma issue ou envie um pull request.

Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.
