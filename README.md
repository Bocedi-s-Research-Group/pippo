# Pippo
Example directory to demonstrate using Git &amp; GitHub to the Bocedi group, presumably during our lab meeting on November 16th.

# About Pippo
*Modify this text with your favourite text editor, then share your proposed changes with Git.*

Thank you Théo! This is great :-)

Pippo (short for Filippo) is the italian name of the character Goofy. 
Extract from the [Wikipedia article](https://en.wikipedia.org/wiki/Goofy) about Goofy.

Goofy is a cartoon character created by The Walt Disney Company as a sidekick to Mickey Mouse. 
He is a tall, anthropomorphic dog who typically wears a turtle neck and vest, with pants, shoes, white gloves, and a tall hat originally designed as a rumpled fedora. 
Goofy is a close friend of Mickey Mouse and Donald Duck, and is Max Goof's father. 
He is normally characterized as hopelessly clumsy and dim-witted, yet this interpretation is not always definitive; occasionally, Goofy is shown as intuitive and clever, albeit in his own unique, eccentric way.



![Alt text: A graffiti representing Pippo in Innsbruck](https://upload.wikimedia.org/wikipedia/commons/thumb/1/13/Graffiti_Karmelitergasse_Innsbruck_01.jpg/800px-Graffiti_Karmelitergasse_Innsbruck_01.jpg?20220801222727)

*A graffiti representing Pippo in Innsbruck, Germany (picture taken by Wikipedia user Luftschiffhafen).*

# About Markdown

Markdown is a simple text formatting language based on plain text.
It has the advantages of being quite trivial to learn and use, and easily rendered by many tools (including GitHub here!).
Being based on plain text, it also easy to read even when it cannot be rendered. 

## Basic Markdown syntax

While writing Markdown text, it is usually a good idea to write one sentence per line.
Text on consecutive lines will be rendered into the same paragraph.

To jump to a new paragraph, one needs to leave an empty line in-between both paragraphs.

Text can be emphasized with asterisks, using one for *italics* and two for **bold** fonts. 

Headers are marked by starting the line with hashtags (#). Adding more hashtags makes headers of lower levels

# Title
## Section
### Subsection
#### Subsubsection

Text can be formatted to appear as a `code block`.

This is done by wrapping the corresponding text between backticks (`). You can also make multi-lines code block by wrapping the corresponding section with three backticks:
```
// 'Hello World!'  C++ program 
 
#include <iostream>
 
int main()
{
  std::cout << "Hello World!" << std::endl;
  return 0;
}
```

Another useful format is quoted text, done by starting the line with the > symbol.
> Gawrsh!

Lists can be created by starting each item line with a dash (-) or an asterisk (*):
- item 1
- item 2
- item 3
Lists can also be numbered if one starts each item line with a number and a dot (1.)
1. item 1
2. item 2
3. item 3

Hyperlinks are created by wrapping the text between square brackets followed by a link wrapped in regular parentheses (that is `[text](url)`),  [like this](https://www.youtube.com/watch?v=dQw4w9WgXcQ).
Adding an exclamation mark before this hyperlink creates an image `[alt text](path or url to image)`:
![ah-hyuck!](https://upload.wikimedia.org/wikipedia/en/5/50/Goofy_Duckipedia.png)

Finally, one can build and render a table, using vertical slashes (`|`) to separate columns, and dashes to separate header and entry lines:

```
| Language   | Name        |
|------------|-------------|
| English    | Goofy       |
| Italian    | Pippo       |
| French     |       Dingo |
| Turkish    |        Gufi |
| Portuguese |      Pateta |
| Latin      |     Stultus |
```

| Language   | Name        |
|------------|-------------|
| English    | Goofy       |
| Italian    | Pippo       |
| French     |       Dingo |
| Turkish    |        Gufi |
| Portuguese |      Pateta |
| Latin      |     Stultus |



## Additional features on GitHub

GitHub renders Markdown, and also adds some features on its own.
For example, you can add language-specific highlighting in multi-line code blocks by adding the name of the language after the three opening backticks:

```cpp
// 'Hello World!'  C++ program 
 
#include <iostream>
 
int main()
{
  std::cout << "Hello World!" << std::endl;
  return 0;
}
```

Lists can be created with tickable items by adding a whitespace and square brackets after the item symbol, (e.g. `- [ ] This needs to be done`). Items can be ticked by adding an x inside the brackets, or simply clicking on the rendered doc:
- [ ] This needs to be done
- [x] This has been done
      
There's much more, you can find out about it in the [official doc](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

## R Markdown

R supports its own form of Markdown, aptly called R Markdown.
R Markdown combines classic Markdown with R code blocks, which can be directly run as the document is being run to produce figures or analyses.
There are also some extra features, for example supporting LateX-style equations rendering.
This is not the place to teach R Markdown, but if you want to learn more, head to [the official doc](https://rmarkdown.rstudio.com/).

## Done
