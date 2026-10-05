# Calculadora em C

Uma calculadora simples com interface gráfica desenvolvida na linguagem C, utilizando a API Win32 do Windows.

## Funcionalidades

A calculadora permite realizar as seguintes operações matemáticas básicas com dois números:
- **Soma**
- **Subtração**
- **Multiplicação**
- **Divisão**

Além das operações matemáticas, a interface conta com:
- Botão **Limpar**: apaga os valores inseridos e prepara a calculadora para uma nova operação.
- Botão **Sair**: encerra o programa de forma segura.
- Tratamento de erros, como aviso de campos vazios e impedimento de divisão por zero.

## Tecnologias Utilizadas
- Linguagem C
- Windows API (Win32) para a construção da interface gráfica (GUI).

## Como Executar

O projeto já inclui um arquivo executável compilado para Windows. 
Basta executar o arquivo `Calculadora.exe` presente no repositório.

### Como Compilar (Para Desenvolvedores)
Se você deseja modificar o código e recompilar o projeto, pode utilizar o **GCC (MinGW)** com o seguinte comando:

```bash
gcc main.c -o Calculadora.exe -mwindows
```
Ou abra o projeto diretamente no **Code::Blocks** utilizando o arquivo `Calculadora em C.cbp`.
