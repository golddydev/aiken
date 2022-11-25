# Blocks

If statements

```gleam
if condition {

} else {

}
```

Case Patterns

```gleam
when color is {
    Green -> "Success."
    Blue -> "Warning."
    Red -> "Error!"
}
```

Let bindings with blocks

```gleam
let num = -5
let absNum = if num>=0 {num} else {-num}

let message = when color is {
    Green -> "Success."
    Blue -> "Warning."
    Red -> "Error!"
}
```

Since everything is secretly a function, the last statement in any block is implicitly its return.