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

You can write one-liner alerts using `<br>`.

> [!NOTE]<br>This is a one-liner note.

> [!NOTE]<br />This is a one-liner note.

Broken since 14 Nov 2023: no content after `<br>`

> [!NOTE]<br>

> [!NOTE]<br />

> [!NOTE]<br><br>

> [!NOTE]<br><br />

> [!NOTE]<br /><br>

> [!NOTE]<br /><br />

> [!NOTE]<br>
> This is a note.

> [!NOTE]<br />
> This is a note.

<br>br test</br>

> [!NOTE]<br></br>

> [!NOTE]
> This is a note.
> <br>This is inside <code>&lt;br&gt;</code>.</br>

> [!NOTE]
> <br>This is inside <code>&lt;br&gt;</code>.</br>

> [!NOTE]<br>This is a one-liner note.<br><br>This is inside `<br>`.</br>

> [!NOTE]<br>This is a one-liner note.<br>This is inside `<br>`.</br>

> [!NOTE]<br><br>This is inside `<br>`.</br>

> [!NOTE]<br>This is inside `<br>`.</br>

## nested alerts (not supported)

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

## `<hr>` (`<hr />`)

<hr />

<hr>hr test</hr>

> [!NOTE]
> This is a note.
> <hr />
> after the break

> [!NOTE]
> <hr />

> [!NOTE]<br>This is a one-liner note using `<br>`.<hr />after the break

> [!NOTE]<br><hr />

> [!NOTE]<hr />

> [!NOTE]<hr />after the break

> [!NOTE]
> This is a note.
> <hr>This is inside <code>&lt;hr&gt;</code>.</hr>

> [!NOTE]
> <hr>This is inside <code>&lt;hr&gt;</code>.</hr>

> [!NOTE]<br>This is a one-liner note.<br><hr>This is inside `<hr>`.</hr>

> [!NOTE]<br>This is a one-liner note.<hr>This is inside `<hr>`.</hr>

> [!NOTE]<br><hr>This is inside `<hr>`.</hr>

> [!NOTE]<hr>This is inside `<hr>`.</hr>

## ATX headings

> [!NOTE]
> This is a note.
> # This is `<h1>` text.
> ## This is `<h2>` text.
> ### This is `<h3>` text.
> #### This is `<h4>` text.
> ##### This is `<h5>` text.
> ###### This is `<h6>` text.

## `<h1>`&ndash;`<h6>`

### `<h1>`&ndash;`<h6>` in alerts

> [!NOTE]
> This is a note.
> <h1>This is <code>&lt;h1&gt;</code> text.</h1>
> <h2>This is <code>&lt;h2&gt;</code> text.</h2>
> <h3>This is <code>&lt;h3&gt;</code> text.</h3>
> <h4>This is <code>&lt;h4&gt;</code> text.</h4>
> <h5>This is <code>&lt;h5&gt;</code> text.</h5>
> <h6>This is <code>&lt;h6&gt;</code> text.</h6>

> [!NOTE]<br>Thi is a one-liner note.<h1>This is `<h1>` text.</h1><h2>This is `<h2>` text.</h2><h3>This is `<h3>` text.</h3><h4>This is `<h4>` text.</h4><h5>This is `<h5>` text.</h5><h6>This is `<h6>` text.</h6>

> [!NOTE]<br>Thi is a one-liner note.<br><h1>This is `<h1>` text.</h1><br><h2>This is `<h2>` text.</h2><br><h3>This is `<h3>` text.</h3><br><h4>This is `<h4>` text.</h4><br><h5>This is `<h5>` text.</h5><br><h6>This is `<h6>` text.</h6>

> [!NOTE]<h1>

> [!NOTE]<h1></h1>

> [!NOTE]<h2>

> [!NOTE]<h2></h2>

> [!NOTE]<h3>

> [!NOTE]<h3></h3>

> [!NOTE]<h4>

> [!NOTE]<h4></h4>

> [!NOTE]<h5>

> [!NOTE]<h5></h5>

> [!NOTE]<h6>

> [!NOTE]<h6></h6>

### alerts in `<h1>`&ndash;`<h6>` (not supported)

<h1>
> [!NOTE]
> This is a note.
</h1>

<h1>

> [!NOTE]
> This is a note.

</h1>

<h1>
> [!NOTE]<br>This is a one-liner note.
</h1>

<h1>

> [!NOTE]<br>This is a one-liner note.

</h1>

<h1>> [!NOTE]<br>This is a one-liner note.</h1>

<h2>
> [!NOTE]
> This is a note.
</h2>

<h2>

> [!NOTE]
> This is a note.

</h2>

<h2>
> [!NOTE]<br>This is a one-liner note.
</h2>

<h2>

> [!NOTE]<br>This is a one-liner note.

</h2>

<h2>> [!NOTE]<br>This is a one-liner note.</h2>

<h3>
> [!NOTE]
> This is a note.
</h3>

<h3>

> [!NOTE]
> This is a note.

</h3>

<h3>
> [!NOTE]<br>This is a one-liner note.
</h3>

