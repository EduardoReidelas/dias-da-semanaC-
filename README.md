# dias-da-semanaC-

using System;

class HelloWorld {
    static void Main() {
        Console.WriteLine("Digite o dia");
        string numero = Console.ReadLine(); // Corrigido "Readline" para "ReadLine"
        
        switch (numero) {
            case "1":
                Console.WriteLine("Domingo");
                break;
            case "2":
                Console.WriteLine("Segunda");
                break;
            case "3":
                Console.WriteLine("Terça feira");
                break;
            case "4":
                Console.WriteLine("Quarta feira");
                break;
            case "5":
                Console.WriteLine("Quinta feira");
                break;
            case "6":
                Console.WriteLine("Sexta feira");
                break;
            case "7":
                Console.WriteLine("Sabado");
                break;
            default:
                Console.WriteLine("Dia inválido");
                break;
        }    
    }
}
