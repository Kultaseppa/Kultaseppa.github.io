<!DOCTYPE html>
<html>
## Exercise 1
Writing in Markdown is *not* that hard!

## Exercise 2
**BBCode**

BBCode (Bulletin Board Code) is a lightweight markup language used to format posts in message boards, forums, and online communities. It was designed to be easy to use and parse, and is similar to HTML in its basic syntax. BBCode allows users to add formatting, links, and media to their posts, and is often used in place of HTML to reduce the risk of cross-site scripting attacks.

**R Markdown**

R Markdown is a variant of Markdown that is specifically designed for creating documents that contain R code and results. It is an open-source format that allows users to embed R code, output, and graphics in a single document, making it easy to create reproducible reports and documents. R Markdown is commonly used for data analysis, scientific research, and technical writing, and is a powerful tool for creating dynamic documents that combine text, code, and data visualization.

## Exercise 3
[![Video title](https://upload.wikimedia.org/wikipedia/commons/4/43/Cute_dog.jpg)](https://www.youtube.com/watch?v=qAt1LQJnnTE)

## Exercise 4
public class Person
{
  private string name;
  private int age;

  public Person(string initialName)
  {
    this.age = 0;
    this.name = initialName;
  }
  public void PrintPerson()
  {
    Console.WriteLine(this.name + ", age " + this.age + " years");
  }
  public void GrowOlder()
  {
    this.age = this.age + 1;
  }
}
