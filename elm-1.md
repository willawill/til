#Day 1

- Elm is strongly typed.
- To concat two strings: `"4" ++ "5"`
- Single assignment language, no edit in place array

- Case pattern matching:
```
list = [1,2,3]
case list of\
head::tail->tail\
[]->[]
```

- User `type` to define a data type.

```
> type Color = All | Active
> type Color = Black | White
> type Piece = Knight | Queen
> type CP = CP Color Piece
> CP Black Knight
CP Black Knight : Repl.CP
```

- I think elm follows the python identation.

```
> f n = \
|   if n < 1 then 1\
|     else n * 2
<function> : number -> number'
```