namespace ConsoleApp1
{
    internal class Program
    {
        static void Main(string[] args)
        {
            //Contains (содержит)
            string word = "Hello";
            Console.WriteLine(word.Contains("H"));
            if (word.Contains("lo") )
            {
                Console.WriteLine("Success");
            }
            char[] example = { 'a', '.', '0' };
            Console.WriteLine(example.Contains(','));
            char[] punc = { '.', '!', '?', ',', ':', '\"', ';', '–', '(', ')', '[', ']', '{', '}', '/' };
            char x = '.';
            if (punc.Contains(x))
            {
                Console.WriteLine("it is punc");
            }
            else
            {
                Console.WriteLine("It is NOT punc");
            }
            if("aaa".Contains('a'))
            {
                Console.WriteLine("String is it many chars");
                Console.WriteLine("Money money money");
                Console.WriteLine("Must be funny");
                Console.WriteLine("In The Rich Mans world");
            }
            //Replace (заменить)
            string text = "Cat Dog dog doggy";
            string newtext = text.Replace("dog", "more cats");//! more catsggy !
            Console.WriteLine(text);
            Console.WriteLine(text.Replace("dog","more cats"));
            text = text.Replace("dog", "more cats");

            //Trim
            string word2 = "  c.at.?  ";
            Console.WriteLine();

            word2 = word2.Trim(' '); //Trimleft Trimrigth
            word2 = word2.Trim(punc);
            Console.WriteLine(word2);

            //Split (разделение по пробелам)
            string text2 = "hello, my   dear 2 friends!";
            string[] dirtyWords = text2.Split(' '); //Split 

            foreach(string w in dirtyWords)
            {
                Console.WriteLine(w);
            }


            //Join
            string text3 = String.Join(" ", dirtyWords);
            Console.WriteLine(text3);

            //IsDigit/IsLetter
            char s = 'a';
            Console.WriteLine(Char.IsDigit(s)); //является ли цифрой
            Console.WriteLine(Char.IsLetter(s)); //является ли буквой
            Console.WriteLine(Char.IsPunctuation(s)); //является ли пунктуацией
            Console.WriteLine(Char.IsLower(s)); //является ли нижний регистр
            Console.WriteLine(Char.IsUpper(s)); //является ли биг


            //ToLower/ToUpper
            string word3 = "aaa";
            Console.WriteLine(word3 = word3.ToUpper());

            string vowels = "аоеуяюиэ";
            vowels += vowels.ToUpper();
            Console.WriteLine(vowels);

            //внести в массив вс слова в тексте
            string input = "hello, my dear 1 jobs!";
            string[] dirtyDrims = input.Split(' ');
            string[] cleanDrims = new string[0]; ;
            for (int i=0; i<dirtyDrims.Length; i++)
            {
                string trimDrim = dirtyDrims[i].Trim(punc);
                Console.WriteLine(trimDrim);

                bool f = true;
                foreach(char symbol in trimDrim)
                {

                }
            }
        }
    }
}
