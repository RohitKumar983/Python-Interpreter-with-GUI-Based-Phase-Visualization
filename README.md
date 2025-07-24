
# Python Mini-Compiler/Interpreter

A Python-based mini-compiler/interpreter with a Tkinter GUI that demonstrates various compiler phases including Lexical Analysis, Syntax & AST Analysis, Semantic Analysis, Intermediate Code Generation, Code Optimization, and Code Generation.

## Features

- Interactive GUI with code editor and output display
- Support for Python-like syntax including:
  - Variables and assignments
  - Arithmetic operations
  - Control structures (if-else, while, for loops)
  - Function definitions and calls
  - Lists and string operations
  - Error handling (try-except)
  - Built-in functions (print, len, range)

## Project Structure

```
.
├── ast_nodes.py      # AST node definitions
├── lexer.py         # Lexical analyzer
├── myparser.py      # Parser implementation
├── intrepreter.py   # Interpreter implementation
├── script.py        # Main GUI application
├── requirements.txt # Project dependencies
└── README.md        # This file
```

## Setup and Installation

1. Make sure you have Python 3.7+ installed
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   python script.py
   ```

## Usage

1. Launch the application
2. Choose from the main options:
   - Learn Python
   - Test Your Skills
   - Optimize Code
   - Compiler Phases
3. Write your code in the editor
4. View the output and analysis in the respective panels

## Compiler Phases

1. **Lexical Analysis**: Tokenizes input code
2. **Syntax & AST Analysis**: Builds Abstract Syntax Tree
3. **Semantic Analysis**: Type checking and validation
4. **Intermediate Code Generation**: Generates three-address code
5. **Code Optimization**: Performs optimizations like constant folding
6. **Code Generation**: Produces final output

## Notes

- The interpreter supports a subset of Python features
- Error messages are displayed in the output panel
- The GUI provides real-time feedback for code analysis 
