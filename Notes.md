# Compiler Tool Chain

- Preprocessor => performs basic code manipulation
  - ex. #include < iostream > is a directive that instructs the preprocessor to include information about the iostream library directly into the program's source code.
- Compiler => reads a translation unit and generates an object file (these contain object code)
  - These files contain data and instructions in an intermediate format
- Linker => generates programs from object files
  - responsible for finding the libraries you've included within your source code

# Type System

- Object-oriented language => objects are abstractions with state and behavior
- The collection of behaviors and states describing an object is called its => type
- Strongly typed language => each object has a predefined data type
  - int -> the int object can store whole numbers (its state) and support many math operations (its behavior)
