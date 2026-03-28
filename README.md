# una-ihcux-lista05

# Funcionalidade
O `Program.cs` utiliza duas bibliotecas, System e System.Threading. O código funciona para fazer a conversão de real para dólar; quando o usuário informa o valor em reais e a cotação do dólar, o sistema divide o valor e faz a conversão automaticamente.
1. O usuário informa o valor em reais e a cotação do dólar. Caso o usuário informe um valor diferente de um double, como uma string, o programa cai em catch, informando que a entrada está inválida.
2. Caso o usuário tenha informado o valor corretamente, o código faz a conversão dividindo os valores e mostrando sempre duas casas decimais.
3. Sempre no final do código, independente se deu erro ou não, é mostrada uma mensagem no final.

# O que o código utiliza
- `Thread.Sleep` de 1 segundo para o sistema conectar ao banco central.
- `For` uma laço de repetição que conta 0,5 segundos 3 vezes e sempre a cada final de loop adiciona um ponto final na mensagem.
- `Try-Catch` para mostrar uma mensagem de erro mais amigavel para o usuario.
- `F2` O valor final mostra sempre com duas casas decimais.

## 📸 Evidência de Execução
![Print do terminal rodando o projeto dando certo](./program_executado.png)
## 📸 Evidência de Execução
![Print do terminal rodando o projeto dando erro](./program_erro.png)
