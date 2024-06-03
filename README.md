var o = new Flamingo();
o.Age.Dump();

class Flamingo
{
  string name;
  public int Age = 17;
  static readonly int legs = 2, eyes = 2;
}
//Constructors

Flamingo p = new Flamingo ("Pinky");   // Call constructor

public class Flamingo
{
  string name;                   // Define field
  public Flamingo (string n)        // Define constructor
  {
    name = n;                    // Initialization code (set up field)
  }
}
