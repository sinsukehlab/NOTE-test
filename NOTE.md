# `[!NOTE]` test

## Simple alerts
> [!NOTE]
> This is a note.

> [!TIP]
> This is a tip.

> [!IMPORTANT]
> Crutial information comes here.

> [!CAUTION]
> Negative potential consequences of an action.

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

> This also breaks the syntax.\
> [!NOTE]
> This is a note.

> This also breaks the syntax.
> 
> [!NOTE]
> This is a note.

> [!NOTE]
> 

> [!NOTE]<br>This is a one-liner note.

> [!NOTE]<br>
> This is a note.

## nested alerts
> [!NOTE]
> This is a note.
>> [!NOTE]
>> This is a note (broken).

> [!NOTE]
> This is a note.
>>
>> [!NOTE]
>> This is a note (broken).

> [!NOTE]
> This is a note.
>>
> [!NOTE]
> This won't be shown.

> [!NOTE]
>
>> [!NOTE]
>> This is a note (broken).

> [!NOTE]
>>
>> [!NOTE]
>> This is a note (broken).

> [!NOTE]
>>
> [!NOTE]
> This won't be shown.

> This won't be shown.
>> [!NOTE]
>> This is a note.

> This won't be shown.
>
>> [!NOTE]
>> This is a note.

> This won't be shown.
>>
>> [!NOTE]
>> This is a note.

> This is a quote.
>>
> [!NOTE]
> This is a note (broken).

## list

### alerts in lists
- This is a bullet list with `-`.
  > [!NOTE]
  > This is a note.

- > [!NOTE]
  > This is a note.

+ This is a bullet list with `+`.
  > [!NOTE]
  > This is a note.

+ > [!NOTE]
  > This is a note.

* This is a bullet list with `*`.
  > [!NOTE]
  > This is a note.

* > [!NOTE]
  > This is a note.

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

1. > [!NOTE]
   > This is a note.
<br>

1. This is an ordered list.
1. > [!NOTE]
   > This is a note.
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

+ [ ] This is a task list (`+`).
  > [!NOTE]
  > This is a note.

+ [x] This is a task list with a checked task (`+`).
  > [!NOTE]
  > This is a note.

* [ ] This is a task list (`*`).
  > [!NOTE]
  > This is a note.

* [x] This is a task list with a checked task (`*`).
  > [!NOTE]
  > This is a note.

1. [ ] This is a task list. The number `1. ` won't be shown.
   > [!NOTE]
   > This is a note.
<br>

1. [x] This is a task list with a checked task. The number `1. ` won't be shown.
   > [!NOTE]
   > This is a note.

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

## code block
simple code block
```
fn main () {
  println!("Hello, World!");
}
```

code block with syntax highlighting
```rust
fn main () {
  println!("Hello, World!");
}
```

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

## table
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
