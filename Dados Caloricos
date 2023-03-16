using System;

class Program {
  public static void Main (string[] args) {
    int  tcor, tped, tnat;
    double p, rcor, rped, rnat,tot;

    Console.Write("Digite seu peso > ");
    p=double.Parse(Console.ReadLine());

    Console.Write("Digite quanto tempo você corre semanalmente em minutos > ");
    tcor=int.Parse(Console.ReadLine());

    Console.Write("Digite quanto tempo você pedala semanalmente em minutos > ");
    tped=int.Parse(Console.ReadLine());

    Console.Write("Digite quanto tempo você nada (Crawl) semanalmene em minutos > ");
    tnat=int.Parse(Console.ReadLine());

    rcor=(7.0f * p)*(tcor) / 60;
    rped= (7.0f * p)*(tped) / 60;
    rnat= (8.0f * p)*(tnat) / 60;
    tot= rcor+rped+rnat;

    Console.WriteLine($"você perdeu correndo o total de {rcor.ToString("0,000")} Kcal");
    Console.WriteLine($"você perdeu pedalando o total de {rped.ToString("0,000")} Kcal");
    Console.WriteLine($"você perdeu nadando o total de {rnat.ToString("0,000")} Kcal");

    Console.WriteLine($"Você Perdeu o total de  {tot.ToString("0,000")} Kcal");
    
    }
  }
