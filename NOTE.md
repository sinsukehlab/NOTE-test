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

> This also breaks the syntax here (different from comments).\
> [!NOTE]
> This is a note.

> This also breaks the syntax here.
> 
> [!NOTE]
> This is a note.

> [!NOTE]
> 

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

- [ ] This is a task list.
  > [!NOTE]
  > This is a note.

- [x] This is a task list with a checked task.
  > [!NOTE]
  > This is a note.

+ [ ] This is a task list.
  > [!NOTE]
  > This is a note.

+ [x] This is a task list with a checked task.
  > [!NOTE]
  > This is a note.

* [ ] This is a task list.
  > [!NOTE]
  > This is a note.

* [x] This is a task list with a checked task.
  > [!NOTE]
  > This is a note.