<h3>

> [!NOTE]<br>This is a one-liner note.

</h3>

<h3>> [!NOTE]<br>This is a one-liner note.</h3>

<h4>
> [!NOTE]
> This is a note.
</h4>

<h4>

> [!NOTE]
> This is a note.

</h4>

<h4>
> [!NOTE]<br>This is a one-liner note.
</h4>

<h4>

> [!NOTE]<br>This is a one-liner note.

</h4>

<h4>> [!NOTE]<br>This is a one-liner note.</h4>

<h5>
> [!NOTE]
> This is a note.
</h5>

<h5>

> [!NOTE]
> This is a note.

</h5>

<h5>
> [!NOTE]<br>This is a one-liner note.
</h5>

<h5>

> [!NOTE]<br>This is a one-liner note.

</h5>

<h5>> [!NOTE]<br>This is a one-liner note.</h5>

<h6>
> [!NOTE]
> This is a note.
</h6>

<h6>

> [!NOTE]
> This is a note.

</h6>

<h6>
> [!NOTE]<br>This is a one-liner note.
</h6>

<h6>

> [!NOTE]<br>This is a one-liner note.

</h6>

<h6>> [!NOTE]<br>This is a one-liner note.</h6>

## `<hgroup>`

<hgroup>
<h4>This is <code>&lt;h4&gt;</code> text.</h4>
<p>This is <code>&lt;p&gt;</code> text.</p>
</hgroup>

<hgroup>
<h4>This is <code>&lt;h4&gt;</code> text.</h4>
<p>This is <code>&lt;p&gt;</code> text.</p>
<p>second <code>&lt;p&gt;</code></p>
</hgroup>

<hgroup>
<h4>This is <code>&lt;h4&gt;</code> text.</h4>
</hgroup>

<hgroup>
<h4>This is <code>&lt;h4&gt;</code> text.</h4>
<h5>This is <code>&lt;h5&gt;</code> text.</h5>
</hgroup>

<hgroup>
<h4>This is <code>&lt;h4&gt;</code> text.</h4>
<h5>This is <code>&lt;h5&gt;</code> text.</h5>
<p>This is <code>&lt;p&gt;</code> text.</p>
</hgroup>

### `<hgroup>` in alerts

> [!NOTE]
> This is a note.
> <hgroup>
> <h4>This is <code>&lt;h4&gt;</code> text.</h4>
> <p>This is <code>&lt;p&gt;</code> text.</p>
> </hgroup>

> [!NOTE]
> <hgroup>
> <h4>This is <code>&lt;h4&gt;</code> text.</h4>
> <p>This is <code>&lt;p&gt;</code> text.</p>
> </hgroup>

> [!NOTE]
> <hgroup>
> <h4>This is <code>&lt;h4&gt;</code> text.</h4>
> <p>This is <code>&lt;p&gt;</code> text.</p>
> <p>second <code>&lt;p&gt;</code></p>
> </hgroup>

> [!NOTE]
> <hgroup>
> <h4>This is <code>&lt;h4&gt;</code> text.</h4>
> </hgroup>

> [!NOTE]
> <hgroup>
> <h4>This is <code>&lt;h4&gt;</code> text.</h4>
> <h5>This is <code>&lt;h5&gt;</code> text.</h5>
> </hgroup>

> [!NOTE]
> <hgroup>
> <h4>This is <code>&lt;h4&gt;</code> text.</h4>
> <h5>This is <code>&lt;h5&gt;</code> text.</h5>
> <p>This is <code>&lt;p&gt;</code> text.</p>
> </hgroup>

> [!NOTE]<br>This is a one-liner note.<hgroup><h4>This is `<h4>` text.</h4><p>This is `<p>` text.</p></hgroup>

> [!NOTE]<br>This is a one-liner note.<br><hgroup><br><h4>This is `<h4>` text.</h4><br><p>This is `<p>` text.</p><br></hgroup>

> [!NOTE]<br><hgroup><h4>This is `<h4>` text.</h4><p>This is `<p>` text.</p></hgroup>

> [!NOTE]<hgroup><h4>This is `<h4>` text.</h4><p>This is `<p>` text.</p></hgroup>

> [!NOTE]<hgroup><h4>This is `<h4>` text.</h4><p>This is `<p>` text.</p><p>second `<p>`</p></hgroup>

> [!NOTE]<hgroup><h4>This is `<h4>` text.</h4></hgroup>

> [!NOTE]<hgroup><h4>This is `<h4>` text.</h4><h5>This is `<h5>` text.</h5></hgroup>

> [!NOTE]<hgroup><h4>This is `<h4>` text.</h4><h5>This is `<h5>` text.</h5><p>This is `<p>` text.</p></hgroup>

### alerts in `<hgroup>`

<hgroup>
> [!NOTE]
> This is a note.
</hgroup>

<hgroup>

> [!NOTE]
> This is a note.

</hgroup>

<hgroup>
> [!NOTE]<br>This is a one-liner note.
</hgroup>

<hgroup>

> [!NOTE]<br>This is a one-liner note.

