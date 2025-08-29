# Relatório de Produção (Difícil)

Uma fábrica produz peças em série.

- Declare no código:
```java
int passo = 4;
int limite = 20;
```
- Mostre todos os números de `1` até `limite` que sejam múltiplos de `passo` **na mesma linha**, separados por espaço.
- Depois imprima:
  - `Quantidade: Q`
  - `Soma: S`
  - Por fim, uma mensagem que dependa da quantidade:
    - `Produção: ALTA` se `Q >= 5`
    - `Produção: BAIXA` caso contrário

## Saída esperada
```
4 8 12 16 20
Quantidade: 5
Soma: 60
Produção: ALTA
```

⚠️ Regras:
- Não use `Scanner`.
- Não use arrays.
- Reflita sobre qual laço e como decidir a mensagem final.
