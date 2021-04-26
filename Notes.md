# Compiler Tool Chain

- Preprocessor => performs basic code manipulation
  - ex. #include < iostream > is a directive that instructs the preprocessor to include information about the iostream library directly into the program's source code.
- Compiler => reads a translation unit and generates an object file (these contain object code)
  - These files contain data and instructions in an intermediate format
- Linker => generates programs from object files
  - responsible for finding the libraries you've included within your source code