</hgroup>

<hgroup>

> [!NOTE]
> This is a note.
> <h4>This is <code>&lt;h4&gt;</code> text.</h4>
> <p>This is <code>&lt;p&gt;</code> text.</p>

</hgroup>

<hgroup>

> [!NOTE]
> <h4>This is <code>&lt;h4&gt;</code> text.</h4>
> <p>This is <code>&lt;p&gt;</code> text.</p>

</hgroup>

<hgroup>

> [!NOTE]
> <h4>This is <code>&lt;h4&gt;</code> text.</h4>
> <p>This is <code>&lt;p&gt;</code> text.</p>
> <p>second <code>&lt;p&gt;</code></p>

</hgroup>

<hgroup>

> [!NOTE]
> <h4>This is <code>&lt;h4&gt;</code> text.</h4>

</hgroup>

<hgroup>

> [!NOTE]
> <h4>This is <code>&lt;h4&gt;</code> text.</h4>
> <h5>This is <code>&lt;h5&gt;</code> text.</h5>

</hgroup>

<hgroup>

> [!NOTE]
> <h4>This is <code>&lt;h4&gt;</code> text.</h4>
> <h5>This is <code>&lt;h5&gt;</code> text.</h5>
> <p>This is <code>&lt;p&gt;</code> text.</p>

</hgroup>

<hgroup>

> [!NOTE]<br>This is a note.<h4>This is `<h4>` text.</h4><p>This is `<p>` text.</p>

</hgroup>

<hgroup>

> [!NOTE]<h4>This is `<h4>` text.</h4><p>This is `<p>` text.</p>

</hgroup>

<hgroup>

> [!NOTE]<h4>This is `<h4>` text.</h4><p>This is `<p>` text.</p><p>second `<p>`</p>

</hgroup>

<hgroup>

> [!NOTE]<h4>This is `<h4>` text.</h4>

</hgroup>

<hgroup>

> [!NOTE]<h4>This is `<h4>` text.</h4><h5>This is `<h5>` text.</h5>

</hgroup>

<hgroup>

> [!NOTE]<h4>This is `<h4>` text.</h4><h5>This is `<h5>` text.</h5><p>This is `<p>` text.</p>

</hgroup>

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

~~~
fn main () {
  println!("Hello, World!");
}
~~~

fenced code block with syntax highlighting
```rust
fn main () {
  println!("Hello, World!");
}
```

~~~rust
fn main () {
  println!("Hello, World!");
}
~~~

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
> This is a note.
> ~~~
> fn main() {
>   println!("Hello, World!");
> }
> ~~~

> [!NOTE]
> ```
> fn main() {
>   println!("Hello, World!");
> }
> ```

> [!NOTE]
> ~~~
> fn main() {
>   println!("Hello, World!");
> }
> ~~~

> [!NOTE]
> This is a note.
> ```rust
> fn main() {
>   println!("Hello, World!");
> }
> ```

> [!NOTE]
> This is a note.
> ~~~rust
> fn main() {
>   println!("Hello, World!");
> }
> ~~~

> [!NOTE]
> ```rust
> fn main() {
>   println!("Hello, World!");
> }
> ```

> [!NOTE]
> ~~~rust
> fn main() {
>   println!("Hello, World!");
> }
> ~~~

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

> [!NOTE]
> This is a note.
> ~~~math
> \LaTeX
> ~~~

> [!NOTE]
> ~~~math
> \LaTeX
> ~~~

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
> This is a note.
> | Header |
> | --- |

> [!NOTE]
> | Header |
> | --- |

> [!NOTE]
> | Header |
> | --- |
> | Content |

> [!NOTE]
> |a|
> |-|

> [!NOTE]
> |-|

> [!NOTE]
|-|

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

### with MathJax

> [!NOTE]
> | $\LaTeX$ |
> | --- |

> [!NOTE]
> | $$\LaTeX$$ |
> | --- |

> [!NOTE]
> | Header 1 | Header 2 |
> | --- | --- |
> | $\LaTeX$ | $$\LaTeX$$ |

> [!NOTE]
> | $\LaTeX$ | $$\LaTeX$$ |
> | --- | --- |
> | Content 1 | Content 2 |

> [!NOTE]
> | Left-aligned | Center-aligned | Right-aligned |
> | :--- | :---: | ---: |
> | $\LaTeX$ | $\LaTeX$ | $\LaTeX$ |
> | $$\LaTeX$$ | $$\LaTeX$$ | $$\LaTeX$$ |

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

<html>

> [!NOTE]
> This is a note.
> <head>
> This is inside <code>&lt;head&gt;</code>.
> </head>
> <body>
> This is inside <code>&lt;body&gt;</code>.
> </body>

</html>

<html>

> [!NOTE]<br>This is a one-liner note.<br><head>This is inside `<head>`.</head><br><body>This is inside `<body>`.</body>

</html>

## `<head>`

<head>head</head>

<head>
<title>
title
</title>
</head>

### `<head>` in alerts

> [!NOTE]
> This is a note.
> <head>This is inside <code>&lt;head&gt;</code>.</head>

