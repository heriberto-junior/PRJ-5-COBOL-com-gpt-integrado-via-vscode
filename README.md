<<<<<<< HEAD
# Simulador de Processamento Batch de Cartões

Este projeto simula o processamento de cartões em lote usando Cobol GNU.

## Estrutura
 - `cartoes.cbl`: Programa principal em Cobol GNU
 - `cartoes.txt`: Arquivo de entrada com dados dos cartões
 - `relatorio.txt`: Arquivo de saída com resultados do processamento

## Formato do arquivo de entrada (`cartoes.txt`)
Cada linha representa um cartão:

```
<NUMERO> <NOME> <VALOR> <STATUS>
```
Exemplo:
```
12345 JOAO 1000 A
23456 MARIA 500 R
```

## Como executar
1. Compile o programa:
   ```
   cobc -x cartoes.cbl
   ```
2. Execute:
   ```
   ./cartoes
   ```

## Testes automatizados
Para integração com GitHub Actions, crie scripts de teste e workflows para validar o processamento.
# Simulador de Processamento Batch de Cartões

Este projeto simula o processamento de cartões em lote usando Cobol GNU.

## Estrutura
- `cartoes.cbl`: Programa principal em Cobol GNU
- `cartoes.txt`: Arquivo de entrada com dados dos cartões
- `relatorio.txt`: Arquivo de saída com resultados do processamento

## Formato do arquivo de entrada (`cartoes.txt`)
Cada linha representa um cartão:

```
<NUMERO> <NOME> <VALOR> <STATUS>
```
Exemplo:
```
12345 JOAO 1000 A
23456 MARIA 500 R
```

## Como executar
1. Compile o programa:
   ```
   cobc -x cartoes.cbl
   ```
2. Execute:
   ```
   ./cartoes
   ```

## Testes automatizados
Para integração com GitHub Actions, crie scripts de teste e workflows para validar o processamento.
=======
# PRJ-5-COBOL-com-gpt-integrado-via-vcode
Projeto que visa testar VSCode com GPT-4.1 como copiloto integrado para desenvolver em Cobol GNU
>>>>>>> ccd6dce30336722460d9dfd40b61bf0e1eced99c
