# Introduction to Compiler Design 2022 Fall Homeworks

## Homework 1: Scanner

Build a scanner using `lex` and `yacc`.

TODOs:
- [x] identifier
- [x] numeric literal
    - [x] integer
    - [x] floating points
    - [x] scientific notations
- [x] comments
    - [x] single line comment
    - [x] multiple line comment
- [x] string literal
- [x] directives
    - [x] `pragma`'s
- [ ] distinguish an `add_op` and positive sign.
    - This should be done in parser, not in scanner.