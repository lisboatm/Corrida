# Ponto de Término do Treinamento de Leonardo

## Descrição

Leonardo, um corredor profissional, deseja determinar onde terminará seu treinamento em uma pista circular. Dado o número de metros que ele pretende correr e o comprimento da pista, o programa calcula a posição final na pista após o treinamento.

## Objetivo

Calcular o ponto de término do treinamento de Leonardo em uma pista circular com base na distância que ele deseja correr.

## Entrada

A entrada consiste em uma única linha contendo dois inteiros:

- `C`: um número inteiro representando os metros que Leonardo pretende correr (1 ≤ C ≤ 10^8).
- `N`: um número inteiro representando o comprimento da pista em metros (1 ≤ N ≤ 100).

## Saída

A saída deve ser um único inteiro que representa o ponto de término do treinamento de Leonardo, indicando a distância em metros entre o ponto de partida e o local onde ele termina.

## Exemplo

### Exemplo de Entrada 1

```
7000 100
```

### Exemplo de Saída 1

```
0
```

### Exemplo de Entrada 2

```
918 76
```

### Exemplo de Saída 2

```
6
```

## Como Executar

Para executar o programa, siga os passos abaixo:

1. Certifique-se de ter o Python instalado em sua máquina.
2. Crie um arquivo Python (por exemplo, `treinamento.py`) e cole o seguinte código:

```python
# Leitura dos valores de C e N
C, N = map(int, input().split())

# Cálculo do ponto de término
ponto_de_termino = C % N

# Impressão do resultado
print(ponto_de_termino)
```

3. Execute o programa a partir do terminal ou prompt de comando:

```bash
python treinamento.py
```

4. Insira os valores de entrada quando solicitado.

## Considerações

- O comprimento da pista deve ser maior que zero, e Leonardo não pode correr zero ou uma distância negativa.
- O programa assume que os dados de entrada estão no formato correto.

## Licença

Este projeto é de domínio público. Você pode usar, modificar e distribuir conforme necessário.
