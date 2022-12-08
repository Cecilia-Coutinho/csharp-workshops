Om uppgiften
I denna uppgift kommer du �va p� att anv�nda Polymorphism inom objektorientering. Uppgiften handlar till stor del om att t�nka ut en struktur f�r Polymorphism .

Vad du ska g�ra
 Du ska skapa en klass som ska vara ParentClass till de andra klasserna som ska �rva fr�n den. Klassen ska heta Geometri{ } och den ska en metod som heter Area() och return typ �r en double.

 Du ska skapa tre klasser till som ska �rva fr�n Geometriklassen och klasserna ska heta Rektangel, Fyrkant och Cirkel. Namn ska vara p� Engleska Alla klasser ska ha en metod som heter Area().

 Varje klass ska ha minst en egenskap, till exempel:

public class Cirkel{
     public double Radius {get; set;}
}
 I alla ChildClasses ska vi overrida metoden Area() med olika implementeringar. Eftersom arean f�r en cirkel inte r�knas ut p� samma s�tt som arean f�r en fyrkant.

 Alla ChildClasses m�ste ha en Constructor f�r att ge v�rde till egenskaper och vi ska ge den ett fast v�rde i konstruktorn. Till Exempel:

public Cirkel{
      Radius = 4;
}
 I Main-metoden ska du skapa object reference fr�n Geometriklassen och den ska peka till ett objekt av varje klass.

Output :
Area Cirkel: 78,5
Area Fyrkant: 36
Area Rektangel: 18,02