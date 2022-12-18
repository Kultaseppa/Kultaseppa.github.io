## Exercise 1
Writing in Markdown is _not_ that hard!

I **will** complete these lessons!

"_Of course_," she whispered. Then, she shouted: "All I need is **a little moxie**!"

If you're thinking to yourself, **_This is unbelievable_**, you'd probably be right.

#Header one
##Header two
###Header three
####Header four
#####Header five
######Header six

[Search for it.](www.google.com)

[You're **really, really** going to want to see this.](www.dailykitten.com)


####The Latest News from [the BBC](www.bbc.com/news)

Do you want to [see something fun][a fun place]?

Well, do I have [the website for you][another fun place]!

[a fun place]: www.zombo.com
[another fun place]: www.stumbleupon.com

![A pretty tiger](https://upload.wikimedia.org/wikipedia/commons/5/56/Tiger.50.jpg)

![Black cat][Black]

![Orange cat][Orange]

[Black]: https://upload.wikimedia.org/wikipedia/commons/a/a3/81_INF_DIV_SSI.jpg
[Orange]: http://icons.iconarchive.com/icons/google/noto-emoji-animals-nature/256/22221-cat-icon.png

I read this interesting quote the other day:

>"Her eyes had called him and his soul had leaped at the call. To live, to err, to fall, to triumph, to recreate life out of life!"

>Once upon a time and a very good time it was there was a moocow coming down along the road and this moocow that was coming down along the road met a nicens little boy named baby tuckoo...

>His father told him that story: his father looked at him through a glass: he had a hairy face.

>He was baby tuckoo. The moocow came down the road where Betty Byrne lived: she sold lemon platt.

* Flour, 
* Cheese,
* Tomatoes

1. Cut the cheese,
2. Slice the tomatoes,
3. Rub the tomatoes in flour

* Azalea (_Ericaceae Rhododendron_)
* Chrysanthemum (_Anthemideae Chrysanthemum_)
* Dahlia (_Coreopsideae Dahlia_)

* Calculus,
 * A professor, 
 * Has no hair, 
 * Often wears green
* Castafiore, 
 * An opera singer,
 * Has white hair,
 * Is possibly mentally unwell

1. Cut the cheese
  * Make sure that the cheese is cut into little triangles.
  

2. Slice the tomatoes
  * Be careful when holding the knife.
  * For more help on tomato slicing, see Thomas Jefferson's seminal essay _Tom Ate Those_.




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
