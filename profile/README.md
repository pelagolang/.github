<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/pelagolang/pelago/main/assets/brand/logo/pelago-horizontal-dark.svg">
    <img alt="Pelago" src="https://raw.githubusercontent.com/pelagolang/pelago/main/assets/brand/logo/pelago-horizontal.svg" width="360">
  </picture>
</p>

<p align="center"><strong>A self-hosting systems language.</strong><br>Native code. No GC. No runtime.</p>

**Pelago** (from *pelagos*, Greek for "the open sea"; source files end in `.pel`) compiles to native code with its own backend, has no garbage collector and no runtime, and is memory safe through value semantics instead of a borrow checker. Errors are `result` values, absence is `none`, and integer overflow traps instead of wrapping.

```
fn sum_squares(n: int) -> int {
    var total = 0
    for i of 1..=n {
        total += i * i
    }
    return total
}
```

## Repositories

| Repository | What it is |
|---|---|
| [pelago](https://github.com/pelagolang/pelago) | The compiler, interpreter, formatter and language server (`pelago`), plus the design docs |
| [examples](https://github.com/pelagolang/examples) | Sample programs |
| [vscode-pelago](https://github.com/pelagolang/vscode-pelago) | VS Code extension: highlighting, snippets, language server |
| [zed-pelago](https://github.com/pelagolang/zed-pelago) | Zed extension |
| [tree-sitter-pelago](https://github.com/pelagolang/tree-sitter-pelago) | Tree-sitter grammar for Zed, Neovim and Helix |

## Start here

- Read the [README](https://github.com/pelagolang/pelago#readme) and the [roadmap](https://github.com/pelagolang/pelago/blob/main/ROADMAP.md).
- Take the [syntax tour](https://github.com/pelagolang/pelago/blob/main/examples/tour.pel).
- Contributing: see [CONTRIBUTING](https://github.com/pelagolang/.github/blob/main/CONTRIBUTING.md). Questions: [SUPPORT](https://github.com/pelagolang/.github/blob/main/SUPPORT.md).

Everything here is dual-licensed MIT OR Apache-2.0.
