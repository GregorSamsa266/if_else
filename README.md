# if_else
namespace if_else
{
    class Program
    {
        static void Main(string[] args)
        {
            int time = DateTime.Now.Hour;
            if (time>17)
            Console.WriteLine("Gündüz");
            else
            Console.WriteLine("Gece");
        }
    }
}