> [!NOTE]
> <head>This is inside <code>&lt;head&gt;</code>.</head>

> [!NOTE]<br>This is a one-liner note.<br><head>This is inside `<head>`.</head>

> [!NOTE]<br>This is a one-liner note.<head>This is inside `<head>`.</head>

> [!NOTE]<br><head>This is inside `<head>`.</head>

> [!NOTE]
> <head>
> This is inside <code>&lt;head&gt;</code>.
> </head>

> [!NOTE]
> <head>
> <title>
> This is inside <code>&lt;head&gt;&lt;title&gt;</code>.
> </title>
> </head>

### alerts in `<head>`

<head>
> [!NOTE]
> This is a note.
</head>

<head>

> [!NOTE]
> This is a note.

</head>

<head>
> [!NOTE]
> This is a note.
> <head>
> This is inside <code>&lt;head&gt;</code>.
> </head>
</head>

<head>

> [!NOTE]
> This is a note.
> <head>
> This is inside <code>&lt;head&gt;</code>.
> </head>

</head>

<head>
> [!NOTE]<br>This is a one-liner note.
</head>

<head>

> [!NOTE]<br>This is a one-liner note.

</head>

<head>> [!NOTE]<br>This is a one-liner note.</head>

<head>
> [!NOTE]<br>This is a one-liner note.<br><head>This is inside <code>&lt;head&gt;</code>.</head>
</head>

<head>

> [!NOTE]<br>This is a one-liner note.<br><head>This is inside `<head>`.</head>

</head>

<head>> [!NOTE]<br>This is a one-liner note.<br><head>This is inside <code>&lt;head&gt;</code>.</head></head>

## `<title>` (not supported)

<title>title</title>

<title>
<p>
paragraph test
</p>
</title>

### `<title>` in alerts

> [!NOTE]
> This is a note.
> <title>This is inside <code>&lt;title&gt;</code>.</title>

> [!NOTE]
> <title>This is inside <code>&lt;title&gt;</code>.</title>

> [!NOTE]<br>This is a one-liner note.<br><title>This is inside `<title>`.</title>

> [!NOTE]<br>This is a one-liner note.<title>This is inside `<title>`.</title>

> [!NOTE]<br><title>This is inside `<title>`.</title>

> [!NOTE]
> <title>
> This is inside <code>&lt;title&gt;</code>.
> </title>

> [!NOTE]
> <title>
> <p>
> This is inside <code>&lt;title&gt;&lt;p&gt;</code>.
> </p>
> </title>

### alerts in `<title>`

<title>
> [!NOTE]
> This is a note.
</title>

<title>

> [!NOTE]
> This is a note.

</title>

<title>
> [!NOTE]
> This is a note.
> <title>
> This is inside <code>&lt;title&gt;</code>.
> </title>
</title>

<title>

> [!NOTE]
> This is a note.
> <title>
> This is inside <code>&lt;title&gt;</code>.
> </title>

</title>

<title>
> [!NOTE]<br>This is a one-liner note.
</title>

<title>

> [!NOTE]<br>This is a one-liner note.

</title>

<title>> [!NOTE]<br>This is a one-liner note.</title>

<title>
> [!NOTE]<br>This is a one-liner note.<br><title>This is inside <code>&lt;title&gt;</code>.</title>
</title>

<title>

> [!NOTE]<br>This is a one-liner note.<br><title>This is inside `<title>`.</title>

</title>

<title>> [!NOTE]<br>This is a one-liner note.<br><title>This is inside <code>&lt;title&gt;</code>.</title></title>

## `<meta>`

<meta charset="utf-8" />

<meta>meta test</meta>

> [!NOTE]
> This is a note.
> <meta charset="utf-8" />

> [!NOTE]
> <meta charset="utf-8" />

> [!NOTE]<br>This is a one-liner note.<br><meta charset="utf-8" />

> [!NOTE]<br>This is a one-liner note.<meta charset="utf-8" />

> [!NOTE]<br><meta charset="utf-8" />

> [!NOTE]
> This is a note.
> <meta>This is inside <code>&lt;meta&gt;</code>.</meta>

> [!NOTE]
> <meta>This is inside <code>&lt;meta&gt;</code>.</meta>

> [!NOTE]<br>This is a one-liner note.<br><meta>This is inside `<meta>`.</meta>

> [!NOTE]<br>This is a one-liner note.<meta>This is inside `<meta>`.</meta>

> [!NOTE]<br><meta>This is inside `<meta>`.</meta>

## `<base>`

<base href="https://github.com/" />

<base>base test</base>

> [!NOTE]
> This is a note.
> <base href="https://github.com/" />

> [!NOTE]
> <base href="https://github.com/" />

> [!NOTE]<br>This is a one-liner note.<br><base href="https://github.com/" />

> [!NOTE]<br>This is a one-liner note.<base href="https://github.com/" />

> [!NOTE]<br><base href="https://github.com/" />

> [!NOTE]
> This is a note.
> <base>This is inside <code>&lt;base&gt;</code>.</base>

