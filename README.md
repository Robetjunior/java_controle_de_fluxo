# Desafio Controle de Fluxo

Projeto da DIO (Trilha Java Básico) para exercitar leitura de parâmetros, laços e exceções.

## Requisitos

- Receber dois inteiros via terminal.
- Se o primeiro > segundo, lançar `ParametrosInvalidosException` com mensagem "O segundo parâmetro deve ser maior que o primeiro".
- Caso contrário, calcular `contagens = segundo - primeiro` e imprimir de 1 a `contagens`:  
  `Imprimindo o número X`

## Estrutura

```
DesafioControleFluxo/
├── src/
│ ├── Contador.java
│ └── ParametrosInvalidosException.java
└── README.md
```


## Execução

```bash
javac src/*.java
java -cp src Contador
```

Informe os valores quando solicitado.

## Exemplos

**Entrada:**
```
12
30
```

**Entrada:**
````
Imprimindo o número 1
...
Imprimindo o número 18
```