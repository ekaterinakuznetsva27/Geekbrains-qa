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
![image_2022-12-25_16-09-02](https://user-images.githubusercontent.com/116455284/211215071-accd0fb9-19ab-4e5c-a2b8-ece131163168.png)