> [!NOTE]
> <base>This is inside <code>&lt;base&gt;</code>.</base>

> [!NOTE]<br>This is a one-liner note.<br><base>This is inside `<base>`.</base>

> [!NOTE]<br>This is a one-liner note.<base>This is inside `<base>`.</base>

> [!NOTE]<br><base>This is inside `<base>`.</base>

## `<link>`

<link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub" />

<link>link test</link>

> [!NOTE]
> This is a note.
> <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub" />

> [!NOTE]
> <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub" />

> [!NOTE]<br>This is a one-liner note.<br><link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub" />

> [!NOTE]<br>This is a one-liner note.<link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub" />

> [!NOTE]<br><link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub" />

> [!NOTE]
> This is a note.
> <link>This is inside <code>&lt;link&gt;</code>.</link>

> [!NOTE]
> <link>This is inside <code>&lt;link&gt;</code>.</link>

> [!NOTE]<br>This is a one-liner note.<br><link>This is inside `<link>`.</link>

> [!NOTE]<br>This is a one-liner note.<link>This is inside `<link>`.</link>

> [!NOTE]<br><link>This is inside `<link>`.</link>

## `<style>` (not supported)

<style>
  p {
    color: #26b72b;
  }
</style>

<p>paragraph</p>

### `<style>` in alerts

> [!NOTE]
> This is a note.
> <style>This is inside <code>&lt;style&gt;</code>.</style>

> [!NOTE]
> <style>This is inside <code>&lt;style&gt;</code>.</style>

> [!NOTE]<br>This is a one-liner note.<br><style>This is inside `<style>`.</style>

> [!NOTE]<br>This is a one-liner note.<style>This is inside `<style>`.</style>

> [!NOTE]<br><style>This is inside `<style>`.</style>

> [!NOTE]
> <style>
> This is inside <code>&lt;style&gt;</code>.
> </style>

> [!NOTE]
> This is a note.
> <style>
>   p {
>     color: red;
>   }
> </style>
> <p>This is a paragraph.</p>

### alerts in `<style>`

<style>
> [!NOTE]
> This is a note.
</style>

<style>

> [!NOTE]
> This is a note.

</style>

<style>
> [!NOTE]
> This is a note.
> <style>
> This is inside <code>&lt;style&gt;</code>.
> </style>
</style>

<style>

> [!NOTE]
> This is a note.
> <style>
> This is inside <code>&lt;style&gt;</code>.
> </style>

</style>

<style>
> [!NOTE]<br>This is a one-liner note.
</style>

<style>

> [!NOTE]<br>This is a one-liner note.

</style>

<style>> [!NOTE]<br>This is a one-liner note.</style>

<style>
> [!NOTE]<br>This is a one-liner note.<br><style>This is inside <code>&lt;style&gt;</code>.</style>
</style>

<style>

> [!NOTE]<br>This is a one-liner note.<br><style>This is inside `<style>`.</style>

</style>

<style>> [!NOTE]<br>This is a one-liner note.<br><style>This is inside <code>&lt;style&gt;</code>.</style></style>

## `<body>`

<body>body</body>

<body>
<p>
body paragraph
</p>
</body>

### `<body>` in alerts

> [!NOTE]
> This is a note.
> <body>This is inside <code>&lt;body&gt;</code>.</body>

> [!NOTE]
> <body>This is inside <code>&lt;body&gt;</code>.</body>

> [!NOTE]<br>This is a one-liner note.<br><body>This is inside `<body>`.</body>

> [!NOTE]<br>This is a one-liner note.<body>This is inside `<body>`.</body>

> [!NOTE]<br><body>This is inside `<body>`.</body>

> [!NOTE]
> <body>
> This is inside <code>&lt;body&gt;</code>.
> </body>

> [!NOTE]
> <body>
> <p>
> This is inside <code>&lt;body&gt;&lt;p&gt;</code>.
> </p>
> </body>

### alerts in `<body>`

<body>
> [!NOTE]
> This is a note.
</body>

<body>

> [!NOTE]
> This is a note.

</body>

<body>
> [!NOTE]
> This is a note.
> <body>
> This is inside <code>&lt;body&gt;</code>.
> </body>
</body>

<body>

> [!NOTE]
> This is a note.
> <body>
> This is inside <code>&lt;body&gt;</code>.
> </body>

</body>

<body>
> [!NOTE]<br>This is a one-liner note.
</body>

<body>

> [!NOTE]<br>This is a one-liner note.

</body>

<body>> [!NOTE]<br>This is a one-liner note.</body>

<body>
> [!NOTE]<br>This is a one-liner note.<br><body>This is inside <code>&lt;body&gt;</code>.</body>
</body>

<body>

> [!NOTE]<br>This is a one-liner note.<br><body>This is inside `<body>`.</body>

</body>

<body>> [!NOTE]<br>This is a one-liner note.<br><body>This is inside <code>&lt;body&gt;</code>.</body></body>

<body>

> [!NOTE]
> This is a note.
> <p>
> This is inside <code>&lt;p&gt;</code>.
> </p>

