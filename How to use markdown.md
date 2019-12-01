# How to use Markdown for writing Docs

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

### Bold and italic text

This text is **bold**.
`This text is **bold**.`

This text is *italic*.
`This text is *italic*.`

This is text is both ***bold and italic***.
`This is text is both ***bold and italic***.`

### Blockquotes

> The drought had lasted now for ten million years, and the reign of the terrible lizards had long since ended. Here on the Equator, in the continent which would one day be known as Africa, the battle for existence had reached a new climax of ferocity, and the victor was not yet in sight. In this barren and desiccated land, only the small or the swift or the fierce could flourish, or even hope to survive.

`> The drought had lasted now for ten million years, and the reign of the terrible lizards had long since ended. Here on the Equator, in the continent which would one day be known as Africa, the battle for existence had reached a new climax of ferocity, and the victor was not yet in sight. In this barren and desiccated land, only the small or the swift or the fierce could flourish, or even hope to survive.`

### Lists

#### Unordered list
- List item 1
`- List item 1`
- List item 2
`- List item 2`
- List item 3
`- List item 3`

- List item 1
`- List item 1`
  - List item A
  `- List item A`
  - List item B
  `- List item B`
- List item 2
`- List item 2`

#### Ordered list

1. First instruction
`1. First instruction`
1. Second instruction
`1. Second instruction`
1. Third instruction
`1. Third instruction`

0. First instruction
`0. First instruction`
   1. Sub-instruction
   `1. Sub-instruction`
   1. Sub-instruction
   `1. Sub-instruction`
1. Second instruction
`1. Second instruction`

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

[README.md](README.md)

[How to use Markdown for writing Docs](https://docs.microsoft.com/ko-kr/contribute/how-to-write-use-markdown)

### Code snippets
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

## Docs custom Markdown extensions

> [!NOTE]
> Information the user should notice even if skimming.

> [!TIP]
> Optional information to help a user be more successful.

> [!IMPORTANT]
> Essential information required for user success.

> [!CAUTION]
> Negative potential consequences of an action.

> [!WARNING]
> Dangerous certain consequences of an action.