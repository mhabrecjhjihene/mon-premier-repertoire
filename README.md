# mon-premier-repertoire
void PremiereOccurrence()
static void PremiereOccurrence()
{
   
    int indice = 0;
    int nombre = 0;
    char[] chaine = new char[10];
   
    Console.Write("entrer le caractere cherché : ");
    char caractereRechercher = Convert.ToChar(Console.ReadLine());

    Console.Write("entrer la chaine  : ");

    for (int j = 0; j < chaine.Length; j++)
    {
        char caractere = Convert.ToChar(Console.ReadLine());
        chaine[j] = caractere;
    }


   
  
    int i = 0;

    do
    {
       
        Console.Write("st trouve");
    } while (caractereRechercher == chaine[i]);
  

    if (indice == 0)
    {
        Console.WriteLine($"le caractere {caractereRechercher}ne se trouve pas dans la chaine{chaine}");
    }
    else
    {
        Console.Write($"la premiere occurence de {caractereRechercher}dans la chaine {chaine} est a l'index {indice} ");
    }
}