</body>

<body>

> [!NOTE]<br>This is a one-liner note.<br><p>This is inside `<p>`.</p>

</body>

## `<address>`

<address>address</address>

<address>
<a href="mailto:CRISPR-Cas@chemist.com">CRISPR-Cas@chemist.com</a>
</address>

### `<address>` in alerts

> [!NOTE]
> This is a note.
> <address>This is inside <code>&lt;address&gt;</code>.</address>

> [!NOTE]
> <address>This is inside <code>&lt;address&gt;</code>.</address>

> [!NOTE]<br>This is a one-liner note.<br><address>This is inside `<address>`.</address>

> [!NOTE]<br>This is a one-liner note.<address>This is inside `<address>`.</address>

> [!NOTE]<br><address>This is inside `<address>`.</address>

> [!NOTE]
> <address>
> This is inside <code>&lt;address&gt;</code>.
> </address>

> [!NOTE]
> <address>
> This is inside <code>&lt;address&gt;</code>.
> <a>
> This is inside <code>&lt;address&gt;&lt;a&gt;</code>.
> </a>
> </address>

> [!NOTE]<br><address>This is inside `<address>`.<a>This is inside `<address><a>`.</a></address>

### alerts in `<address>`

<address>
> [!NOTE]
> This is a note.
</address>

<address>

> [!NOTE]
> This is a note.

</address>

<address>
> [!NOTE]
> This is a note.
> <a>
> This is inside <code>&lt;a&gt;</code>.
> </a>
</address>

<address>

> [!NOTE]
> This is a note.
> <a>
> This is inside <code>&lt;a&gt;</code>.
> </a>

</address>

<address>
> [!NOTE]<br>This is a one-liner note.
</address>

<address>

> [!NOTE]<br>This is a one-liner note.

</address>

<address>> [!NOTE]<br>This is a one-liner note.</address>

<address>
> [!NOTE]<br>This is a one-liner note.<br><a>This is inside <code>&lt;a&gt;</code>.</a>
</address>

<address>

> [!NOTE]<br>This is a one-liner note.<br><a>This is inside `<a>`.</a>

</address>

<address>> [!NOTE]<br>This is a one-liner note.<br><a>This is inside <code>&lt;a&gt;</code>.</a></address>

## `<article>`

<article>article</article>

<article>
main article
<article>
child article
</article>
</article>

### `<article>` in alerts

> [!NOTE]
> This is a note.
> <article>This is inside <code>&lt;article&gt;</code>.</article>

> [!NOTE]
> <article>This is inside <code>&lt;article&gt;</code>.</article>

> [!NOTE]<br>This is a one-liner note.<br><article>This is inside `<article>`.</article>

> [!NOTE]<br>This is a one-liner note.<article>This is inside `<article>`.</article>

> [!NOTE]<br><article>This is inside `<article>`.</article>

> [!NOTE]<article>This is inside `<article>`.</article>

> [!NOTE]
> <article>
> This is inside <code>&lt;article&gt;</code>.
> </article>

> [!NOTE]
> <article>
> This is inside <code>&lt;article&gt;</code>.
> <article>
> This is inside <code>&lt;article&gt;&lt;article&gt;</code>.
> </article>
> </article>

> [!NOTE]<br><article>This is inside `<article>`.<article>This is inside `<article><article>`.</article></article>

### alerts in `<article>`

<article>
> [!NOTE]
> This is a note.
</article>

<article>

> [!NOTE]
> This is a note.

</article>

<article>
> [!NOTE]
> This is a note.
> <article>
> This is inside <code>&lt;article&gt;</code>.
> </article>
</article>

<article>

> [!NOTE]
> This is a note.
> <article>
> This is inside <code>&lt;article&gt;</code>.
> </article>

</article>

<article>
> [!NOTE]<br>This is a one-liner note.
</article>

<article>

> [!NOTE]<br>This is a one-liner note.

</article>

<article>> [!NOTE]<br>This is a one-liner note.</article>

<article>
> [!NOTE]<br>This is a one-liner note.<br><article>This is inside <code>&lt;article&gt;</code>.</article>
</article>

<article>

> [!NOTE]<br>This is a one-liner note.<br><article>This is inside `<article>`.</article>

</article>

<article>> [!NOTE]<br>This is a one-liner note.<br><article>This is inside <code>&lt;article&gt;</code>.</article></article>

## `<aside>`

<aside>aside</aside>

<article>
<p>before</p>
<aside>
<p>aside</p>
</aside>
<p>after</p>
</article>

### `<aside>` in alerts

> [!NOTE]
> This is a note.
> <aside>This is inside <code>&lt;aside&gt;</code>.</aside>

> [!NOTE]
> <aside>This is inside <code>&lt;aside&gt;</code>.</aside>

> [!NOTE]<br>This is a one-liner note.<br><aside>This is inside `<aside>`.</aside>

> [!NOTE]<br>This is a one-liner note.<aside>This is inside `<aside>`.</aside>

