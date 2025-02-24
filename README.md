# Projeto Valores Decimais

Crie um programa que leia três notas de um aluno e calcule a média aritmética dessas notas. Exiba o resultado da média para o usuário.
Dicas:
Utilize Console.WriteLine para exibir mensagens pedindo as notas.
Utilize Console.ReadLine para capturar as entradas do usuário e Convert.ToDecimal para converter as entradas para valores decimais.
Realize a média dos três valores e exiba o resultado com Console.WriteLine.
=================================================================================================================================================================================
using System;

class Program
{
    static void Main()
    {
        // Solicita as três notas ao usuário
        Console.WriteLine("Digite a primeira nota:");
        decimal nota1 = Convert.ToDecimal(Console.ReadLine());

  Console.WriteLine("Digite a segunda nota:");
        decimal nota2 = Convert.ToDecimal(Console.ReadLine());

  Console.WriteLine("Digite a terceira nota:");
        decimal nota3 = Convert.ToDecimal(Console.ReadLine());

  // Calcula a média aritmética
        decimal media = (nota1 + nota2 + nota3) / 3;

  // Exibe o resultado
        Console.WriteLine($"A média das notas é: {media:F2}");
    }
}
