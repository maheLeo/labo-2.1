

|Ligne exécuté|Effet|Ligne d'appel|
|-|-|-|
|for (int i = 1; i < 4; i++)|i = 1<br />i < 4 est vraie|Main()|
|if (i % 2 == 0)|i : 1<br />i % 2 vaut 1, 1 % 2 == 0 est faux|Main()|
|Console.WriteLine("ah ben ah ben, " + i + " est impair")|i : 1<br />affiche "ah ben ah ben, 1 est impair"|Main()|
|for (int i = 1; i < 4; i++)|i : 2<br />i < 4 est vraie|Main()|
|if (i % 2 == 0)|i : 2<br />i : 2 vaut 0, 2 % 2 == 0 est vraie|Main()|
|Console.WriteLine(i + " est pair")|i : 2<br />affiche i + " est pair"|Main()|
|for (int i = 1; i < 4; i++)|i : 3<br />i < 4 est vraie|Main()|
|if (i % 2 == 0)|i : 3<br />i : 3 vaut 1|Main()|
|Console.WriteLine("ah ben ah ben, " + i + " est impair")|i : 3<br />affiche "ah ben ah ben, " + i + " est impair" |Main()|
|for (int i = 1; i < 4; i++)|i : 4<br />i < 4 est faux|Main()|



