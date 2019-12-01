# How to use Markdown for writing Docs

## Markdown이란?
HTML, XML 등과 같은 Markup 언어의 일종으로, 2004년 John Gruber와 Aaron Swartz가 만들었다.
다른 플랫폼에서 사용하고 있는 마크업 언어로 쉽게 컨버팅이 가능하고, 문법이 간결한 장점을 가지고 있다.

## Markdown의 장점
1. 문법이 간결하여 쉽고 빠르게 익히고, 작성할 수 있다.
2. 텍스트만으로 작성이 가능하고, 용량이 적어 부담이 없다.
3. 다양한 형태로 컨버팅이 가능하다.

## Markdown의 단점
1. 표준이 없기 때문에 사용하는 에디터나 페이지에 따라 렌더링된 결과물이 다르다.
2. 파편화로 인해 확장 문법이 많고, 익혀야하는 문법도 다양하다.
3. 멀티미디어를 가져오는 방법이 불편하거나 없다.

## Markdown basics
### Headings

# This is heading 1
`# This is heading 1`

## This is heading 2
`## This is heading 2`

### This is heading 3
`### This is heading 3`

#### This is heading 4
`#### This is heading 4`

# Async Programming in F# #
`# Async Programming in F# #`

위와 같이 heading의 마지막이 #으로 끝난다면 추가로 # 문자를 하나 더 붙여야 에러가 없다.

제목 1
======

제목 2
------

### Bold and italic text

This text is **bold**.
`This text is **bold**.`

This text is *italic*.
`This text is *italic*.`

This is text is both ***bold and italic***.
`This is text is both ***bold and italic***.`

이텔릭체는 *별표(asterisks)* 혹은 _언더바(underscore)_를 사용하세요.

두껍게는 **별표(asterisks)** 혹은 __언더바(underscore)__를 사용하세요.

**_이텔릭체_와 두껍게**를 같이 사용할 수 있습니다.

취소선은 ~~물결표시(tilde)~~를 사용하세요.

<u>밑줄</u>은 `<u></u>`를 사용하세요.

### Blockquotes

> The drought had lasted now for ten million years, and the reign of the terrible lizards had long since ended. Here on the Equator, in the continent which would one day be known as Africa, the battle for existence had reached a new climax of ferocity, and the victor was not yet in sight. In this barren and desiccated land, only the small or the swift or the fierce could flourish, or even hope to survive.

`> The drought had lasted now for ten million years, and the reign of the terrible lizards had long since ended. Here on the Equator, in the continent which would one day be known as Africa, the battle for existence had reached a new climax of ferocity, and the victor was not yet in sight. In this barren and desiccated land, only the small or the swift or the fierce could flourish, or even hope to survive.`

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
> 
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.

> This is the first level of quoting.
>
> > This is nested blockquote.
>
> Back to the first level.

> ## This is a header.
> 
> 1.   This is the first list item.
> 2.   This is the second list item.
> 
> Here's some example code:
> 
>     return shell_exec("echo $input | $markdown_script");

### Lists

#### Unordered list
- List item 1<br>
`- List item 1`
- List item 2<br>
`- List item 2`
- List item 3<br>
`- List item 3`

- List item 1<br>
`- List item 1`
  - List item A<br>
  `- List item A`
  - List item B<br>
  `- List item B`
- List item 2<br>
`- List item 2`

#### Ordered list

1. First instruction<br>
`1. First instruction`
1. Second instruction<br>
`1. Second instruction`
1. Third instruction<br>
`1. Third instruction`

0. First instruction<br>
`0. First instruction`
   1. Sub-instruction<br>
   `1. Sub-instruction`
   1. Sub-instruction<br>
   `1. Sub-instruction`
1. Second instruction<br>
`1. Second instruction`

#### Checklist

> [!div class="checklist"]
> * List item 1
> * List item 2
> * List item 3

### Tables

| Fun                 |                 With |     Tables      |
| :------------------ | -------------------: | :-------------: |
| left-aligned column | right-aligned column | centered column |
| $100                |                 $100 |      $100       |
| $10                 |                  $10 |       $10       |
| $1                  |                   $1 |       $1        |

- `Shift` + `Alt` + `F` on Windows
- `Ctrl` + `Shift` + `I` on Linux

| Fun                 |                 With |     Tables      |
| :------------------ | -------------------: | :-------------: |
| left-aligned column | right-aligned column | centered column |
| $100                |                 $100 |      $100       |
| $10                 |                  $10 |       $10       |
| $1                  |                   $1 |       $1        |


### Links

[README.md](README.md "Paper Summit's README")

[How to use Markdown for writing Docs](https://docs.microsoft.com/ko-kr/contribute/how-to-write-use-markdown "How to use Markdown for writing Docs")

### Code snippets

    codeblock
    use like this
    using at least 4 spaces or 1 tab

```alias
...
your code goes in here
...
```
```python
...
import tensorflow as tf
...
```

| Name                                | Markdown Label     |
| ----------------------------------- | ------------------ |
| .NET Console                        | dotnetcli          |
| ASP.NET (C#)                        | aspx-csharp        |
| ASP.NET (VB)                        | aspx-vb            |
| AzCopy                              | azcopy             |
| Azure CLI                           | azurecli           |
| Azure PowerShell                    | azurepowershell    |
| Bash                                | bash               |
| C++                                 | cpp                |
| C++/CX                              | cppcx              |
| C++/WinRT                           | cppwinrt           |
| C#                                  | csharp             |
| C# in browser                       | csharp-interactive |
| Console                             | console            |
| CSHTML                              | cshtml             |
| DAX                                 | dax                |
| Docker                              | dockerfile         |
| F#                                  | fsharp             |
| Go                                  | go                 |
| HTML                                | html               |
| HTTP                                | http               |
| Java                                | java               |
| JavaScript                          | javascript         |
| JSON                                | json               |
| Kusto Query Language                | kusto              |
| Markdown                            | md                 |
| Objective-C                         | objc               |
| OData                               | odata              |
| PHP                                 | php                |
| PowerApps (dot decimal separator)   | powerapps-dot      |
| PowerApps (comma decimal separator) | powerapps-comma    |
| PowerShell                          | powershell         |
| Python                              | python             |
| Q#                                  | qsharp             |
| R                                   | r                  |
| Ruby                                | ruby               |
| SQL                                 | sql                |
| Swift                               | swift              |
| TypeScript                          | typescript         |
| VB                                  | vb                 |
| XAML                                | xaml               |
| XML                                 | xml                |

```csharp
// Hello1.cs
public class Hello1
{
    public static void Main()
    {
        System.Console.WriteLine("Hello, World!");
    }
}
```

```sql
CREATE TABLE T1 (
  c1 int PRIMARY KEY,
  c2 varchar(50) SPARSE NULL
);
```

## Gotchas and troubleshooting

### Alt text

![The_New_Feature_Logo](더뉴피쳐_최종-01.png)

![Markdown](https://ko.wikipedia.org/wiki/%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4#/media/%ED%8C%8C%EC%9D%BC:Markdown-mark.svg)


![alt text for image](../images/Introduction.png)

$$
susic
$$

$$
y = ax + b
$$