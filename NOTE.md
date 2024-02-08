# `[!NOTE]` test

## Simple alerts

> [!NOTE]
> This is a note.

> [!TIP]
> This is a tip. (Supported since 14 Nov 2023)

> [!IMPORTANT]
> Crutial information comes here.

> [!CAUTION]
> Negative potential consequences of an action. (Supported since 14 Nov 2023)

> [!WARNING]
> Critical content comes here.

> [!NOTE]\
> This is a note. (hard line break `\`)

> [!NOTE]
> This is a note.
> multiple lines with a soft line break

> [!NOTE]
> This is a note.\
> multiple lines with a hard line break (`\`)

> [!NOTE] No character is allowed except a line break.
> This is a note.

> [!NOTE] No character is allowed except a line break.\
> This is a note.

> [!NOTE]
> 

> [!NOTE]<br>This is a one-liner note.

Broken since 14 Nov 2023
> [!NOTE]<br>

> [!NOTE]<br><br>

> [!NOTE]<br>
> This is a note.

## nested alerts

> [!NOTE]
> This is a note.
>> [!NOTE]
>> This is a note (broken).

> [!NOTE]
> This is a note.
>> [!NOTE]<br>This is a one-liner note (broken).

> [!NOTE]<br>This is a one-liner note.
>> [!NOTE]<br>This is a one-liner note (broken).

> [!NOTE]
> This is a note.
>>
>> [!NOTE]
>> This is a note (broken).

> [!NOTE]
> This is a note.
>>
>> [!NOTE]<br>This is a one-liner note (broken).

> [!NOTE]
> This is a note.
>>
> [!NOTE]
> This is a note (broken).

> [!NOTE]
> This is a note.
>>
> [!NOTE]<br>This is a one-liner note (broken).

> [!NOTE]<br>This is a one-liner note.
>>
> [!NOTE]
> This is a note (broken).

> [!NOTE]<br>This is a one-liner note.
>>
> [!NOTE]<br>This is a one-liner note (broken).

> [!NOTE]
>
>> [!NOTE]
>> This is a note (broken).

> [!NOTE]
>
>> [!NOTE]<br>This is a one-liner note (broken).

> [!NOTE]
>>
>> [!NOTE]
>> This is a note (broken).

> [!NOTE]
>>
>> [!NOTE]<br>This is a one-liner note (broken).

> [!NOTE]
>>
> [!NOTE]
> This is a note (broken).

> [!NOTE]
>>
> [!NOTE]<br>This is a one-liner note (broken).

## block quote

### alerts in quotes (broken since 14 Nov 2023)

> This breaks the syntax.
> [!NOTE]
> This is a note.

> This breaks the syntax.\
> [!NOTE]
> This is a note.

> This breaks the syntax.<br>
> [!NOTE]
> This is a note.

> This breaks the syntax.
>
> [!NOTE]
> This is a note.

> This breaks the syntax.
> [!NOTE]<br>This is a one-liner note.

> This is a quote.
>> [!NOTE]
>> This is a note.

> This is a quote.
>> [!NOTE]<br>This is a one-liner note.

> This is a quote.
>
>> [!NOTE]
>> This is a note.

> This is a quote.
>
>> [!NOTE]<br>This is a one-liner note.

> This is a quote.
>>
>> [!NOTE]
>> This is a note.

> This is a quote.
>>
>> [!NOTE]<br>This is a one-liner note.

> This is a quote.
>>
> [!NOTE]
> This is a note (broken).

> This is a quote.
>>
> [!NOTE]<br>This is a one-liner note (broken).

> This is a quote.
> > [!NOTE]
> > This is a note.

> This is a quote.
> > [!NOTE]<br>This is a one-liner note.

> This is a quote.
>
> > [!NOTE]
> > This is a note.

> This is a quote.
>
> > [!NOTE]<br>This is a one-liner note.

> This is a quote.
> >
> > [!NOTE]
> > This is a note.

> This is a quote.
> >
> > [!NOTE]<br>This is a one-liner note.

> This is a quote.
> >
> [!NOTE]
> This is a note (broken).

> This is a quote.
> >
> [!NOTE]<br>This is a one-liner note (broken).

### quotes in alerts

> [!NOTE]
> This is a note.
>> This is indented (`>>`).

> [!NOTE]
>> This is indented (`>>`).

> [!NOTE]
>> This is indented (`>>`).
>>> This is indented (`>>>`).

> [!NOTE]
>>> This is indented (`>>>`).

> [!NOTE]
> This is a note.
> > This is a quote.

> [!NOTE]
> > This is a quote.

> [!NOTE]
> > This is a quote.
> > > This is a quote (`> > > `).

> [!NOTE]
> > > This is a quote (`> > > `).

> This is a quote.
>> [!NOTE]
>>> This is indented (`>>>`).

> This is a quote.
> > [!NOTE]
> > > This is a quote (`> > > `).

## thematic break and setext heading

> [!NOTE]
> This is a note (broken).
> ---

> [!NOTE]
> 
> This is `<h2>` text.
> ---

> [!NOTE]
> 
> This is `<h1>` text.
> ===

> [!NOTE]
> This is a note.
> 
> ---

> [!NOTE]
> This is a note.
> 
> ---
> after the break

> [!NOTE]
> ---

> [!NOTE]
> 
> ---

> [!NOTE]<br>This is a note using `<br>` (broken).
> ---

> [!NOTE]<br>This is a note using `<br>`.
> 
> ---

> [!NOTE]
> This is a note (not broken).
> ___

> [!NOTE]
> This is a note.
> 
> ___

> [!NOTE]
> This is a note.
> ___
> after the break

> [!NOTE]
> This is a note.
> 
> ___
> after the break

> [!NOTE]
> ___

> [!NOTE]
> 
> ___

> [!NOTE]<br>This is a note using `<br>` (not broken).
> ___

> [!NOTE]<br>This is a note using `<br>`.
> 
> ___

> [!NOTE]
> This is a note (not broken).
> ***

> [!NOTE]
> This is a note.
> 
> ***

> [!NOTE]
> This is a note.
> ***
> after the break

> [!NOTE]
> This is a note.
> 
> ***
> after the break

> [!NOTE]
> ***

> [!NOTE]
> 
> ***

> [!NOTE]<br>This is a note using `<br>` (not broken).
> ***

> [!NOTE]<br>This is a note using `<br>`.
> 
> ***

> [!NOTE]<br>This is a one-liner note using `<br>`.<hr />after the break

> [!NOTE]<br><hr />

## code block

simple indented code block

    fn main () {
      println!("Hello, World!");
    }


simple fenced code block
```
fn main () {
  println!("Hello, World!");
}
```

fenced code block with syntax highlighting
```rust
fn main () {
  println!("Hello, World!");
}
```

> [!NOTE]
> This is a note.
> 
>     fn main () {
>       println!("Hello, World!");
>     }
> 

> [!NOTE]
> 
>     fn main () {
>       println!("Hello, World!");
>     }
> 

> [!NOTE]
> This is a note.
> ```
> fn main() {
>   println!("Hello, World!");
> }
> ```

> [!NOTE]
> ```
> fn main() {
>   println!("Hello, World!");
> }
> ```

> [!NOTE]
> This is a note.
> ```rust
> fn main() {
>   println!("Hello, World!");
> }
> ```

> [!NOTE]
> ```rust
> fn main() {
>   println!("Hello, World!");
> }
> ```

## MathJax (directly supported since 14 Nov 2023)

> [!NOTE]
> This is a note.
> $\LaTeX$

> [!NOTE]
> This is a note.\
> $\LaTeX$

> [!NOTE]
> This is a note.<br>
> $\LaTeX$

> [!NOTE]
> $\LaTeX$

> [!NOTE]
> Here is $\LaTeX$.

> [!NOTE]
> This is a note.
> $$\LaTeX$$

> [!NOTE]
> This is a note.\
> $$\LaTeX$$

> [!NOTE]
> This is a note.<br>
> $$\LaTeX$$

> [!NOTE]
> $$\LaTeX$$

> [!NOTE]
> Here is $$\LaTeX$$.

> [!NOTE]<br>This is a one-liner note.<br>$\LaTeX$

> [!NOTE]<br>$\LaTeX$

> [!NOTE]<br>Here is $\LaTeX$.

> [!NOTE]<br>This is a one-liner note.<br>$$\LaTeX$$

> [!NOTE]<br>$$\LaTeX$$

> [!NOTE]<br>Here is $$\LaTeX$$.

> [!NOTE]
> This is a note.
> $$ \LaTeX $$

> [!NOTE]
> This is a note.
> 
> $$ \LaTeX $$

> [!NOTE]
> $$ \LaTeX $$

> [!NOTE]
> This is a note.
> $$
> \LaTeX
> $$

> [!NOTE]
> This is a note.
> 
> $$
> \LaTeX
> $$

> [!NOTE]
> $$
> \LaTeX
> $$

> [!NOTE]
> This is a note.
> ```math
> \LaTeX
> ```

> [!NOTE]
> ```math
> \LaTeX
> ```

## list

### alerts in lists (broken since 14 Nov 2023)

- This is a bullet list with `-`.
  > [!NOTE]
  > This is a note.

- This is a bullet list with `-`.
  > [!NOTE]<br>This is a one-liner note.

- > [!NOTE]
  > This is a note.

- > [!NOTE]<br>This is a one-liner note.

+ This is a bullet list with `+`.
  > [!NOTE]
  > This is a note.

+ This is a bullet list with `+`.
  > [!NOTE]<br>This is a one-liner note.

+ > [!NOTE]
  > This is a note.

+ > [!NOTE]<br>This is a one-liner note.

* This is a bullet list with `*`.
  > [!NOTE]
  > This is a note.

* This is a bullet list with `*`.
  > [!NOTE]<br>This is a one-liner note.

* > [!NOTE]
  > This is a note.

* > [!NOTE]<br>This is a one-liner note.

- This is a bullet list with `-`.
  > [!NOTE]
  > This is a note.
  + subitem with `+`
    > [!NOTE]
    > This is a note.
    * subitem with `*`
      > [!NOTE]
      > This is a note.

1. This is an ordered list.
   > [!NOTE]
   > This is a note.
<br>

1. This is an ordered list.
   > [!NOTE]<br>This is a one-liner note.
<br>

1. > [!NOTE]
   > This is a note.
<br>

1. This is an ordered list.
1. > [!NOTE]
   > This is a note.
<br>

1. > [!NOTE]<br>This is a one-liner note.
<br>

1. This is an ordered list.
   > [!NOTE]
   > This is a note.
   1. This is an ordered list.
      > [!NOTE]
      > This is a note.
      1. This is an ordered list.
         > [!NOTE]
         > This is a note.
<br>

- [ ] This is a task list (`-`).
  > [!NOTE]
  > This is a note.

- [x] This is a task list with a checked task (`-`).
  > [!NOTE]
  > This is a note.

- [ ] This is a task list (`-`).
  > [!NOTE]<br>This is a one-liner note.

- [x] This is a task list with a checked task (`-`).
  > [!NOTE]<br>This is a one-liner note.

+ [ ] This is a task list (`+`).
  > [!NOTE]
  > This is a note.

+ [x] This is a task list with a checked task (`+`).
  > [!NOTE]
  > This is a note.

+ [ ] This is a task list (`+`).
  > [!NOTE]<br>This is a one-liner note.

+ [x] This is a task list with a checked task (`+`).
  > [!NOTE]<br>This is a one-liner note.

* [ ] This is a task list (`*`).
  > [!NOTE]
  > This is a note.

* [x] This is a task list with a checked task (`*`).
  > [!NOTE]
  > This is a note.

* [ ] This is a task list (`*`).
  > [!NOTE]<br>This is a one-liner note.

* [x] This is a task list with a checked task (`*`).
  > [!NOTE]<br>This is a one-liner note.

1. [ ] This is a task list. The number `1. ` won't be shown.
   > [!NOTE]
   > This is a note.
<br>

1. [x] This is a task list with a checked task. The number `1. ` won't be shown.
   > [!NOTE]
   > This is a note.
<br>

1. [ ] This is a task list. The number `1. ` won't be shown.
   > [!NOTE]<br>This is a one-liner note.
<br>

1. [x] This is a task list with a checked task. The number `1. ` won't be shown.
   > [!NOTE]<br>This is a one-liner note.
<br>

- [ ] This is a task list.
  > [!NOTE]
  > This is a note.
  - [x] This is a task list.
    > [!NOTE]
    > This is a note.

### lists in alerts

> [!NOTE]
> This is a note.
> - This is a bullet list with `-`.

> [!NOTE]
> - This is a bullet list with `-` directly in an alert.

- This is a bullet list with `-`.
  > [!NOTE]
  > This is a note.
  > - This is a bullet list with `-`.

- This is a bullet list with `-`.
  > [!NOTE]
  > - This is a bullet list with `-` directly in an alert.

- > [!NOTE]
  > This is a note.
  > - This is a bullet list with `-`.

- > [!NOTE]
  > - This is a bullet list with `-` directly in an alert.

> [!NOTE]
> This is a note.
> + This is a bullet list with `+`.

> [!NOTE]
> + This is a bullet list with `+` directly in an alert.

+ This is a bullet list with `+`.
  > [!NOTE]
  > This is a note.
  > + This is a bullet list with `+`.

+ This is a bullet list with `+`.
  > [!NOTE]
  > + This is a bullet list with `+` directly in an alert.

+ > [!NOTE]
  > This is a note.
  > + This is a bullet list with `+`.

+ > [!NOTE]
  > + This is a bullet list with `+` directly in an alert.

> [!NOTE]
> This is a note.
> * This is a bullet list with `*`.

> [!NOTE]
> * This is a bullet list with `*` directly in an alert.

* This is a bullet list with `*`.
  > [!NOTE]
  > This is a note.
  > * This is a bullet list with `*`.

* This is a bullet list with `*`.
  > [!NOTE]
  > * This is a bullet list with `*` directly in an alert.

* > [!NOTE]
  > This is a note.
  > * This is a bullet list with `*`.

* > [!NOTE]
  > * This is a bullet list with `*` directly in an alert.

- > [!NOTE]
  > + This is a bullet list with `+` directly in an alert.
  >   * subitem with `*`

- This is a bullet list with `-`.
  > [!NOTE]
  > + This is a bullet list with `+` directly in an alert.
  >   * subitem with `*`
  + subitem with `+`
    > [!NOTE]
    > * This is a bullet list with `*` directly in an alert.
    >   - subitem with `-`
    * subitem with `*`
      > [!NOTE]
      > - This is a bullet list with `-` directly in an alert.
      >   + subitem with `+`

> [!NOTE]
> This is a note.
> 1. This is an ordered list.

> [!NOTE]
> 1. This is an ordered list directly in an alert.

> [!NOTE]
> 1. This is an ordered list directly in an alert.
>    1. subitem
>       1. subitem

1. This is an ordered list.
   > [!NOTE]
   > This is a note.
   > 1. This is an ordered list.
<br>

1. This is an ordered list.
   > [!NOTE]
   > 1. This is an ordered list directly in an alert.
<br>

1. > [!NOTE]
   > This is a note.
   > 1. This is an ordered list.
<br>

1. > [!NOTE]
   > 1. This is an ordered list directly in an alert.
<br>

1. This is an ordered list.
   > [!NOTE]
   > 1. This is an ordered list directly in an alert.
   >    1. subitem
   >       1. subitem
   1. This is an ordered list.
      > [!NOTE]
      > 1. This is an ordered list directly in an alert.
      >    1. subitem
      >       1. subitem
      1. This is an ordered list.
         > [!NOTE]
         > 1. This is an ordered list directly in an alert.
         >    1. subitem
         >       1. subitem
<br>

> [!NOTE]
> This is a note.
> - [ ] This is a task list (`-`).
> - [x] This is a task list with a checked task (`-`).
> + [ ] This is a task list (`+`).
> + [x] This is a task list with a checked task (`+`).
> * [ ] This is a task list (`*`).
> * [x] This is a task list with a checked task (`*`).
> 1. [ ] This is a task list.
> 1. [x] This is a task list with a checked task.

> [!NOTE]
> - [ ] This is a task list directly in an alert.

- [ ] This is a task list.
  > [!NOTE]
  > This is a note.
  > - [ ] This is a task list.

- [ ] This is a task list.
  > [!NOTE]
  > - [ ] This is a task list directly in an alert.

- [ ] This is a task list.
  > [!NOTE]
  > - [ ] This is a task list directly in an alert.
  - [x] This is a task list.
    > [!NOTE]
    > - [x] This is a task list directly in an alert.

## table (GitHub Flavored Markdown)

### tables in alerts

> [!NOTE]
> | Header 1 | Header 2 |
> | --- | --- |
> | a | b |
> | c | d |

> [!NOTE]
> | Left-aligned | Center-aligned | Right-aligned |
> | :--- | :---: | ---: |
> | abc | abc | abc |
> | 1234 | 1234 | 1234 |

### alerts in tables (not supported)

| NOTE | IMPORTANT | WARNING |
| --- | --- | --- |
| > [!NOTE]<br>This is a note. | > [!IMPORTANT]<br>This is important. | > [!WARNING]<br>This is a warning. |
| > [!NOTE]<br>This is a note.<br>second line | > [!IMPORTANT]<br>This is important.<br>second line | > [!WARNING]<br>This is a warning.<br>second line |

| Header | > [!NOTE]<br>This is a note. |
| --- | --- |
| Content | NOTE |

| Left-aligned | Center-aligned | Right-aligned |
| :--- | :---: | ---: |
| > [!NOTE]<br>This is a note. | > [!NOTE]<br>This is a note. | > [!NOTE]<br>This is a note. |
| > [!IMPORTANT]<br>This is important. | > [!IMPORTANT]<br>This is important. | > [!IMPORTANT]<br>This is important. |
| > [!WARNING]<br>This is a warning. | > [!WARNING]<br>This is a warning. | > [!WARNING]<br>This is a warning. |

> [!NOTE]
> | NOTE | IMPORTANT | WARNING |
> | --- | --- | --- |
> | > [!NOTE]<br>This is a note. | > [!IMPORTANT]<br>This is important. | > [!WARNING]<br>This is a warning. |
> | > [!NOTE]<br>This is a note.<br>second line | > [!IMPORTANT]<br>This is important.<br>second line | > [!WARNING]<br>This is a warning.<br>second line |

> [!IMPORTANT]
> | Header | > [!NOTE]<br>This is a note. |
> | --- | --- |
> | Content | NOTE |

> [!WARNING]
> | Left-aligned | Center-aligned | Right-aligned |
> | :--- | :---: | ---: |
> | > [!NOTE]<br>This is a note. | > [!NOTE]<br>This is a note. | > [!NOTE]<br>This is a note. |
> | > [!IMPORTANT]<br>This is important. | > [!IMPORTANT]<br>This is important. | > [!IMPORTANT]<br>This is important. |
> | > [!WARNING]<br>This is a warning. | > [!WARNING]<br>This is a warning. | > [!WARNING]<br>This is a warning. |

## `<table>`

### `<table>` in alerts

> [!NOTE]
> This is a note.
> <table>
> <tr>
> <td>
> This is inside <code>&lt;table&gt;&lt;tr&gt;&lt;td&gt;</code>.
> </td>
> </tr>
> </table>

> [!NOTE]
> <table>
> <tr>
> <td>
> This is inside <code>&lt;table&gt;&lt;tr&gt;&lt;td&gt;</code>.
> </td>
> </tr>
> </table>

> [!NOTE]
> <table><tr><td>This is inside <code>&lt;table&gt;&lt;tr&gt;&lt;td&gt;</code>.</td></tr></table>

> [!NOTE]<br>This is a one-liner note.<br><table><tr><td>This is inside `<table><tr><td>`.</td></tr></table>

> [!NOTE]<br>This is a one-liner note.<table><tr><td>This is inside `<table><tr><td>`.</td></tr></table>

> [!NOTE]<br><table><tr><td>This is inside `<table><tr><td>`.</td></tr></table>

> [!NOTE]
> This is a note.
> <table>
> <tr>
> This is inside <code>&lt;table&gt;&lt;tr&gt;</code>.
> </tr>
> </table>

> [!NOTE]
> <table>
> <tr>
> This is inside <code>&lt;table&gt;&lt;tr&gt;</code>.
> </tr>
> </table>

> [!NOTE]
> <table><tr>This is inside <code>&lt;table&gt;&lt;tr&gt;</code>.</tr></table>

> [!NOTE]<br>This is a one-liner note.<br><table><tr>This is inside `<table><tr>`.</tr></table>

> [!NOTE]<br>This is a one-liner note.<table><tr>This is inside `<table><tr>`.</tr></table>

> [!NOTE]<br><table><tr>This is inside `<table><tr>`.</tr></table>

> [!NOTE]
> This is a note.
> <table>
> This is inside <code>&lt;table&gt;</code>.
> </table>

> [!NOTE]
> <table>
> This is inside <code>&lt;table&gt;</code>.
> </table>

> [!NOTE]
> <table>This is inside <code>&lt;table&gt;</code>.</table>

> [!NOTE]<br>This is a one-liner note.<br><table>This is inside `<table>`.</table>

> [!NOTE]<br>This is a one-liner note.<table>This is inside `<table>`.</table>

> [!NOTE]<br><table>This is inside `<table>`.</table>

> [!NOTE]
> <table>
> <thead>
> <tr>
> <th>Header 1</th>
> <th>Header 2</th>
> </tr>
> </thead>
> <tbody>
> <tr>
> <td>a</td>
> <td>b</td>
> </tr>
> <tr>
> <td>c</td>
> <td>d</td>
> </tr>
> </tbody>
> </table>

> [!NOTE]<br><table><thead><tr><th>Header 1</th><th>Header 2</th></tr></thead><tbody><tr><td>a</td><td>b</td></tr><tr><td>c</td><td>d</td></tr></tbody></table>

> [!NOTE]
> <table>
> <tr>
> <th>Header 1</th>
> <th>Header 2</th>
> </tr>
> <tr>
> <td>a</td>
> <td>b</td>
> </tr>
> <tr>
> <td>c</td>
> <td>d</td>
> </tr>
> </table>

> [!NOTE]<br><table><tr><th>Header 1</th><th>Header 2</th></tr><tr><td>a</td><td>b</td></tr><tr><td>c</td><td>d</td></tr></table>

> [!NOTE]
> <table>
> <thead>
> <tr>
> <th align="left">Left</th>
> <th align="center">Center</th>
> <th align="right">Right</th>
> </tr>
> </thead>
> <tbody>
> <tr>
> <td align="left">abcdefg</td>
> <td align="center">abcdefg</td>
> <td align="right">abcdefg</td>
> </tr>
> <tr>
> <td align="left">1234</td>
> <td align="center">1234</td>
> <td align="right">1234</td>
> </tr>
> </tbody>
> </table>

> [!NOTE]<br><table><thead><tr><th align="left">Left</th><th align="center">Center</th><th align="right">Right</th></tr></thead><tbody><tr><td align="left">abcdefg</td><td align="center">abcdefg</td><td align="right">abcdefg</td></tr><tr><td align="left">1234</td><td align="center">1234</td><td align="right">1234</td></tr></tbody></table>

> [!NOTE]
> <table>
> <thead>
> <tr>
> <th align="left">Left</th>
> <th align="center">Center</th>
> <th align="right">Right</th>
> </tr>
> </thead>
> <tbody>
> <tr>
> <td>abcdefg</td>
> <td>abcdefg</td>
> <td>abcdefg</td>
> </tr>
> <tr>
> <td>1234</td>
> <td>1234</td>
> <td>1234</td>
> </tr>
> </tbody>
> </table>

> [!NOTE]<br><table><thead><tr><th align="left">Left</th><th align="center">Center</th><th align="right">Right</th></tr></thead><tbody><tr><td>abcdefg</td><td>abcdefg</td><td>abcdefg</td></tr><tr><td>1234</td><td>1234</td><td>1234</td></tr></tbody></table>

> [!NOTE]
> <table>
> <thead>
> <tr>
> <th>Header 1</th>
> <th>Header 2</th>
> <th>Header 3</th>
> </tr>
> </thead>
> <tbody>
> <tr>
> <td align="left">abc</td>
> <td align="center">abc</td>
> <td align="right">abc</td>
> </tr>
> <tr>
> <td align="right">1234</td>
> <td align="center">1234</td>
> <td align="left">1234</td>
> </tr>
> </tbody>
> </table>

> [!NOTE]<br><table><thead><tr><th>Header 1</th><th>Header 2</th><th>Header 3</th></tr></thead><tbody><tr><td align="left">abc</td><td align="center">abc</td><td align="right">abc</td></tr><tr><td align="right">1234</td><td align="center">1234</td><td align="left">1234</td></tr></tbody></table>

### alerts in `<table>`

<table>
<tr>
<td>
> [!NOTE]
> This is a note.
</td>
</tr>
</table>

<table>
<tr>
<td>

> [!NOTE]
> This is a note.

</td>
</tr>
</table>

<table>
<tr>
<td>
> [!NOTE]<br>This is a one-liner note.
</td>
</tr>
</table>

<table>
<tr>
<td>

> [!NOTE]<br>This is a one-liner note.

</td>
</tr>
</table>

<table><tr><td>> [!NOTE]<br>This is a one-liner note.</td></tr></table>

<table>
<tr>
> [!NOTE]
> This is a note.
</tr>
</table>

<table>
<tr>

> [!NOTE]
> This is a note.

</tr>
</table>

<table>
<tr>
> [!NOTE]<br>This is a one-liner note.
</tr>
</table>

<table>
<tr>

> [!NOTE]<br>This is a one-liner note.

</tr>
</table>

<table><tr>> [!NOTE]<br>This is a one-liner note.</tr></table>

<table>
> [!NOTE]
> This is a note.
</table>

<table>

> [!NOTE]
> This is a note.

</table>

<table>
> [!NOTE]<br>This is a one-liner note.
</table>

<table>

> [!NOTE]<br>This is a one-liner note.

</table>

<table>> [!NOTE]<br>This is a one-liner note.</table>

<table>
<tr>
<td>

> [!NOTE]
> This is a note.
> <table>
> <tr>
> <td>
> This is inside <code>&lt;table&gt;&lt;tr&gt;&lt;td&gt;</code>.
> </td>
> </tr>
> </table>

</td>
</tr>
</table>

<table>
<tr>
<td>

> [!NOTE]<br>This is a note.<br><table><tr><td>This is inside `<table><tr><td>`.</td></tr></table>

</td>
</tr>
</table>

<table>
<thead>
<tr>
<th>NOTE</th>
<th>TIP</th>
<th>IMPORTANT</th>
<th>CAUTION</th>
<th>WARNING</th>
</tr>
</thead>
<tbody>

<tr>

<td>

> [!NOTE]
> This is a note.

</td>

<td>

> [!TIP]
> This is a tip.

</td>

<td>

> [!IMPORTANT]
> This is important.

</td>

<td>

> [!CAUTION]
> This is a caution.

</td>

<td>

> [!WARNING]
> This is a warning.

</td>

</tr>

<tr>

<td>

> [!NOTE]<br>This is a one-liner note.

</td>

<td>

> [!TIP]<br>This is a one-liner tip.

</td>

<td>

> [!IMPORTANT]<br>This is important (one-liner).

</td>

<td>

> [!CAUTION]<br>This is a one-liner caution.

</td>

<td>

> [!WARNING]<br>This is a one-liner warning.

</td>

</tr>

</tbody>
</table>

<table>
<thead>
<tr>

<th>Header</th>

<th>

> [!NOTE]<br>This is a one-liner note.

</th>

</tr>
</thead>
<tbody>
<tr>
<td>Content</td>
<td>NOTE</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Left-aligned</th>
<th align="center">Center-aligned</th>
<th align="right">Right-aligned</th>
</tr>
</thead>
<tbody>

<tr>

<td align="left">

> [!NOTE]
> This is a note.

> [!NOTE]<br>This is a one-liner note.

</td>

<td align="center">

> [!NOTE]
> This is a note.

> [!NOTE]<br>This is a one-liner note.

</td>

<td align="right">

> [!NOTE]
> This is a note.

> [!NOTE]<br>This is a one-liner note.

</td>

</tr>

<tr>

<td align="left">

> [!TIP]
> This is a tip.

> [!TIP]<br>This is a one-liner tip.

</td>

<td align="center">

> [!TIP]
> This is a tip.

> [!TIP]<br>This is a one-liner tip.

</td>

<td align="right">

> [!TIP]
> This is a tip.

> [!TIP]<br>This is a one-liner tip.

</td>

</tr>

<tr>

<td align="left">

> [!IMPORTANT]
> This is important.

> [!IMPORTANT]<br>This is important (one-liner).

</td>

<td align="center">

> [!IMPORTANT]
> This is important.

> [!IMPORTANT]<br>This is important (one-liner).

</td>

<td align="right">

> [!IMPORTANT]
> This is important.

> [!IMPORTANT]<br>This is important (one-liner).

</td>

</tr>

<tr>

<td align="left">

> [!CAUTION]
> This is a caution.

> [!CAUTION]<br>This is a one-liner caution.

</td>

<td align="center">

> [!CAUTION]
> This is a caution.

> [!CAUTION]<br>This is a one-liner caution.

</td>

<td align="right">

> [!CAUTION]
> This is a caution.

> [!CAUTION]<br>This is a one-liner caution.

</td>

</tr>

<tr>

<td align="left">

> [!WARNING]
> This is a warning.

> [!WARNING]<br>This is a one-liner warning.

</td>

<td align="center">

> [!WARNING]
> This is a warning.

> [!WARNING]<br>This is a one-liner warning.

</td>

<td align="right">

> [!WARNING]
> This is a warning.

> [!WARNING]<br>This is a one-liner warning.

</td>

</tr>

</tbody>
</table>

> [!NOTE]
> <table>
> <tr>
> <td>

> [!NOTE]
> This is a note.

> </td>
> </tr>
> </table>

### with MathJax

> [!NOTE]
> <table>
> <tr>
> <td>
> $\LaTeX$
> </td>
> </tr>
> </table>

> [!NOTE]
> <table><tr><td>$\LaTeX$</td></tr></table>

> [!NOTE]
> <table>
> <tr>
> <td>
> $$\LaTeX$$
> </td>
> </tr>
> </table>

> [!NOTE]
> <table><tr><td>$$\LaTeX$$</td></tr></table>

> [!NOTE]
> <table>
> <tr>
> <td>
> $$
> \LaTeX
> $$
> </td>
> </tr>
> </table>

> [!NOTE]
> <table>
> <tr>
> <td>
> 
> $$
> \LaTeX
> $$
> 
> </td>
> </tr>
> </table>

> [!NOTE]
> <table>
> <tr>
> <td>
> ```math
> \LaTeX
> ```
> </td>
> </tr>
> </table>

> [!NOTE]
> <table>
> <tr>
> <td>
> 
> ```math
> \LaTeX
> ```
> 
> </td>
> </tr>
> </table>

<table>
<tr>
<td>

$\LaTeX$
> [!NOTE]
> This is a note.

</td>
</tr>
</table>

<table>
<tr>
<td>

$$\LaTeX$$
> [!NOTE]
> This is a note.

</td>
</tr>
</table>

<table>
<tr>
<td>

$$
\LaTeX
$$
> [!NOTE]
> This is a note.

</td>
</tr>
</table>

<table>
<tr>
<td>

```math
\LaTeX
```
> [!NOTE]
> This is a note.

</td>
</tr>
</table>

<table>
<tr>
<td>

$\LaTeX$
> [!NOTE]<br>This is a one-liner note.

</td>
</tr>
</table>

<table>
<tr>
<td>

$$\LaTeX$$
> [!NOTE]<br>This is a one-liner note.

</td>
</tr>
</table>

<table>
<tr>
<td>

$$
\LaTeX
$$
> [!NOTE]<br>This is a one-liner note.

</td>
</tr>
</table>

<table>
<tr>
<td>

```math
\LaTeX
```
> [!NOTE]<br>This is a one-liner note.

</td>
</tr>
</table>

<table>
<tr>
<td>

> [!NOTE]
> $\LaTeX$

</td>
</tr>
</table>

<table>
<tr>
<td>

> [!NOTE]
> $$\LaTeX$$

</td>
</tr>
</table>

<table>
<tr>
<td>

> [!NOTE]
> $$
> \LaTeX
> $$

</td>
</tr>
</table>

<table>
<tr>
<td>

> [!NOTE]
> ```math
> \LaTeX
> ```

</td>
</tr>
</table>

<table>
<tr>
<td>

> [!NOTE]<br>$\LaTeX$

</td>
</tr>
</table>

<table>
<tr>
<td>

> [!NOTE]<br>$$\LaTeX$$

</td>
</tr>
</table>

<table>
<tr>

<td>

> [!NOTE]
> This is a note.

</td>

<td>

$\LaTeX$

</td>

</tr>
</table>

<table>
<tr>

<td>

> [!NOTE]
> This is a note.

</td>

<td>

$$\LaTeX$$

</td>

</tr>
</table>

<table>
<tr>

<td>

> [!NOTE]
> This is a note.

</td>

<td>

$$
\LaTeX
$$

</td>

</tr>
</table>

<table>
<tr>

<td>

> [!NOTE]
> This is a note.

</td>

<td>

```math
\LaTeX
```

</td>

</tr>
</table>

<table>
<tr>

<td>

> [!NOTE]<br>This is a one-liner note.

</td>

<td>

$\LaTeX$

</td>

</tr>
</table>

<table>
<tr>

<td>

> [!NOTE]<br>This is a one-liner note.

</td>

<td>

$$\LaTeX$$

</td>

</tr>
</table>

<table>
<tr>

<td>

> [!NOTE]<br>This is a one-liner note.

</td>

<td>

$$
\LaTeX
$$

</td>

</tr>
</table>

<table>
<tr>

<td>

> [!NOTE]<br>This is a one-liner note.

</td>

<td>

```math
\LaTeX
```

</td>

</tr>
</table>

<table>

<tr>
<td>

> [!NOTE]
> This is a note.

</td>
</tr>

<tr>
<td>

$\LaTeX$

</td>
</tr>

</table>

<table>

<tr>
<td>

> [!NOTE]
> This is a note.

</td>
</tr>

<tr>
<td>

$$\LaTeX$$

</td>
</tr>

</table>

<table>

<tr>
<td>

> [!NOTE]
> This is a note.

</td>
</tr>

<tr>
<td>

$$
\LaTeX
$$

</td>
</tr>

</table>

<table>

<tr>
<td>

> [!NOTE]
> This is a note.

</td>
</tr>

<tr>
<td>

```math
\LaTeX
```

</td>
</tr>

</table>

<table>

<tr>
<td>

> [!NOTE]<br>This is a one-liner note.

</td>
</tr>

<tr>
<td>

$\LaTeX$

</td>
</tr>

</table>

<table>

<tr>
<td>

> [!NOTE]<br>This is a one-liner note.

</td>
</tr>

<tr>
<td>

$$\LaTeX$$

</td>
</tr>

</table>

<table>

<tr>
<td>

> [!NOTE]<br>This is a one-liner note.

</td>
</tr>

<tr>
<td>

$$
\LaTeX
$$

</td>
</tr>

</table>

<table>

<tr>
<td>

> [!NOTE]<br>This is a one-liner note.

</td>
</tr>

<tr>
<td>

```math
\LaTeX
```

</td>
</tr>

</table>

## `<div>`

### `<div>` in alerts

> [!NOTE]
> This is a note.
> <div align="center">
> This is inside <code>&lt;div&gt;</code>.
> </div>

> [!NOTE]
> <div align="center">
> This is inside <code>&lt;div&gt;</code>.
> </div>

> [!NOTE]
> <div align="center">This is inside <code>&lt;div&gt;</code>.</div>

> [!NOTE]<br>This is a one-liner note.<br><div align="center">This is inside `<div>`.</div>

> [!NOTE]<br>This is a one-liner note.<div align="center">This is inside `<div>`.</div>

> [!NOTE]<br><div align="center">This is inside `<div>`.</div>

### alerts in `<div>` (broken since 28 Nov 2023?)

<div align="center">
> [!NOTE]
> This is a note.
</div>

<div align="center">

> [!NOTE]
> This is a note.

</div>

<div align="center">
> [!NOTE]
> This is a note.
> <div align="right">
> This is inside <code>&lt;div&gt;</code>.
> </div>
</div>

<div align="center">

> [!NOTE]
> This is a note.
> <div align="right">
> This is inside <code>&lt;div&gt;</code>.
> </div>

</div>

<div align="center">
> [!NOTE]<br>This is a one-liner note.
</div>

<div align="center">

> [!NOTE]<br>This is a one-liner note.

</div>

<div align="center">
> [!NOTE]<br>This is a one-liner note.<br><div align="right">This is inside <code>&lt;div&gt;</code>.</div>
</div>

<div align="center">

> [!NOTE]<br>This is a one-liner note.<br><div align="right">This is inside `<div>`.</div>

</div>

<div align="center">> [!NOTE]<br>This is a one-liner note.</div>

<div align="center">> [!NOTE]<br>This is a one-liner note.<br><div align="right">This is inside <code>&lt;div&gt;</code>.</div></div>

## `<html>`

<html>html</html>

<html>
<head>
head
</head>
<body>
body
</body>
</html>

### `<html>` in alerts

> [!NOTE]
> This is a note.
> <html>This is inside <code>&lt;html&gt;</code>.</html>

> [!NOTE]
> <html>This is inside <code>&lt;html&gt;</code>.</html>

> [!NOTE]<br>This is a one-liner note.<br><html>This is inside `<html>`.</html>

> [!NOTE]<br>This is a one-liner note.<html>This is inside `<html>`.</html>

> [!NOTE]<br><html>This is inside `<html>`.</html>

> [!NOTE]
> <html>
> This is inside <code>&lt;html&gt;</code>.
> </html>

> [!NOTE]
> <html>
> <head>
> This is inside <code>&lt;html&gt;&lt;head&gt;</code>.
> </head>
> <body>
> This is inside <code>&lt;html&gt;&lt;body&gt;</code>.
> </body>
> </html>

### alerts in `<html>`

<html>
> [!NOTE]
> This is a note.
</html>

<html>

> [!NOTE]
> This is a note.

</html>

<html>
> [!NOTE]
> This is a note.
> <html>
> This is inside <code>&lt;html&gt;</code>.
> </html>
</html>

<html>

> [!NOTE]
> This is a note.
> <html>
> This is inside <code>&lt;html&gt;</code>.
> </html>

</html>

<html>
> [!NOTE]<br>This is a one-liner note.
</html>

<html>

> [!NOTE]<br>This is a one-liner note.

</html>

<html>> [!NOTE]<br>This is a one-liner note.</html>

<html>
> [!NOTE]<br>This is a one-liner note.<br><html>This is inside <code>&lt;html&gt;</code>.</html>
</html>

<html>

> [!NOTE]<br>This is a one-liner note.<br><html>This is inside `<html>`.</html>

</html>

<html>> [!NOTE]<br>This is a one-liner note.<br><html>This is inside <code>&lt;html&gt;</code>.</html></html>
