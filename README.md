# cwl (C wrapper lang)
A language that's pretty much C99, but aims to fix some of its memory-safety shortcomings. The output is source files in C89.

# TODO
- [ ] Datatypes for ease of working
- [ ] Memory management
- [ ] Tokenizer
- [ ] Parser
  - [ ] Stage 1 -- Overall structure (w/o parsing expressions yet)
  - [ ] Stage 2 -- Expressions
- [ ] Checker (Find errors)
- [ ] Translator (Generate C89 code from the AST)

# Notes
- The project is written in C89 for maximum portability
- No recursion
