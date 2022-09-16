using System;
using System.Collections.Generic;
using System.Globalization;
using System.Security.Cryptography.X509Certificates;
//Anime Quiz for otakus that have confidence in their knowledge of anime.
//Written by Alex Marques.


public class Quiz
{
    static string name = "If this is showing in your gameplay, something went wrong in the code. Please contact the creator, AlexMarques. Email: alex@recriarsistemas.com.br";
    static string answer = "If this is showing in your gameplay, something went wrong in the code. Please contact the creator, AlexMarques. Email: alex@recriarsistemas.com.br";
    static string yn = "If this is showing in your gameplay, something went wrong in the code. Please contact the creator, AlexMarques. Email: alex@recriarsistemas.com.br";
    static int num;
    static string q = "If this is showing in your gameplay, something went wrong in the code. Please contact the creator, AlexMarques. Email: alex@recriarsistemas.com.br";
    static string a = "If this is showing in your gameplay, something went wrong in the code. Please contact the creator, AlexMarques. Email: alex@recriarsistemas.com.br";
    static string d = "If this is showing in your gameplay, something went wrong in the code. Please contact the creator, AlexMarques. Email: alex@recriarsistemas.com.br";
    static int points;
    public static void Main()
    {
        Console.WriteLine("Hey, what's your name?");
        name = Console.ReadLine();
        Start();
    }
    public static void Start()
    {
        Console.WriteLine("Do you want to play the anime quiz? (Y/N)");
        yn = (Console.ReadLine()).ToLower();
        if (yn == "n")
        {
            Console.WriteLine("Goodbye, " + name + ".");
            Console.WriteLine("Please take this quiz to someone who'll want to play it.");
            Main();
        }
        else if (yn == "y")
        {
            Console.WriteLine("Then I'll test your knowledge with a quiz.");
            Rules();
        }
        else
        {
            Console.WriteLine("Invalid awnser");
            Start();
            return;
        }
    }
    public static void Rules()
    {
        Console.WriteLine("This quiz has 30 questions.");
        Console.WriteLine("If you want to jump to the results in the middle of the game, type 'gameover'.");
        Console.WriteLine("If you want to skip a question that you don't know the answer to, no matter how hard you try to think, type 'skip'.");
        Console.WriteLine("Let's begin then:");
        points = 0;
        num = 1;
        Questions();
    }
    public static void Questions()
    {
        string q1 = "Question 1: In Sword Art Online, what is Kirigaya Kazuto's username?";
        string a1 = "kirito";
        string d1 = "1 word, 6 letters";

        string q2 = "Question 2: In Naruto, what is Naruto's village's name (in japanese)?";
        string a2 = "konoha";
        string d2 = "1 word, 6 letters";

        string q3 = "Question 3: In Sword Art Online, what is Kirigaya Kazuto's girlfriend's full name (last name, first name)?";
        string a3 = "yuuki asuna";
        string d3 = "2 words, 5+5 letters";

        string q4 = "Question 4: In Pokemon, what is Ash's first pokemon?";
        string a4 = "pikachu";
        string d4 = "1 word, 6 letters";

        string q5 = "Question 5: In Kimetsu no Yaiba (Demon Slayer), what is the first breathing technique's element that Kamado Tanjirou learns?";
        string a5 = "water";
        string d5 = "1 word, 5 letters";

        string q6 = "Question 6: In Boku no Hero Academia, what is Deku's full name (last name, first name)?";
        string a6 = "midoriya izuku";
        string d6 = "2 words, 8+5 letters";

        string q7 = "Question 7: In Sword Art Online, in what year does the first arc happen?";
        string a7 = "2022";
        string d7 = "4 digits";

        string q8 = "Question 8: In Naruto, who is the sixth hokage (last name, first name)?";
        string a8 = "hatake kakashi";
        string d8 = "2 words, 6+7 letters";

        string q9 = "Question 9: In Shokugeki no Souma (Food Wars), what is the main character's full name (last name, first name)?";
        string a9 = "yukihira souma";
        string d9 = "2 words, 7+3 letters";

        string q10 = "Question 10: In Ao no Exorcist (Blue Exorcist), what is the demon kid's full name (last name, first name)?";
        string a10 = "okumura rin";
        string d10 = "2 word, 6+6 letters";

        string q11 = "Question 11: In The Irregular at Magic High School, what is the name of the famous CAD inventor?";
        string a11 = "taurus silver";
        string d11 = "2 word, 6+6 letters";

        string q12 = "Question 12: In Naruto, what is the name of the Uchiha's eye jutsu after the person kills their closest friend?";
        string a12 = "mangekyou sharingan";
        string d12 = "2 words, 9+9 letters";

        string q13 = "Question 13: In Boku no Hero Academia, what is Bakugou's first try for a hero name?";
        string a13 = "king explosion murderer";
        string d13 = "3 words, 4+9+8 letters";

        string q14 = "Question 14: In Shokugeki no Souma (Food Wars), what was Souma's father's full name before he got married (last name, first name)?";
        string a14 = "saiba jouichirou";
        string d14 = "2 words, 5+10 letters";

        string q15 = "Question 15: In Death Note, what is the name of the Shinigami that follows Yagami Light around?";
        string a15 = "ryuk";
        string d15 = "1 word, 4 letters";

        string q16 = "Question 16: In Kaguya-sama: Love is War, what is the full name of the boy (last name, first name)?";
        string a16 = "shirogane miyuki";
        string d16 = "2 words, 9+6 letters";

        string q17 = "Question 17: In Welcome to Demon School! Iruma-kun, what is the name of the demon Iruma's parents sold him to?";
        string a17 = "sullivan";
        string d17 = "1 word, 8 letters";

        string q18 = "Question 18: In Jujutsu Kaisen, what is the name of the demon whose fingers are eaten by Itadori Yuji?";
        string a18 = "sukuna";
        string d18 = "1 word, 6 letters";

        string q19 = "Question 19: In Nanatsu no Taizai (The Seven Deadly Sins), what is Ban's sin and animal?";
        string a19 = "greed and fox";
        string d19 = "3 words, 5 + ' and ' + 3 letters";

        string q20 = "Question 20: What is the name of the most famous opening music of Naruto (in english)?";
        string a20 = "blue bird";
        string d20 = "2 words, 4+4 letters";

        string q21 = "Question 21: In Boku no Hero Academia, what is Eraser Head's full name (last name, full name)?";
        string a21 = "aizawa shota";
        string d21 = "2 words, 6+5 letters";

        string q22 = "Question 22: What is the name of the main song in the anime Given? Answer in japanese, in romaji (english alphabet).";
        string a22 = "fuyu no hanashi";
        string d22 = "3 words, 4+2+7 letters";

        string q23 = "Question 23: In No Game, No Life, what is the name of the God that takes the pro-gamer siblings to another world?";
        string a23 = "tet";
        string d23 = "1 word, 3 letters";

        string q24 = "Question 24: In Naruto, what is the nickname given to Jiraya by Naruto? answer in japanese, in romaji (english alphabet).";
        string a24 = "ero-sennin";
        string d24 = "2 words, 3 + '-' + 6 letters";

        string q25 = "Question 25: In Kakegurui, how many millions of yens (¥) does Jabami Yumeko owes at the debt settlement party?";
        string a25 = "310";
        string d25 = "3 digits";

        string q26 = "Question 26: In Kakegurui, who was the first to play against Jabami Yumeko, in episode 1 (last name, first name (in english))?";
        string a26 = "saotome mary";
        string d26 = "2 words, 7+4 letters";

        string q27 = "Question 27: In The Hidden Dungeon Only I Can Enter, what is the passphrase to open the hidden dungeon's door? (in english)";
        string a27 = "hidden dungeon only i can enter, let me train in secret to become the strongest in the world";
        string d27 = "18 words, 6 + 7 + 4 + 1 + 3 + 5 + ', ' + 3 + 2 + 5 + 2 + 6 + 2 + 6 + 3 + 9 + 2 + 3 + 5 letters";

        string q28 = "Question 28: In Assassination Classroom, what is the name given to the alien teacher by the students?";
        string a28 = "koro-sensei";
        string d28 = "2 words, 4 + '-' + 6 letters";

        string q29 = "Question 29: In Fairy Tail, what's Natsu's last name?";
        string a29 = "dragneel";
        string d29 = "1 word, 8 letters";

        string q30 = "Question 30: In B: The Beginning, what does the simbol of the B killer actually means?";
        string a30 = "13 and 4";
        string d30 = "2 digits + ' and ' + 1 digit";

        string[] questions1 = new string[] { "error", q1, q2, q3, q4, q5, q6, q7, q8, q9, q10, q11, q12, q13, q14, q15, q16, q17, q18, q19, q20, q21, q22, q23, q24, q25, q26, q27, q28, q29, q30 };
        string[] answer1 = new string[] {"error", a1, a2, a3, a4, a5, a6, a7, a8, a9, a10, a11, a12, a13, a14, a15, a16, a17, a18, a19, a20, a21, a22, a23, a24, a25, a26, a27, a28, a29, a30};
        string[] tips1 = new string[] {"error", d1, d2, d3, d4, d5, d6, d7, d8, d9, d10, d11, d12, d13, d14, d15, d16, d17, d18, d19, d20, d21, d22, d23, d24, d25, d26, d27, d28, d29, d30};

        q = questions1[num];
        a = answer1[num];
        d = tips1[num];

        Console.WriteLine(q);
        answer = (Console.ReadLine()).ToLower();
        if(answer == a)
        {
            Console.WriteLine("Correct! Next Question");
            num += 1;
            points += 1;
            if(num <= 30)
            {
                Questions();
                return;
            }
            else if(num > 30)
            {
                Extra();
            }
        }
        else if (answer == "skip")
        {
            num += 1;
            if (num <= 30)
            {
                Questions();
                return;
            }
            else if (num > 30)
            {
                Extra();
            }
        }
        else if (answer == "gameover")
        {
            Results();
        }
        else if (answer != a && answer != "skip" && answer != "gameover")
        {
            Console.WriteLine("Wrong answer. Try Again.");
            Console.WriteLine("Tip: " + d);
            Questions();
            return;
        }
    }
    public static void ExtraQuestions()
    {

        string q31 = "Extra Question 1 (lyrics): Complete the lyrics: \n Tsumetai ______ ga / Sora de itetsuite / Yasashī furi shite / Mai ochiru koroni";
        string a31 = "namida";
        string d31 = "1 word, 6 letters";

        string q32 = "Extra Question 2 (YAOI): What is the name of the most popular yaoi ship in Boku no Hero Academia?";
        string a32 = "bakudeku";
        string d32 = "1 word, 4 letters";

        string q33 = "Extra Question 3 (japanese): What does 'OMEDETOU GOZAIMASU' mean in japanese?";
        string a33 = "congratulations";
        string d33 = "1 word, 15 letters";

        string[] questions2 = new string[] {"error", q31, q32, q33 };
        string[] answer2 = new string[] {"error", a31, a32, a33 };
        string[] tips2 = new string[] {"error", d31, d32, d33 };

        q = questions2[num];
        a = answer2[num];
        d = tips2[num];

        Console.WriteLine(q);
        answer = (Console.ReadLine()).ToLower();
        if (answer == a)
        {
            Console.WriteLine("Correct! Next Question:");
            num += 1;
            points += 2;
            if (num <= 33)
            {
                ExtraQuestions();
                return;
            }
            else if (num > 33)
            {
                ExtraResults();
            }
        }
        else if (answer == "skip")
        {
            num += 1;
            if (num <= 33)
            {
                ExtraQuestions();
                return;
            }
            else if (num > 33)
            {
                ExtraResults();
            }
        }
        else if (answer == "gameover")
        {
            ExtraResults();
        }
        else if (answer != a && answer != "skip" && answer != "gameover")
        {
            Console.WriteLine("Wrong answer. Try Again.");
            Console.WriteLine("Tip: " + d);
            ExtraQuestions();
            return;
        }
    }
    public static void Extra()
    {
        Console.WriteLine("Do you want to play 3 extra questions, worth 2 points each, about stuff related to anime, like japanese music, yaoi ships and japanese? (Y/N)");
        yn = (Console.ReadLine()).ToLower();
        if (yn == "y")
        {
            ExtraQuestions();
        }
        else if (yn == "n")
        {
            Results();
        }
        else
        {
            Console.WriteLine("Invalid answer.");
            Extra();
            return;
        }
    }
    public static void Results()
    {
        Console.WriteLine("You got " + points + " points out of 30! Congratulations " + name + "!");
        Console.WriteLine("Credits to the author: AlexMarques.");
        Console.WriteLine("Do you want to play again? (Y/N)");
        yn = (Console.ReadLine()).ToLower();
        if (yn == "y")
        {
            Rules();
        }
        else if (yn == "n")
        {
            Console.WriteLine("Goodbye, " + name + ".");
            Console.WriteLine("Please take this quiz to someone who'll want to play it.");
            Main();
        }
        else
        {
            Console.WriteLine("Invalid answer.");
            Results();
            return;
        }
    }
    public static void ExtraResults()
    {
        Console.WriteLine("You got " + points + " points out of 36! Congratulations " + name + "!");
        Console.WriteLine("Credits to the author: AlexMarques.");
        Console.WriteLine("Do you want to play again? (Y/N)");
        yn = (Console.ReadLine()).ToLower();
        if (yn == "y")
        {
            Rules();
        }
        else if (yn == "n")
        {
            Console.WriteLine("Goodbye, " + name + ".");
            Console.WriteLine("Please take this quiz to someone who'll want to play it.");
            Main();
        }
        else
        {
            Console.WriteLine("Invalid answer.");
            ExtraResults();
            return;
        }
    }
}
