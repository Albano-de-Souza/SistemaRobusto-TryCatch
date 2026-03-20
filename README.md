# Sistema de Cadastro Expert - Prevenção de Erros 

Este projeto aplica a **5ª Heurística de Nielsen (Prevenção de Erros)** utilizando C#.

## O que é o Try-Catch?
O `try-catch` é um bloco de código usado para lidar com exceções (erros que acontecem durante a execução). 
- O **`try`** contém o código que pode dar erro (neste caso, a conversão de texto para número).
- O **`catch`** é acionado se o erro ocorrer, permitindo que o sistema exiba uma mensagem amigável em vez de simplesmente travar.

## Conexão com a Prevenção de Erros (UX)
Em vez de deixar o usuário ver uma tela de erro técnica e assustadora, o código previne o fechamento do programa e oferece uma **dica clara** de como corrigir a entrada de dados. Isso melhora a experiência e dá segurança ao usuário.

## Evidências do Teste
### Caminho Feliz (Sucesso)
![Sucesso](./evidencia-sucesso.png)

### Caminho do Erro (Mensagem Amigável)
![Erro](./evidencia-erro.png)
