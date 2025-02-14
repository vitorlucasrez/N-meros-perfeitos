# N-meros-perfeitos

int n;
int SomaDiv;

for (n = 2; n <= 1000; n++)
{
    SomaDiv = 0;

    for(int i = 1; i < n; i++)
    {
        if (n % i == 0)
        SomaDiv+=i;
    }
    if (SomaDiv == n)
    {
        Console.WriteLine($"O número {n} é perfeito!");
        
    }
}
