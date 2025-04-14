# Conversor de Bases Numéricas em C

Este é um programa simples em linguagem C que permite ao usuário converter números entre diferentes bases numéricas: **binário**, **octal**, **decimal** e **hexadecimal**.

## 🧠 Funcionalidades

O programa permite ao usuário:

- Inserir um número em uma base (binária, octal, decimal ou hexadecimal)
- Escolher uma base de destino para conversão
- Visualizar o resultado da conversão

## 📋 Menu de Opções

Ao executar o programa, o usuário pode escolher:


Após selecionar uma opção, o programa solicitará o número na base escolhida e perguntará para qual base deseja convertê-lo.

## 🔄 Conversões Suportadas

| Base de Origem | Bases de Destino |
|----------------|------------------|
| Binário        | Octal, Decimal, Hexadecimal |
| Octal          | Binário, Decimal, Hexadecimal |
| Decimal        | Binário, Octal, Hexadecimal |
| Hexadecimal    | Binário, Octal, Decimal |

## 🛠️ Funções Utilizadas

- `strtol()` — converte strings em números inteiros, com base escolhida (ex: binário para decimal)
- `itoa()` e `ltoa()` — convertem inteiros em strings (ex: decimal para binário)
- `scanf()` e `printf()` — entrada e saída de dados

⚠️ **Nota:** `itoa()` e `ltoa()` são funções não padronizadas (não fazem parte da biblioteca padrão do C), e podem não funcionar em todos os compiladores. Uma alternativa é implementar funções personalizadas ou usar bibliotecas compatíveis.

## 💡 Exemplo de Uso

```bash
Escolha sua opcao de conversao:
1. BINARIO
2. OCTAL
3. DECIMAL
4. HEXA
Opcao: 1

Digite um valor binario: 1010

Escolha uma opção:
1. Converter para octal
2. Converter para decimal
3. Converter para hexadecimal
Opcao: 2

Binario 1010 convertido : 10

