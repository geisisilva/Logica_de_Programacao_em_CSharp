<div align="center">
  
# Logica de Programação em CSharp

Meu repositório de estudos sobre algoritmos e lógica de programação em CSharp.

</div>
<br>

## 📚 Conceitos Aprendidos:

### 1. Comentários, declaração de variáveis e "Hello World"

> [!NOTE]\
> *Retirado da aula de "[Hello_Word](https://github.com/geisisilva/Logica_de_Programacao_em_CSharp/tree/main/Hello_World)"*

<div align="left">

  Nesta aula foram aprendidos:
  - Conceitos básicos para o uso do Visual Studio
  - Criação de algoritmos
  - Lógica de programação
  - "Hello World! :)"
 
</div>
  
```c#
// Na criação de um "algoritmo", podemos seguir este sete passos ↴
// 1.NOME, 2.INÍCIO, 3.DADOS/VARIÁVEIS, 4.ENTRADA, 5.PROCESSAMENTO, 6.SAÍDA, 7.FIM

// 1.NOME:
namespace Calculadora_CSharp
{
    internal class Program
    {
        static void Main(string[] args)
        {
            // 2.INÍCIO
            // Faça um algorítimo que receba dois valores e mostre
            // a soma desses dois valores.

            // 3.DADOS/VARIÁVEIS
            double n1 = 0;
            double n2 = 0;
            double soma = 0;

            // 4.ENTRADA
            Console.WriteLine("Digite o primeiro número:");
            n1 = double.Parse(Console.ReadLine());
            Console.WriteLine("\r\nDigite o segundo número:");
            n2 = double.Parse(Console.ReadLine());

            // 5.PROCESSAMENTO
            soma = n1 + n2;

            // 6.SAÍDA
            Console.WriteLine("\r\nOs números somados são: " + soma);
            Console.ReadKey();

            Console.WriteLine("\r\nHello World!");
        }
    }
}
// 7.FIM :)
```
</div>

<div align="left">
  <h6><a href="#logica-de-programação-em-csharp"> Voltar para o início ↺</a></h6>
</div>
