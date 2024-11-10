# javascript-loop-function-condicao

# Entrega: SnapCrackle

## Descrição

Neste desafio, você precisará implementar duas funções em JavaScript: `snapCrackle` e `snapCracklePrime`. Cada uma delas recebe um parâmetro `maxValue` e deve retornar uma string construída a partir de condições específicas para cada número de 1 até `maxValue` (inclusive).

## Função 1: snapCrackle

A função `snapCrackle(maxValue)` deve:

- Fazer um loop de 1 até `maxValue` (inclusive) e construir uma string seguindo as condições abaixo:
  - Se o número for ímpar, concatenar `"Snap"` no final da string.
  - Se o número for múltiplo de 5, concatenar `"Crackle"` no final da string.
  - Se o número for tanto ímpar quanto múltiplo de 5, concatenar `"SnapCrackle"` no final da string.
  - Se o número não for nem ímpar nem múltiplo de 5, concatenar o próprio número no final da string.

- Todos os itens devem ser separados por vírgula e espaço.

### Exemplo

```javascript
snapCrackle(12); // Deve retornar: "Snap, 2, Snap, 4, SnapCrackle, 6, Snap, 8, Snap, Crackle, Snap, 12"
```

## Função 2: snapCracklePrime

A função `snapCracklePrime(maxValue)` é uma versão avançada da função anterior, com uma regra adicional:

- Se o número for primo, concatenar `"Prime"` no final da string, junto com as outras possíveis condições (como `Snap` e `Crackle`).

### Exemplo

```javascript
snapCracklePrime(15); // Deve retornar: "Snap, Prime, SnapPrime, 4, SnapCracklePrime, 6, SnapPrime, 8, Snap, Crackle, SnapPrime, 12, SnapPrime, 14, SnapCrackle"
```

## Passo a Passo

1. **Implementando a Função `snapCrackle`**
   - Comece criando um loop de 1 até `maxValue`.
   - Para cada número, verifique se ele atende às condições: é ímpar, múltiplo de 5, ou ambos.
   - Construa uma string com os valores ou palavras correspondentes, separados por vírgula e espaço.

2. **Implementando a Função `snapCracklePrime`**
   - Utilize a função `snapCrackle` como base.
   - Adicione uma lógica para verificar se o número é primo. Caso seja, concatene a palavra `Prime`.
  
## Contribuições

- Se você encontrar um problema ou tiver sugestões de melhorias, sinta-se à vontade para abrir uma _issue_ ou enviar um _pull request_.

## Licença

- Este repositório está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

