# Say hello to Kozeig

![Kozeig](https://img.shields.io/badge/language-kozeig-blue)
![Status](https://img.shields.io/badge/status-alpha-orange)

Kozeig (pronounced "koh-sig") is a programming language inspired by the Norwegian concept of "koselig" because code should feel comfortable and enjoyable to write.

## Why Kozeig?

After several abandoned language projects, I finally committed to creating something unique yet readable. Born from my journey through JavaScript, Python, C, and finally falling in love with Rust, Kozeig blends what I've learned along the way.

I built Kozeig to be:
- **Quick**: Compiles and interprets in under a second
- **Flexible**: Run with `koze run` or compile with `koze build`
- **Distinctive**: Curly braces for parameters, square brackets for blocks
- **Approachable**: Familiar concepts with a fresh syntax

## Current Status

Kozeig is young but already handles the fundamentals: functions, variables, recursion, control flow, and basic data types. The factorial example below represents what makes me proud of this project:

```koze
func pub factorial { n : number ! } [
    if { $n <= 1 } [
        1
    ] else [
        $n * call { factorial, $n - 1 }
    ]
]
```

Interested? Check out the [documentation]([SYNTAX.md](https://github.com/kozeig/kozeig/blob/main/SYNTAX.md)) or dive right in. Let's make programming a little cozier together.

---

Happy coding with ❤️ from the Kozeig Team!