> [!NOTE]<br><aside>This is inside `<aside>`.</aside>

> [!NOTE]<aside>This is inside `<aside>`.</aside>

> [!NOTE]
> <aside>
> This is inside <code>&lt;aside&gt;</code>.
> </aside>

> [!NOTE]
> <aside>
> <p>
> This is inside <code>&lt;aside&gt;&lt;p&gt;</code>.
> </p>
> </aside>

> [!NOTE]
> <article>
> <p>
> This is inside <code>&lt;article&gt;&lt;p&gt;</code> before.
> </p>
> <aside>
> <p>
> This is inside <code>&lt;article&gt;&lt;aside&gt;&lt;p&gt;</code>.
> </p>
> </aside>
> <p>
> This is inside <code>&lt;article&gt;&lt;p&gt;</code> after.
> </p>
> </article>

> [!NOTE]<br><aside><p>This is inside `<aside><p>`.</p></aside>

> [!NOTE]<br><article><p>This is inside `<article><p>` before.</p><aside><p>This is inside `<article><aside><p>`.</p></aside><p>This is inside `<article><p>` after.</p></article>

### alerts in `<aside>`

<aside>
> [!NOTE]
> This is a note.
</aside>

<aside>

> [!NOTE]
> This is a note.

</aside>

<aside>
> [!NOTE]
> This is a note.
> <aside>
> This is inside <code>&lt;aside&gt;</code>.
> </aside>
</aside>

<aside>

> [!NOTE]
> This is a note.
> <aside>
> This is inside <code>&lt;aside&gt;</code>.
> </aside>

</aside>

<aside>
> [!NOTE]<br>This is a one-liner note.
</aside>

<aside>

> [!NOTE]<br>This is a one-liner note.

</aside>

<aside>> [!NOTE]<br>This is a one-liner note.</aside>

<aside>
> [!NOTE]<br>This is a one-liner note.<br><aside>This is inside <code>&lt;aside&gt;</code>.</aside>
</aside>

<aside>

> [!NOTE]<br>This is a one-liner note.<br><aside>This is inside `<aside>`.</aside>

</aside>

<aside>> [!NOTE]<br>This is a one-liner note.<br><aside>This is inside <code>&lt;aside&gt;</code>.</aside></aside>

<aside>

> [!NOTE]<aside>This is inside `<aside>`.</aside>

</aside>

<article>

> [!NOTE]
> This is a note.
> <aside>
> This is inside <code>&lt;aside&gt;</code>.
> </aside>

</article>

<article>

> [!NOTE]<br>This is a one-liner note.<br><aside>This is inside `<aside>`.</aside>

</article>

<article>

<p>before</p>

> [!NOTE]
> This is a note.
> <aside>
> <p>
> This is inside <code>&lt;aside&gt;&lt;p&gt;</code>.
> </p>
> </aside>

<p>after</p>

</article>

<article>

<p>before</p>

> [!NOTE]<br>This is a one-liner note.<br><aside><p>This is inside `<aside><p>`.</p></aside>

<p>after</p>

</article>

<article>

<p>before</p>

<aside>

<p>

> [!NOTE]
> This is a note.

</p>

</aside>

<p>after</p>

</article>

<article>

<p>before</p>

<aside>

<p>

> [!NOTE]<br>This is a one-liner note.

</p>

</aside>

<p>after</p>

</article>


## `<header>`

<header>header</header>

<header>
<h4>Page Title</h4>
<img src="https://github.com/fluidicon.png" alt="GitHub fluid icon" />
</header>

### `<header>` in alerts

> [!NOTE]
> This is a note.
> <header>This is inside <code>&lt;header&gt;</code>.</header>

> [!NOTE]
> <header>This is inside <code>&lt;header&gt;</code>.</header>

> [!NOTE]<br>This is a one-liner note.<br><header>This is inside `<header>`.</header>

> [!NOTE]<br>This is a one-liner note.<header>This is inside `<header>`.</header>

> [!NOTE]<br><header>This is inside `<header>`.</header>

> [!NOTE]
> <header>
> This is inside <code>&lt;header&gt;</code>.
> </header>

> [!NOTE]
> <header>
> <h4>
> This is inside <code>&lt;header&gt;&lt;h4&gt;</code>.
> </h4>
> <img src="https://github.com/fluidicon.png" alt="GitHub fluid icon" />
> </header>

### alerts in `<header>`

<header>
> [!NOTE]
> This is a note.
</header>

<header>

> [!NOTE]
> This is a note.

</header>

<header>
> [!NOTE]
> This is a note.
> <header>
> This is inside <code>&lt;header&gt;</code>.
> </header>
</header>

<header>

> [!NOTE]
> This is a note.
> <header>
> This is inside <code>&lt;header&gt;</code>.
> </header>

</header>

<header>
> [!NOTE]<br>This is a one-liner note.
</header>

<header>

> [!NOTE]<br>This is a one-liner note.

</header>

<header>> [!NOTE]<br>This is a one-liner note.</header>

<header>
> [!NOTE]<br>This is a one-liner note.<br><header>This is inside <code>&lt;header&gt;</code>.</header>
</header>

