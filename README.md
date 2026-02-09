# Cygni Language Support for VS Code

Provides language support for the **Cygni** programming language (.cyg files).

## Features

### Syntax Highlighting

Full TextMate grammar for Cygni source files, including:

- Keywords (`func`, `var`, `module`, `struct`, `if`, `else`, `while`, `return`, `native`)
- Built-in types (`Int`, `Long`, `Float`, `Double`, `Bool`, `Char`, `String`, `Void`)
- String and character literals (with escape sequences)
- Numeric literals (integer, float, hex `0x`, binary `0b`)
- Operators and punctuation
- Single-line comments (`//`)
- Annotations (`@NativeFunction`, `@EntryPoint`)
- Function declarations

### Snippets

| Prefix    | Description                     |
| --------- | ------------------------------- |
| `module`  | Define a new module             |
| `func`    | Define a new function           |
| `main`    | Define the main entry function  |
| `struct`  | Define a new structure          |
| `var`     | Declare a variable              |
| `if`      | If-else statement               |
| `while`   | While loop                      |
| `native`  | Native function declaration     |

### Bracket Matching and Auto-closing

Automatic bracket matching, auto-closing pairs, and surrounding pairs for `{}`, `[]`, `()`, `""`, and `''`.

### Indentation Rules

Smart indentation after `{` and dedentation after `}`.

## File Extensions

- `.cyg` -- Cygni source files

## Requirements

None. This is a standalone language support extension.

## Getting Started

1. Install the extension.
2. Open any `.cyg` file to see syntax highlighting in action.
3. Type a snippet prefix (e.g., `func`) and press Tab to expand.

## About Cygni

Cygni is a statically-typed, expression-oriented programming language that compiles to Flint bytecode.
