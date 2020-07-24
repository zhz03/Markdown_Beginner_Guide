

# Markdown beginner's guide

# 7/24/2020

###  Zhaoliang

### Content

[1 Why use Markdown?](### Why use Markdown?)

[2 Markdown Editor software](### Markdown Editor software)

[3 Common grammar](### Common grammar)

[4 Markdown Math](### Markdown Math)

### 1 Why use Markdown?

- __"Anyone can open" and "Style compatibility"__ : 

  Markdown is plain text, anyone can open markdown. And because of that, you will not run into the problem like compatibility issue when your software need to be updated in the future (ex: MS office).

- **It Converts to HTML Easily**:

  HTML is the markup language of the entire World Wide Web (web), but more importantly, it is also the markup language used in the current mainstream e-book format. 

- **It is generally used in many places**:

  - Github and Gihub wiki

  - Slack, rocket chat, Skype 

  - Project management products like [Trello](https://trello.com/en-US)

  - Blog-aware static site generators like Jekyll or Hugo

    

### 2 Markdown Editor software

I personally recommend some Markdown editor software that are powerful, simple, easy to use and have preview. 

- [Typora](https://typora.io/) (strongly recommended): available for MacOS, Linux, Windows
- [iA Writer](https://www.shopify.com/partners/blog/10-of-the-best-markdown-editors) : available for MacOS, ios, Android, Windows
- [Web-based MarkDown Editor](https://codepen.io/itsjzt/full/mMRbVj/)
- Pycharm + markdown module
- VS studio / VS code + markdown support



### 3 Common grammar

#### Heading

By using # for heading 1, ## heading 2, ### heading 3, so on. Just like the title, date, and Author name

#### Un-ordered list

- list1: "-"
* list2: "*"
+ list3: "+"

#### ordered list

1. list1
2. list2
3. list3

#### Quote

> Writing is thinking
>
> ">" is the quote mark, space is needed between > and your words

#### Bold and Italic text

> For bold text: ** or __
> 
> __bold text__
> 
> **bold text**
>
> For italic text: * or _
>
> *italic text*
>
> _italic text_

#### Delete text

>  ~~the text can be deleted too~~

#### The code references

You can used markdown to cite code from different programming languages:

* Python:

  ```python
  for i in range(10):
      print(i)
  ```

- C:

  ```C
  #include<stdio.h>
  int main(){
  print("hello world");
  return 0;
  }
  ```

- MATLAB:

  ```matlab
  %% Modify Plot Properties
  title('Sine Wave')
  xlabel('x')
  ylabel('sin(x)')
  fig = gcf;
  fig.MenuBar = 'none';
  ```

#### Highlight

`use 'text' to Highlight`

#### Separator

use "* * *" or "***" or "---" or "----------------"
> * * *
>
> ***
>
> ---
>
> --------------------

#### Table

| Syntax | Description |
| ---- | :--: |
| Heading | Title |
| Paragraph | Text or images |

#### Images

use 

> ![]() format
>
> ![](url?resize=xxx) format to resize the size of your picture

For example:

![](img_0065.jpg ?resize=450)

#### Link

use

> [](): [] specifies name of your link, and ()  specifies the url of your link

For example:

[Google scholar top publications](https://scholar.google.com/citations?view_op=top_venues&hl=en)



### 4 Markdown Math

Markdown takes Latex syntax to edit directly. But LaTex's grammar, editor, configuration, Chinese support, etc. are much more complicated than Markdown, and it is not as good as Markdown's mature community.

#### Greek letter

Use double $ to encompass the Greek symbol:

```yaml
$\Gamma$、$\iota$、$\sigma$、$\phi$、$\upsilon$、$\Pi$、$\Bbbk$、$\heartsuit$、$\int$、$\oint$
```

$\Gamma$、$\iota$、$\sigma$、$\phi$、$\upsilon$、$\Pi$、$\Bbbk$、$\heartsuit$、$\int$、$\oint$

#### operator

```yaml
$+$、$-$、$=$、$>$、$<$、$\times$、$\div$、$\equiv$、$\leq$、$\geq$、$\neq$
```

$+$、$-$、$=$、$>$、$<$、$\times$、$\div$、$\equiv$、$\leq$、$\geq$、$\neq$

#### Trigonometric function and other math functions

```yaml
$\tan$、$\sin$、$\cos$、$\lg$、$\arcsin$、$\arctan$、$\min$、$\max$、$\exp$、$\log$
```

$\tan$、$\sin$、$\cos$、$\lg$、$\arcsin$、$\arctan$、$\min$、$\max$、$\exp$、$\log$

#### Set symbol

```yaml
$\cup$、$\cap$、$\in$、$\notin$、$\ni$、$\subset$、$\subseteq$、$\supset$、$\supseteq$、$\N$、$\Z$、$\R$、$\R$、$\infty$
```

$\cup$、$\cap$、$\in$、$\notin$、$\ni$、$\subset$、$\subseteq$、$\supset$、$\supseteq$、$\N$、$\Z$、$\R$、$\R$、$\infty$

#### Math equations in Markdown

$z = x + y$

$$a^2 + b^2 = c^2$$

$$\begin{vmatrix}a & b\\ c & d \end{vmatrix}=ad-bc$$    and   $a_x + a_y = z_t$
$$
\mathbf{V}_1 \times \mathbf{V}_2= \begin{vmatrix}
a_{11} &  a_{12} \\
a_{21} & a_{22}
\end{vmatrix}
$$

### Reference

[1] [Markdown Guide](https://www.markdownguide.org/basic-syntax/)

[2] [What is Markdown, and why should you use it?](https://www.ultraedit.com/company/blog/community/what-is-markdown-why-use-it.html#:~:text=It's%20Used%20Everywhere&text=Markdown%20is%20the%20unofficial%20standard,Markdown%20syntax%20they%20call%20wikitext.)