<header>

> [!NOTE]<br>This is a one-liner note.<br><header>This is inside `<header>`.</header>

</header>

<header>> [!NOTE]<br>This is a one-liner note.<br><header>This is inside <code>&lt;header&gt;</code>.</header></header>

<header>

> [!NOTE]
> This is a note.
> <h4>
> This is inside <code>&lt;h4&gt;</code>.
> </h4>

</header>

<header>

> [!NOTE]<br>This is a one-liner note.<br><h4>This is inside `<h4>`.</h4>

</header>

## `<footer>`

<footer>footer</footer>

<footer>
<p>&copy; 2024 sinsukehlab</p>
</footer>

### `<footer>` in alerts

> [!NOTE]
> This is a note.
> <footer>This is inside <code>&lt;footer&gt;</code>.</footer>

> [!NOTE]
> <footer>This is inside <code>&lt;footer&gt;</code>.</footer>

> [!NOTE]<br>This is a one-liner note.<br><footer>This is inside `<footer>`.</footer>

> [!NOTE]<br>This is a one-liner note.<footer>This is inside `<footer>`.</footer>

> [!NOTE]<br><footer>This is inside `<footer>`.</footer>

> [!NOTE]
> <footer>
> This is inside <code>&lt;footer&gt;</code>.
> </footer>

> [!NOTE]
> <footer>
> <p>
> This is inside <code>&lt;footer&gt;&lt;p&gt;</code>.
> </p>
> </footer>

### alerts in `<footer>`

<footer>
> [!NOTE]
> This is a note.
</footer>

<footer>

> [!NOTE]
> This is a note.

</footer>

<footer>
> [!NOTE]
> This is a note.
> <footer>
> This is inside <code>&lt;footer&gt;</code>.
> </footer>
</footer>

<footer>

> [!NOTE]
> This is a note.
> <footer>
> This is inside <code>&lt;footer&gt;</code>.
> </footer>

</footer>

<footer>
> [!NOTE]<br>This is a one-liner note.
</footer>

<footer>

> [!NOTE]<br>This is a one-liner note.

</footer>

<footer>> [!NOTE]<br>This is a one-liner note.</footer>

<footer>
> [!NOTE]<br>This is a one-liner note.<br><footer>This is inside <code>&lt;footer&gt;</code>.</footer>
</footer>

<footer>

> [!NOTE]<br>This is a one-liner note.<br><footer>This is inside `<footer>`.</footer>

</footer>

<footer>> [!NOTE]<br>This is a one-liner note.<br><footer>This is inside <code>&lt;footer&gt;</code>.</footer></footer>

<footer>

> [!NOTE]
> This is a note.
> <p>
> This is inside <code>&lt;p&gt;</code>.
> </p>

</footer>

<footer>

> [!NOTE]<br>This is a one-liner note.<br><p>This is inside `<p>`.</p>

</footer>

## `<main>`

<main>main</main>

<main>
<p>main paragraph</p>
</main>

### `<main>` in alerts

> [!NOTE]
> This is a note.
> <main>This is inside <code>&lt;main&gt;</code>.</main>

> [!NOTE]
> <main>This is inside <code>&lt;main&gt;</code>.</main>

> [!NOTE]<br>This is a one-liner note.<br><main>This is inside `<main>`.</main>

> [!NOTE]<br>This is a one-liner note.<main>This is inside `<main>`.</main>

> [!NOTE]<br><main>This is inside `<main>`.</main>

> [!NOTE]
> <main>
> This is inside <code>&lt;main&gt;</code>.
> </main>

> [!NOTE]
> <main>
> <p>
> This is inside <code>&lt;main&gt;&lt;p&gt;</code>.
> </p>
> </main>

### alerts in `<main>`

<main>
> [!NOTE]
> This is a note.
</main>

<main>

> [!NOTE]
> This is a note.

</main>

<main>
> [!NOTE]
> This is a note.
> <main>
> This is inside <code>&lt;main&gt;</code>.
> </main>
</main>

<main>

> [!NOTE]
> This is a note.
> <main>
> This is inside <code>&lt;main&gt;</code>.
> </main>

</main>

<main>
> [!NOTE]<br>This is a one-liner note.
</main>

<main>

> [!NOTE]<br>This is a one-liner note.

</main>

<main>> [!NOTE]<br>This is a one-liner note.</main>

<main>
> [!NOTE]<br>This is a one-liner note.<br><main>This is inside <code>&lt;main&gt;</code>.</main>
</main>

<main>

> [!NOTE]<br>This is a one-liner note.<br><main>This is inside `<main>`.</main>

</main>

<main>> [!NOTE]<br>This is a one-liner note.<br><main>This is inside <code>&lt;main&gt;</code>.</main></main>

<main>

> [!NOTE]
> This is a note.
> <p>
> This is inside <code>&lt;p&gt;</code>.
> </p>

</main>

<main>

> [!NOTE]<br>This is a one-liner note.<br><p>This is inside `<p>`.</p>

</main>
