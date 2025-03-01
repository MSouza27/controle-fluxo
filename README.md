# Desafio Controle de Fluxo

Este projeto faz parte do desafio de Controle de Fluxo proposto pela **DIO (Digital Innovation One)**.

## Descrição
O sistema recebe dois parâmetros via terminal que representam dois números inteiros. Com base nesses números, o programa realiza uma contagem e imprime no console a quantidade de números incrementados.

### Regras:
- O segundo parâmetro deve ser **maior** que o primeiro.
- Caso contrário, será lançada uma exceção customizada chamada **ParametrosInvalidosException**.

## Tecnologias Utilizadas
- Java
- Programação Orientada a Objetos
- Tratamento de Exceções
- Controle de Fluxo (Estruturas de Repetição e Condicional)

## Como Executar
1. Clone o repositório:

```bash
git clone https://github.com/MSouza27/controle-fluxo
```

2. Acesse o diretório do projeto:

```bash
cd DesafioControleFluxo
```

3. Compile o código:

```bash
javac Contador.java
```

4. Execute o programa:

```bash
java Contador
```

## Exemplo de Execução
**Entrada:**
```
Digite o primeiro parâmetro
5
Digite o segundo parâmetro
10
```

**Saída:**
```
Imprimindo o número 1
Imprimindo o número 2
Imprimindo o número 3
Imprimindo o número 4
Imprimindo o número 5
```

Caso o segundo parâmetro seja menor que o primeiro:
```
O segundo parâmetro deve ser maior que o primeiro
```

## Autor
[Magno Souza](https://github.com/MSouza27)

## Licença
Este projeto está licenciado sob a licença MIT.

