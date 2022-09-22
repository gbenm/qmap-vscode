# qmap
Enables syntax highlight in strings using `/*qmap*/`
after or before opening a string (without spaces), or when
using `qmap(string)` function.

## Examples
```javascript
/** Before */
/* qmap */``
/* qmap */''
/* qmap */""
/*qmap*/""

/** After */
`/* qmap */`
'/* qmap */'
"/* qmap */"
"/*qmap*/"

/** function */
qmap(``)
qmap('')
qmap("")
qmap(``, {
  functions: {
    add: (a, b) => a + b
  }
})
```

## Features

- Highlighting
