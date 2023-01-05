using System;

class Program 
{
  static void Main (string[]args)
  {
    String[] arrStr = new String[]{"Мама", "мыла", "ужа"};
    String[] newArrStr = new String[arrStr.Length];
    int count = 0;
    for (int i = 0; i < arrStr.Length; i++) 
    {
      if (arrStr[i].Length < 4) 
      {
          newArrStr[count] = arrStr[i];
          count++;
      }
    }
    for (int i = 0; i < newArrStr.Length; i++) 
    {
      Console.WriteLine(newArrStr[i]);
    }
  }
}
